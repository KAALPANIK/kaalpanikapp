<template>
  <div>
    <home></home>
  </div>
</template>

<script>
import Home from './components/home'
export default {
  name: 'app',
  components: {
    Home
  }

}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
}
</style>
