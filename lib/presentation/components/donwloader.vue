<script setup lang="ts">
  const { href } = defineProps<{ href: string }>();
</script>

<template>
  <a class="v-downloader" :href="href" download="cv">
    <slot name="icon" />
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M19 9h-4V3H9v6H5l7 7l7-7zM5 18v2h14v-2H5z"/></svg>
  </a>
</template>
