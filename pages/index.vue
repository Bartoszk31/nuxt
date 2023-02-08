<script setup>
import { useCountStore } from "~~/stores/useCountStore";

const countStore = useCountStore();
console.log(countStore);
</script>

<template>
  <div>Home {{ countStore.count }}</div>
  <div><button @click="countStore.increment">+</button></div>
</template>
