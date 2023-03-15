<template>
  <div>
    <header>
      <NuxtLink to="/">index</NuxtLink>
      <NuxtLink to="/test1" style="margin-left: 20px">test1</NuxtLink>
      <NuxtLink to="/test2" style="margin-left: 20px">test2</NuxtLink>
    </header>
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: "default"
}
</script>

<style scoped>

</style>
