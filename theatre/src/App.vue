<template>
  <div id="app">
   
   
    <HeaderComponent/>
  
    <MainComponent/>
    <FooterComponent/>
  </div>
</template>

<script>

import HeaderComponent from './components/HeaderComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
import MainComponent from './components/MainComponent.vue'
export default {
  name: 'App',
  components: {
   
    HeaderComponent,
    FooterComponent,
    MainComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
      /* width: fit-content; */
  margin-top: 0px;
}
@media screen and (max-width:1000px) {
   #app {
    width: fit-content;
   }
}
</style>
