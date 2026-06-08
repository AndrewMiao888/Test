<script setup lang="ts">
const { count, increment } = useCounter()
const { data } = await useFetch('/api/hello')
</script>

<template>
  <div>
    <h2>Home Page</h2>

    <p>API says: {{ data }}</p>

    <p>Counter: {{ count }}</p>
    <button @click="increment">Increase</button>

    <HelloWorld msg="Nuxt 4 is working!" />
  </div>
</template>