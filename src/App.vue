<template>
  <img alt="Emblema do São Paulo F.C." src="./assets/spfc.png">
  <HelloWorldNovo msg= "Bem vindo ao site tricolor."/>
  <TriLibertadores msg=" Oi"/>
  <HelloWorld msg=" "/>
  <RoDape msg=" "/>
  
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HelloWorldNovo from './components/HelloWorldNovo.vue'
import RoDape from './components/RoDape.vue'
import TriLibertadores from './components/TriLibertadores.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,HelloWorldNovo,TriLibertadores,
    RoDape
  }
}
</script>

<style>
#app {
  background-image: linear-gradient(to bottom, #fa0000, #ece4e4);
  font-family: Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
  margin-top: 20px;
  background-color: white;
  border-radius: 10px;
  box-shadow: 25px 25px 15px #0c160480;
  width: 1300px;
  padding: 50px;
  
}
img {
  height: 480px;
  position: relative;
  margin: 1px;
}
</style>
