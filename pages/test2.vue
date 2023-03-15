<template>
  <div>
    test2 - {{data}}
  </div>
</template>

<script setup>
definePageMeta({
  keepalive: true
})
const { data/*, pending, error, refresh*/ } = await useAsyncData(
    'test2',
    () => $fetch('/api/test2')
)
</script>

<style scoped>

</style>
