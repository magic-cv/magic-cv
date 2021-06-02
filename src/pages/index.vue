<!-- <script setup lang="ts">
import { ref } from 'vue'
import { useRouter } from 'vue-router'

const name = ref('')

const router = useRouter()
const go = () => {
  if (name.value)
    router.push(`/hi/${encodeURIComponent(name.value)}`)
}

</script> -->

<template>
  <main>
    <h1>Hello, Magic CV !</h1>
    <button class="start">Get Started</button>
  </main>
</template>

<style>
main {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
h1 {
  color: var(--prism-foreground);
}
</style>

<route lang="yaml">
meta:
  layout: home
</route>
