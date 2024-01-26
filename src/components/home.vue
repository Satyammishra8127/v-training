<template>
<div>
    <h1> Reuse components</h1>
    <ul>
        <li v-for="item in user" :key="item">
            <user :data="item" :getdata="getdata"/>
        </li>
    </ul>
</div>
</template>

<script>
import user from './user.vue'
export default {
    name: 'homePage',
    components: {
        user
    },
    methods: {
        getdata(name){
            alert(name)
        }
    },
    data() {
        return {
            user: [{
                    name: 'Pariwesh Gupta',
                    email: 'pg@test.com'
                },
                {
                    name: 'Satyam mishra',
                    email: 'sm@test.com'
                }
            ]
        }
    }

}
</script>

<style scoped>

</style>
