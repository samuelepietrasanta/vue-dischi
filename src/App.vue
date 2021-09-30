<template>
  <div >
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
@import './style/general.scss';

@import '~bootstrap/scss/bootstrap';

</style>
