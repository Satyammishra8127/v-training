<template>
<div>
    <h1>
        Get input field value
    </h1>
    <input type="text" placeholder="email" v-model="email"/>
    <br />
    <br />
    <input type="text" placeholder="password" v-model="password"/>
    <br />
    <br />
    <button v-on:click="getData()">Get value</button>

</div>
</template>

    
<script>
export default {
    name: 'getinputfieldvaluePage',
    data(){
        return{
             email:null,
             password:null,
        }
    },

     methods: {
        getData(){
            console.warn('values:',this.email,this.password)
        }
     },
}
</script>

    
<style scoped>
h1 {
    color: brown;
}
</style>
