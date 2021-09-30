<template>
  <div id="main-page">

    <CardContainer />


      
  </div>
</template>

<script>
import CardContainer from './CardContainer.vue'
export default {
  name:"MainPage",
  components:{
    CardContainer
    }

}
</script>

<style lang="scss">

#main-page{
    height: calc(100vh - 70px);
    width:100%;
    background-color: #1E2D3B;
}


</style>
    CardContainer