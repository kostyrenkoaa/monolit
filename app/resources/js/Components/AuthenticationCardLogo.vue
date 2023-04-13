<script setup>
import { Link } from '@inertiajs/vue3';
</script>

<template>
    <Link :href="'/'">
        <img src="/imgs/logo.png" alt="">
    </Link>
</template>

<style scoped>
img {
    max-width: 100%;
    height: 109px;
    border-radius: 61px;
}
</style>
