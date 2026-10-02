<script setup lang="ts">
const stack = 'Vite + Vue 3 + TypeScript + plain CSS'
</script>

<template>
  <main class="screen">
    <h1>starter — it runs ✅</h1>
    <p>{{ stack }}</p>
  </main>
</template>

<style scoped>
.screen {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
  background: #0f172a;
  color: #e2e8f0;
  font-family: system-ui, sans-serif;
}
.screen p { color: #94a3b8; }
</style>
