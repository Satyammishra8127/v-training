<template>
<div>
    <h1>
        Teacher :{{ name }}

    </h1>
</div>
</template>
   
<script>
export default {
    name: 'teacherpropsPage',
    props: {
        name: String
    }
}
</script>
   
<style scoped>
h1 {
    color: chocolate
}
</style>
