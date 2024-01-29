<template>
<div>
    <h1>
        Child
    </h1>
    <button v-on:click="getuser(username)"></button>
</div>
</template>

    
<script>
 export default {
      name: 'childPage',
      data(){
        return{
            username:'Ram'
        }
      },
      props:{
        getuser:Function
      }

     }
</script>

    
<style scoped>
h1 {
    color: purple;
}
</style>
