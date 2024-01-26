<template>
    <div v-html="tag">
    </div>
    </template>
    
    <script>
    export default {
        name: 'HtmlbindingPage',
        data(){
            return{
                tag:"<h1>Pariwesh Sir</h1>"
            }
        }
       
    }
    </script>
    
    <style scoped>
    
    </style>
    