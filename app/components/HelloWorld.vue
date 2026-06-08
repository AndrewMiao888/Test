<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div style="margin-top: 20px;">
    <h3>{{ msg }}</h3>
  </div>
</template>