<template>
    <h1>Hello {{name}}</h1>
    <p>In this series, we will use the following frameworks:</p>
    <ul>
        <li v-for="framework of frameworks" v-text="framework"></li>
    </ul>
</template>

<script>
export default {
    name: "Welcome.vue",
    props: {
        name: String,
        frameworks: Array
    }
}
</script>

<style scoped>

</style>
