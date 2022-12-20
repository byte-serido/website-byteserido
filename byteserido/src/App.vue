<template>
  <header>
    <NavBar></NavBar>
  </header>
  
  <main>
    <MyHero></MyHero>
    <MyAbout></MyAbout>
    <MySolutionsAndServices></MySolutionsAndServices>
    <MyContact></MyContact>
  </main>
</template>

<script>
import NavBar from "./components/NavBar.vue"
import MyHero from "./components/MyHero.vue"
import MyAbout from "./components/MyAbout.vue"
import MySolutionsAndServices from "./components/MySolutionsAndServices.vue";
import MyContact from "./components/MyContact.vue"
export default {
  components:{NavBar,MyHero,MyAbout,MySolutionsAndServices, MyContact},
  data(){
    return{
      data(){
        return{}
      }
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
