<template>
    <div>
        <h1>
           Modifiers
        </h1>
        <input type="text" v-model.trim.lazy.number="data"/>
        <h2>Data is:
            {{ data }}
        </h2>

    </div>
    </template>
       
    <script>
    export default {
        name: 'modifiersPage',
        data(){
            return{
                data:''
            }
        }
        
    }
    </script>
       
    <style scoped>
    h1 {
        color: chocolate
    }
    </style>
    