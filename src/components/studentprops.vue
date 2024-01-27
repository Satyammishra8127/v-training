<template>
    <div>
        <h1>
            Student :{{ name }}
        </h1>
    </div>
    </template>
    
    <script>
    export default {
        name: 'studentpropsPage',
        props:{
            name:String
        }  
    }
    </script>
    
    <style scoped>
    h1{
        color:red;
    }
    </style>
    