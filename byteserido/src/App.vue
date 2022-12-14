<template>
  <header>
    <NavBar></NavBar>
  </header>
  
  <main>
    <MyHero></MyHero>
    <MyAbout></MyAbout>
  </main>
</template>

<script>
import NavBar from "./components/NavBar.vue"
import MyHero from "./components/MyHero.vue"
import MyAbout from "./components/MyAbout.vue"
export default {
  components:{NavBar,MyHero,MyAbout},
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
