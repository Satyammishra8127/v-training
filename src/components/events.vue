<template>
    <div>
        <h1 v-on:mousemove="getConsole()">
           Events
        </h1>
        <button v-on:dblclick="getData('welcome to vue.js training')">click me</button>
    </div>
    </template>
    
    <script>
    export default {
        name: 'eventsPage',
        methods:{
            getData(Data){
                alert(Data)
            },
            getConsole(){
                console.warn('welcome to friends')
            }

        }
       
    }
    </script>
    
    <style scoped>
    h1 {
        color:black;
    }
    </style>
    