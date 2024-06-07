<script setup lang="ts">
definePage({
  name: 'profile',
  meta: {
    level: 1,
  },
})

const { t } = useI18n()
</script>

<template>
  <Container padding-t="0">
    <div mx-auto mb-60 pt-15 text-center text-16 text-dark dark:text-white>
      {{ t('profile.placeholder') }}
    </div>
  </Container>
</template>
