<template>
<div>
    <h1 v-if="show">
        if condition
    </h1>
    <h1 v-else>
        Else condition
    </h1>
 <button v-on:click="show=!show">Show</button>
 <passdata name="satyam mishra" :user="user"/>
</div>
</template>

<script>
import passdata from './passdata.vue';
export default {
    name: 'Else1Page',
    components:{
      passdata
    },
    data() {
        return {
            show: false,
            user:{
                name:'satyam mishra',
                email:'sm@test.com'
            }
        }
    }
}
</script>

<style scoped>
h1 {
    color: yellow;
}
</style>
