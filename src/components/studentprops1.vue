<template>
<div>
    <h1>Data</h1>
    <studentprops name="Satyam Mishra" />
    <teacherprops name="Pariwesh sir" />
</div>
</template>
   
<script>
import studentprops from './studentprops.vue'
import teacherprops from './teacherprops.vue'
export default {
    name: 'studentprops1Page',
    components: {
        studentprops,
        teacherprops
    }
}
</script>
    
<style scoped>
h1 {
    color: darkgoldenrod;
}
</style>
