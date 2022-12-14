<template>
  <div id="app">
    <header>
      <AppBar></AppBar>
    </header>
    
    <main>
      <MyHero></MyHero>
      <MyAbout></MyAbout>
    </main>
  </div>
</template>

<script>
import AppBar from "./components/AppBar.vue"
import MyHero from "./components/MyHero.vue"
import MyAbout from "./components/MyAbout.vue"
export default {
  name:"App",
  components:{AppBar,MyHero,MyAbout},
  data(){
    return{

    }
  }
};
</script>

<style>

</style>
