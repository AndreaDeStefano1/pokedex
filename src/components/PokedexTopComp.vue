<template>
  <div class="ds-container d-flex">
    <div class="ds-side flex-shrink-0">
      <div>
         <h5>Numero nel Pokedox:</h5>
        <h2># 1</h2>
      </div>
      
    </div>
    <div class="ds-center d-flex flex-grow-0 flex-shrink-0 flex-wrap">
      <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-v/black-white/animated/1.gif" alt="">
      <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-v/black-white/animated/back/1.gif" alt="">
      <h3>Name: Bulbasaur</h3>
      <h3>Type: grass</h3>





    </div>
  </div>
</template>

<script>
export default {
  name: 'PokedexComp'
}
</script>

<style lang="scss" scoped>
@import '~bootstrap/scss/bootstrap.scss';
.ds-container{
  width: 375px;
  height: 250px;
  .ds-side{
    height: 250px;
    width: 100px;
    background-color: purple;
  }
  .ds-center{
    background-color: rgb(45, 168, 217);
    width: 275px;
    img{
      width: calc(100% / 2);
      height: auto;
    }
  }

}
 
</style>
<!-- 
"generation-v": {
  "black-white": {
    "animated": {
      "back_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-v/black-white/animated/back/1.gif",
      "back_female": null,
      "back_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-v/black-white/animated/back/shiny/1.gif",
      "back_shiny_female": null,
      "front_default": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-v/black-white/animated/1.gif",
      "front_female": null,
      "front_shiny": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/versions/generation-v/black-white/animated/shiny/1.gif",
      "front_shiny_female": null
    }
  }
},
 -->

<!-- "name": "bulbasaur", -->