<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <h1 class="text-4xl font-bold underline"><icon-mdi-account />{{ msg }}</h1>
</template>
<style scoped></style>
