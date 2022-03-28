<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">

    <Counter/>
    
    <Botones/>    

    <Cuadrado/>

  </div>
</template>

<script>

import Counter from "../components/contador.vue";
import Cuadrado from "../components/cuadrado.vue";
import Botones from "../components/botones.vue";

export default {
  name: 'HomeView',
  components:{
    Counter,
    Cuadrado,
    Botones,
  }
}
</script>

<style>

  div{
    margin-bottom: 10px;
  }

  .counter{
    font-size: 80px;
  }

  .botones button{
    font-size: 40px;
    width: 100px;
    margin: 0 10px;
  }

  .cuadrado{
    font-size: 25px;
  }
</style>