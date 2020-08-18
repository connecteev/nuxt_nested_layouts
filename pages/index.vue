<template>
  <div>
    <div class="myLink"><nuxt-link to="test0">/test0 (uses layout 0)</nuxt-link></div>
    <div class="myLink"><nuxt-link to="test1">/test1 (uses layout 1)</nuxt-link></div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
.myLink {
  @apply tw-text-sm tw-font-bold tw-text-blue-600;
}
</style>
