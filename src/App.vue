<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import Menu from './components/general/menu.vue'
</script>

<template>
  <Menu />
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
  <RouterView />
</template>

<style scoped>

</style>
