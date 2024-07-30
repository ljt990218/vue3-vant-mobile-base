<script setup lang="ts">
defineProps({
  paddingT: {
    type: String,
    default: '0',
  },
  paddingX: {
    type: String,
    default: '16',
  },
})
</script>

<template>
  <main :style="`padding-top: ${paddingT}px; padding-left: ${paddingX}px; padding-right: ${paddingX}px`">
    <NavBar />
    <slot />
  </main>
</template>
