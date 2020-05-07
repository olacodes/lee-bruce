<template>
  <div id="app">
    <PriceListing />
  </div>
</template>

<script>
import PriceListing from './components/PriceListing'
export default {
  name: 'App',
  components: {
    PriceListing
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
