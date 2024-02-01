<script>
import AppHeader from './components/AppHeader.vue'
export default {
  name: 'Dc-comics',
  components: {
    AppHeader
  }
}

</script>

<template>
  <AppHeader />
</template>

<style>
/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Generics */
img {
  max-width: 100%;
  height: auto;
}

body {
  max-height: 100vh;
  background-color: black;
}
</style>