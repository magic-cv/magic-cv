<script setup lang="ts">
import { useHead } from '@vueuse/head'

// https://github.com/vueuse/head
// you can use this to manipulate the document head in any components,
// they will be rendered correctly in the html results with vite-ssg
useHead({
  title: 'magic cv',
  meta: [
    { name: 'description', content: '一个充满魔法的简历生成网站' },
    { name: 'a', content: 'sdfs' },
  ],
})
</script>

<template>
  <router-view />
</template>
