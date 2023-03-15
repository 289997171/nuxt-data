<template>
  <div>
    test1 - {{data}}
  </div>
</template>

<script setup>
definePageMeta({
  keepalive: true
})
const {data} = useFetch('/api/test1')
</script>

<style scoped>

</style>
