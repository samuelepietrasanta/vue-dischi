<template>
  <div id="app">
    <h1 class="text-success">ciao</h1>
    <MainApp />
  </div>
</template>

<script>
/* import axios from 'axios' */

import MainApp from './components/MainApp.vue'

export default {
  name: 'App',

  components: {
    MainApp
  },
  /* mounted(){
    axios.get('https://flynn.boolean.careers/exercises/api/array/music')
    .then(function(response){

    })

  } */
}
</script>

<style lang="scss">

@import '~bootstrap/scss/bootstrap';
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
