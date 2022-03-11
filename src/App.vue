<template>
  <div>{{ vitePort }}</div>
</template>
<script setup lang="ts">
import { ref } from "vue";
const vitePort = ref(import.meta.env.VITE_PORT);
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
