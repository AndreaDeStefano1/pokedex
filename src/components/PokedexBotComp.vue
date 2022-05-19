<template>
  <div class="pokedex-bot d-flex flex-column-reverse p-2">
   <div class="search">
     <input v-model="pokemonName" type="text">
     <button class="btn btn-danger ms-1">Cerca</button>
   </div>
   <div class="moves">
     Mosse
   </div>
    
  </div>
</template>

<script>
export default {
  name: 'PokedexBotComp',
  data(){
    return{
      pokemonName: '',
    }
  }
}
</script>

<style lang="scss" scoped>
@import '~bootstrap/scss/bootstrap.scss';
div{

  .pokedex-bot{
    background-color: rgb(45, 168, 217);
    width: 313px;
    height: 314px;
  }

}
 
</style>