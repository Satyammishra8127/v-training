<template>
<div>
<h1 :class="click"> class binding</h1>
<button v-on:click="colorfull=!colorfull">click</button>
</div>
</template>
    
<script>
export default {
    name: 'ClassbindingPage',
    data(){
        return{
            colorfull:true
        }
    },
    computed:{
        click(){
            return{
                green:this.colorfull,
                err:true
            }
        }
    }

}
</script>

<style scoped>
.green {
 background:green;
 width: 200px;
 margin-left: 600px;
 padding:10px;

}
.err{
    color:red;
}
</style>
