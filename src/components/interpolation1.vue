<template>
<div>
    <h1>
        Email :{{ Email }}
    </h1>
    <h1>
        Email :{{ mobile}}
    </h1>
    <h1>
        Email :{{ Name}}
    </h1>
    <h1>
        surname :{{ getName('mishra')}}
    </h1>
</div>
</template>

<script>
export default {
    name: 'interpolaton1Page',
    data() {
        return {
            Email: 'satyamprogrammer.cse@gmail.com',
            mobile: '8127777102',
            Name: 'Satyam Mishra',
            getName:function(a){
                return a;
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
