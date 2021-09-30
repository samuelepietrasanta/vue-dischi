<template>
  <div class="carta">
      <img :src="source" alt="Album">
      <h5 class="text-center title">{{title}}</h5>

      <div class="author-year text-center">
          {{author}} <br>
          {{year}}
      </div>
  </div>
</template>

<script>
export default {
    name:'Card',

    props: ['source' , 'title' , 'author' , 'year']

}
</script>

<style lang="scss">

.carta{
    width: 150px;
    background-color: #2E3A46;

    img{
        width:100%
    }

    h5{
        color:white
    }

    .title{
        text-transform: uppercase;
    }

    .author-year{
        font-size:.8rem;
        color:#6D726F;
    }
}

</style>