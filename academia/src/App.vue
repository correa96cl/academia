<template>
  <div id="app">
    <login msg="Oi"/>
    <cssLogin/>
  </div>
</template>

<script>
import Login from './components/Login.vue'
import CssLogin from './assets/css/login.css'


export default {
  name: 'App',
  components: {
    Login, CssLogin
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
