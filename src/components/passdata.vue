<template>
<div>
    <h1>
        {{name}}
    </h1>
    <h2>
        {{user.name}}
    </h2>
</div>
</template>

<script>
export default {
    name: 'passdataPage',
    props: {
        name: String,
        user: Object
    }
}
</script>

<style scoped>
h1 {
    color: purple;
}
</style>
