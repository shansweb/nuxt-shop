<script setup lang="ts">
import InputField from '~/components/inputField.vue';

function openAbout() {
    // navigateTo('/about');
    setPageLayout('auth');
}
</script>

<template>
    <div>
        Index
        <Icon name="icons:twitter" />
        <nuxt-link to="/About">About</nuxt-link>
        <button @click="openAbout">sad</button>
        <InputField variant="black" placeholder="Ваш email для акций и предложений"/>
    </div>
</template>