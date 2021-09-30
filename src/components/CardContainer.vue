<template>
  <div id="card-container">
      <div>
          <Card />
      </div>
  </div>
</template>

<script>
import Card from './Card.vue'
export default {
    name:'CardContainer',
    components:{
        Card
    }

}
</script>

<style lang="scss">
#card-container{
    width:60%;
    margin:0 auto;
    background-color: white;
}

</style>