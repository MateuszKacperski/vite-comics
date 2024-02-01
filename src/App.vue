<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  name: 'Dc-comics',
  date: () => ({
    elements
  }),
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}

</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
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
  min-height: 100vh;
  background-color: black;
}

/* Utils */
.container {
  margin: 0 auto;
  max-width: 1200px;
  display: flex;
  align-items: center;
  justify-content: space-between;

}
</style>