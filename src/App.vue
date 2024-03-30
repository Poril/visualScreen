<template>
  <div id="app">
    <RouterView />
  </div>
</template>


<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>


<style scoped>
#app {
  height: 100%;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
