<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>
<template>
    <div class="wrapper"></div>
    <RouterView />
</template>
<style scoped>
.wrapper {
    width: 100%;
    height: 50px;
    background-color: red;
    position: fixed;
    top: 0;
    left: 0
}
</style>