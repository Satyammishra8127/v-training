<template>
<div>
    <h1>
        Two-way-binding
    </h1>
    <input type="text" v-model="count" />
            <h2>{{ count }}</h2>

</div>
</template>

    
<script>
export default {
    name: 'twowaybindingPage',
    data() {
        return {
            count:19
        }
    }

}
</script>

    
<style scoped>
h1 {
    color: purple;
}
</style>
