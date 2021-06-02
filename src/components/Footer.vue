<script setup lang="ts">
import { isDark, toggleDark } from '~/logic'

</script>

<template>
  <nav class="text-xl mt-6">
    <a class="icon-btn mx-2" title="mode" @click="toggleDark">
      <carbon-moon v-if="isDark" />
      <carbon-sun v-else />
    </a>
  </nav>
</template>
