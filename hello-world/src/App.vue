<template>
  <div id="app">
    <img alt="Vue logo" src="https://cdn.galleries.smcloud.net/t/galleries/gf-UNto-nrdS-94kd_krzysztof-krawczyk-664x442-nocrop.JPG">
   
    <HelloWorld msg="Krawczyk po 10 piwach, wchodzi lepiej"/>
    <Test msg="krawczyk komponent"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Test from './components/Test.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Test
  }
}
</script>

<style type="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
