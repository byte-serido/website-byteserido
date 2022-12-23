<template>
  <header>
    <NavBar></NavBar>
  </header>
  
  <main>
    <MyHero id="hero"></MyHero>
    <MyAbout id="about"></MyAbout>
    <MySolutionsAndServices id="sands"></MySolutionsAndServices>
    <MyContact id="contact"></MyContact>
  </main>
  <footer>
    <MyFooter></MyFooter>
  </footer>
</template>

<script>
import NavBar from "./components/NavBar.vue"
import MyHero from "./components/MyHero.vue"
import MyAbout from "./components/MyAbout.vue"
import MySolutionsAndServices from "./components/MySolutionsAndServices.vue";
import MyContact from "./components/MyContact.vue"
import MyFooter from "./components/MyFooter.vue";
export default {
  components:{NavBar,MyHero,MyAbout,MySolutionsAndServices,MyContact,MyFooter},
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
