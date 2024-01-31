<template>
<div>
    <h1>
        Computed Property
    </h1>
    <h2>In-template expressions are very convenient,<br>
        but they are meant for simple operations.<br>
        Putting too much logic in your templates,<br>
        can make them bloated and hard to maintain.</h2>
    <h2>
        {{ getResult }}
    </h2>
</div>
</template>

<script>
export default {
    name: 'ComputedPROPERTYPage',
    data() {
        return {
            dollars: 100,
            rupeeVal: 70,
            discount: 10
        }
    },
    computed: {
        getResult() {
            return (this.dollars * this.rupeeVal) - this.discount;
        }
    }

}
</script>

<style scoped>
h1 {
    color: chocolate
}
h2{
    color: black;
}

</style>
