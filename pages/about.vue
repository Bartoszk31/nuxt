<script setup>
const { pending, data } = useLazyFetch("/api/test");
</script>

<template>
  <div v-if="pending">Loading</div>
  <div v-else>asaasdasdsas{{ data }}</div>
</template>
