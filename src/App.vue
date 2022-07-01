<template>
  <div id="app">
    <!-- header component -->
    <TheHeader></TheHeader>

    <!-- main component -->
    <TheMain></TheMain>

    <!-- footer component -->
    <TheFooter></TheFooter>

  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue';
import TheMain from './components/TheMain.vue';
import TheFooter from './components/TheFooter.vue';


export default {
  name: 'App',
  components: {
    TheHeader,
    TheMain,
    TheFooter
}
}
</script>

<style lang="scss">
@import "./assets/scss/main.scss";

#app {
  background-color: #242340;
  color: white;
}
</style>
