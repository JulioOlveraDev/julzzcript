<script setup lang="ts">
async function fetchData() {
  const response = await fetch('/api')
  const data = await response.text()
  console.log(data)
}
</script>

<template>
  <button @click="fetchData">Click Me</button>
</template>

<style scoped></style>
