<template>
  <div id="app">

    <mon-style/>
  </div>
</template>

<script>
import MonStyle from './components/MonStyle'

export default {
  name: 'App',
  components: {
    MonStyle
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
