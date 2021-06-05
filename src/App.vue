<template>
  <div id="app">
    <Home/>
  </div>
</template>

<script>
import Home from './page/home.vue'
export default {
  name: 'App',
  components: {
    Home,
  }
}
</script>

<style>
@import url('./style/reset.css');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap');
#app {
  font-family: 'Roboto', sans-serif;
  padding: 0px 20px;
}
</style>
