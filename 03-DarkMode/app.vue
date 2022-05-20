<script setup lang="ts">
import {} from '#app'

  const { isDarkMode } = useDarkMode()
</script>

<template>
  <div :style="isDarkMode && { background: 'black' }">
    <Nav />
    <Heading />
    <Cards />
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  font-family: Georgia;
}
</style>
