<script setup>

const route = useRoute()
// console.log(route)
</script>

<template>
  <div>we are inside the blog</div>
  <div>post id is: {{ route.params.id }}</div>
</template>

<style scoped>

</style>