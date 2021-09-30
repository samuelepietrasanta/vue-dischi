<template>
  <div>
    <Header />
    <CardContainer />
  </div>
</template>

<script>
import Header from './Header.vue'
import CardContainer from './CardContainer.vue'


export default {
  name: 'MainApp',
  props: { },
  components: {
    Header,
    CardContainer
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss" >

</style>
