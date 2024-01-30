<template>
<div>
    <h1>
        REF
    </h1>
    <input type="text" ref="input"/>
    <button v-on:click="getData">click me</button>

</div>
</template>
   
<script>
export default {
    name: 'ReF1Page',
    methods:{
        getData(){
             this.$refs.input.focus();
             let val=this.$refs.input.value;
             console.warn(val);
             this.$refs.input.style.color="red"
        }
    }

}
</script>
    
<style scoped>
h1 {
    color: purple;
}
</style>
