<template>
  <div id="app">
    <Users />
    <Footer />
  </div>
</template>

<script>
import Users from './components/Users.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    Users,
    Footer
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  margin-top: 60px;
}
</style>