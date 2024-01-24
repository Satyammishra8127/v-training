<template>
<div>
    <h1>methods@Params</h1>
    <h1>
        Name :{{ getName('satyam mishra')}}
    </h1>
    <h1>
        email:{{ email }}
    </h1>
    <h1>
        all data:{{ getdata().email }}
    </h1>
</div>
</template>

<script>
export default {
    name: 'methodsparamsPage',
    data() {
        return {
            email: 'sm@6394243434@gmail.com',

        }
    },
    methods: {
        getName(name) {
            return name;
        },
        getdata(){
            return{
                name:'satyam mishra',
                email:this.email
            }
        }

    }
}
</script>

<style scoped>
h1 {
    color: orange;
}
</style>
