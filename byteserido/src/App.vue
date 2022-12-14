<template>
  <header>
    <AppBar></AppBar>
  </header>
  
  <main>
    <MyHero></MyHero>
    <MyAbout></MyAbout>
  </main>
</template>

<script>
import AppBar from "./components/AppBar.vue"
import MyHero from "./components/MyHero.vue"
import MyAbout from "./components/MyAbout.vue"
export default {
  components:{AppBar,MyHero,MyAbout},
  data(){
    return{

    }
  }
};
</script>

<style>
  #app{
    display: flex;
    flex-direction: column;
    flex: 1;
    min-height: 100%;
  }
</style>
