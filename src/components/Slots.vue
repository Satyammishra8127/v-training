<template>
<div>
    <slot></slot>
    <header>
        <slot name="header"></slot>
    </header>
    <main>
        <slot name="main"></slot>
    </main>
    <footer>
        <slot name="footer"></slot>
    </footer>
</div>
</template>

<script>
export default {
    name: 'SlotsPage',

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
