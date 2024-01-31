<template>
<div>
    <Slots>
        <h1>
            Watchers
        </h1>
    </Slots>
    <Slots>
        <h2>Slots in Vue.js</h2>
    </Slots>
    <h2>
        {{count}}
    </h2>
    <button v-on:click="count=count+1">+</button>
    <button v-on:click="count=count-1">-</button>
    <Slots>
        <template v-slot:header>
            <h1>Pariwesh sir</h1>
        </template>
        <template v-slot:main>
            <h1>Technology</h1>
        </template>
        <template v-slot:footer>
            <h1>Teacher</h1>
        </template>
    </Slots>
</div>
</template>

<script>
import Slots from './Slots.vue'
export default {
    name: 'WatcherPage',
    components: {
        Slots
    },
    data() {
        return {
            count: 0
        }
    },
    watch: {
        count(val, prev) {
            if (val > 5 && val > prev) {
                this.count = 0
            }
        }
    }

}
</script>

<style scoped>
h1 {
    color: chocolate
}

h2 {
    color: black;
}
</style>
