<template>
<div>
    <h1>
        Get Checkbox-radio-value
    </h1>
    <h3>Technology</h3>

    <label for="java">java</label>
    <input type="checkbox" value="java" v-model="Technology" id="java" />

    <label for="javascript">javascript</label>
    <input type="checkbox" value="javascript" v-model="Technology" id="javascript" />
    
    <label for="python">python</label>
    <input type="checkbox" value="python" v-model="Technology" id="python" />
    <br/><br/>
    <h3>Profession</h3>
    <label for="student">student</label>
    <input type="radio" value="student"  id="student" v-model="profession" name="profession"/>

    <label for="developer">developer</label>
    <input type="radio" value="developer"  id="developer" v-model="profession" name="profession" />
    <h4>Technology:{{ Technology }} </h4>
    <h4>I am a:{{ profession }} </h4>
</div>
</template>

    
<script>
export default {
    name: 'checkboxradioPage',
    data(){
        return{
            Technology:[],
            profession:null
        }
    }


}
</script>

    
<style scoped>
h1 {
    color: green;
}
</style>
