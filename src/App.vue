<template>
  <div class="">
    <header-component></header-component>
      <content-component></content-component>
    <footer-component></footer-component>
  </div>
  
</template>

<script>

import HeaderComponent from './components/shared/HeaderComponent.vue'
import FooterComponent from './components/shared/FooterComponent.vue'
import ContentComponent from './components/shared/ContentComponent'


export default {
  name: 'App',
  components: {
    HeaderComponent,
    FooterComponent,
    ContentComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
   min-height: 450px;
    margin: 0px;
    padding: 0px;
    text-align: center;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    
}
</style>
