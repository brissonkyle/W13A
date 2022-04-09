<template>
  <div id="app">
    <HeaderComp/>
    <BodyComp/>
    <FooterComp/>
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import BodyComp from './components/BodyComp.vue'
import FooterComp from './components/FooterComp.vue'
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    HeaderComp,
    BodyComp,
    FooterComp
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
*{
  background-color: rgb(175, 6, 113);
}
</style>
