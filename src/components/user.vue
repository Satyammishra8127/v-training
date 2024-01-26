<template>
<div>
    <h2>
        {{ data.name }}
    </h2>
    <h2>
        {{ data.email }}
    </h2>
    <button v-on:click="getdata(data.name)">click</button>
</div>
</template>

<script>
export default {
    name: 'userPage',
    //props means = whatever data and variables are coming in.
    props: {
       data:Object,
       getdata:Function
    },
}
</script>

<style scoped>

</style>
