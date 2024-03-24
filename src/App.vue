<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="m-2.5 text-emerald-500">
    <RouterLink to="/">Home</RouterLink> <span class="text-gray-900" >|</span>
    <RouterLink to="/about">About</RouterLink> <span class="text-gray-900" >|</span>
    <RouterLink to="/test1">test1</RouterLink> <span class="text-gray-900" >|</span>
  </div>

  <RouterView />
</template>

<style scoped >
.fs{
  font-size: 20px;

}

</style>
