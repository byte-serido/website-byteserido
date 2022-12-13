<template>
  <div id="app">
    <header>
      <AppBar></AppBar>
    </header>
    
    <main>
      <MyHero></MyHero>
    </main>
  </div>
</template>

<script>
import AppBar from "./components/AppBar.vue"
import MyHero from "./components/MyHero.vue"
export default {
  name:"App",
  components:{AppBar,MyHero},
  data(){
    return{

    }
  }
};
</script>

<style>

</style>
