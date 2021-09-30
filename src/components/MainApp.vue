<template>
  <div>
    <Header />
    <MainPage />
  </div>
</template>

<script>
import Header from './Header.vue'
import MainPage from './MainPage.vue'


export default {

  name: 'MainApp',

  props:{},
  components: {
    Header,
    MainPage
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss" >


</style>
