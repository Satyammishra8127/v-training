<template>
<div>
    <h1>
        Parent
    </h1>
    <child :getuser="getusername"/>
</div>
</template>

<script>
import child from './child.vue'
export default {
    name: 'parentPage',
    components:{
        child,
    },
    methods:{
        getusername(name){
            alert(name)
        }
    }
}
</script>
   
<style scoped>
h1 {
    color: purple;
}
</style>
