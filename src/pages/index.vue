<template>
  <h1>Index page</h1>
  <NuxtLink to="/page-sample">Home page</NuxtLink>
</template>

<script setup lang="ts">

definePageMeta({
  title: "My home page",
  // middleware: ["navigation-guards"],
})


// // router.push()は使えないの？
// function navigate(){
//   return navigateTo({
//     path: "/search",
//     query: {
//       name: name.value,
//       type: type.value
//     }
//   })
// }

</script>

<style lang="scss" scoped>

</style>
