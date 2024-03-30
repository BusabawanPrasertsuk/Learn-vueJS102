<script setup>

// การส่งค่าผ่าน component 
defineProps({
  msg: String,
})

</script>

<template>
  <h1>Hello this is About{{ msg }}</h1>
</template>

<style scoped>

</style>
