<template>
  <div id="card-container">
      <div class="my_flex-class ">
          <Card class="p-2" v-for="(album, index) in ListaAlbum" :key="index" :source="album.poster" :title="album.title"
                                                    :author="album.author" :year="album.year" />
      </div>
  </div>
</template>

<script>
import axios from 'axios'
import Card from './Card.vue'


export default {
    name:'CardContainer',
    components:{
        Card
    },
    data:function(){
        return {
            ListaAlbum : []
        }
    },

    mounted(){
        axios.get('https://flynn.boolean.careers/exercises/api/array/music')
        .then((risposta) => {
            this.ListaAlbum = risposta.data.response.slice()

        })
    }

}
</script>

<style lang="scss">
#card-container{
    width:60%;
    margin:0 auto;
    padding-top:50px;

    .my_flex-class{
        display: flex;
        flex-wrap: wrap;
    }
}

</style>