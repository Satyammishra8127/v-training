<template>
<div>
    <h1>
        Loop condition
    </h1>
    <ul>
        <li v-for="item in Technology" :key="item">
            {{ item }}

        </li>

    </ul>
    <br>
    <br>
    <ul>
        <li v-for="item in user" :key="item">
            name: {{ item.name }} and Email:{{ item.Email }}

        </li>
    </ul>
    

</div>
</template>

<script>
export default {
    name: 'loop1Page',
    data() {
        return {
            Technology: ['vue', 'react', 'html', 'javascript', 'python', 'django'],
            user: [{
                name: "Satyam mishra",
                Email: "sm@test.com"
            }]
        }
    }

}
</script>

<style scoped>
h1 {
    color: purple;
}
</style>
