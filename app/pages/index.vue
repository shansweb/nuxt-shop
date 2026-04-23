<script setup lang="ts">
import InputField from '~/components/inputField.vue';
</script>

<template>
    <div>
        Index
        <nuxt-link to="/About">About</nuxt-link>
        <InputField variant="black" placeholder="Ваш email для акций и предложений"/>
    </div>
</template>