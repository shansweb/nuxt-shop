<script setup lang="ts">
function openAbout() {
    navigateTo('/about');
}
</script>

<template>
    <div>
        Index
        <nuxt-link to="/About">About</nuxt-link>
        <button @click="openAbout">sad</button>
    </div>
</template>