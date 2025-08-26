<script setup lang="ts">

</script>

<template>
    <h1 class="text-3xl font-bold underline">
        Hello world
    </h1>
    <router-link to="index">Index</router-link>
    <router-link to="page">Page</router-link>
    <router-view></router-view>
</template>
<script>
    export default {
        name: "App"
    }
</script>

<style scoped>

</style>
