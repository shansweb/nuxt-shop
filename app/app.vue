<script setup lang="ts">
import type { LayoutKey } from '#build/types/nitro-layouts';
import '~/assets/styles/main.css';

const name = ref<LayoutKey>('auth');
</script>

<template>
  <NuxtLayout :name="name">
    <NuxtPage />
  </NuxtLayout>
</template>