<template>
  <div class="d-flex justify-content-center align-items-center vh-100">
    <div class=" h-100">
      <img src="https://img.icons8.com/officexs/620/000000/pokedex.png"/>

      <PokedexTopComp class="poke-sprite position-absolute"/>

      <PokedexBotComp class="poske-info position-absolute"/>

      
    </div>
  </div>
</template>

<script>
import PokedexTopComp from './components/PokedexTopComp.vue';
import PokedexBotComp from './components/PokedexBotComp.vue';

export default {
  name: 'App',
  components: {
    PokedexTopComp,
    PokedexBotComp
  }
}
</script>

<style lang="scss" scoped>
@import '~bootstrap/scss/bootstrap.scss';

div{
  position: relative;
  img{
    height: 1000px;
  }
}
.poke-sprite{
  top: 125px;
  left: 313px;
}
.poke-info{
  top: 562px;
  left: 375px;
}
</style>
