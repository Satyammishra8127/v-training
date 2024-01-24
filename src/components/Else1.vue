<template>
<div>
    <h1 v-if="show">
        if condition
    </h1>
    <h1 v-else>
        Else condition
    </h1>
 <button v-on:click="show=!show">Show</button>
</div>
</template>

<script>
export default {
    name: 'Else1Page',
    data() {
        return {
            show: false
        }
    }

}
</script>

<style scoped>
h1 {
    color: yellow;
}
</style>
