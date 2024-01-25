<template>
  <div>
    <app-nav></app-nav>
  </div>
</template>

<script>
import navbar from './components/navbar.vue'
export default {
  components: {
    'app-nav': navbar
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
  margin-top: 60px;
}
</style>
