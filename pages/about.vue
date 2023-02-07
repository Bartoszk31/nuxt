<script setup>
const { pending, data } = useLazyFetch("/api/test");
</script>

<template>
  <div v-if="pending">Loading</div>
  <div v-else>asasas{{ data }}</div>
</template>
