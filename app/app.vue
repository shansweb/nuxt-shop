<script setup lang="ts">
import '~/assets/styles/main.css';
const runtime = useRuntimeConfig();
// const config = useAppConfig();
const hello = ref(runtime.public.apiurl);
</script>

<template>
  <div>
    {{ hello }}
    <NuxtPage />
  </div>
</template>