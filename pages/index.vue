<script setup lang="ts">
const route = useRoute();

definePageMeta({
    layout: 'default',
})
</script>

<template>
  <div>
    <features />
    <featured-artists />
    <pricing />
    <reminder />
    <faq />
  </div>
</template>
