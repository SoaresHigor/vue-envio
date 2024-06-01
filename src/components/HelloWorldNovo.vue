<template>
  <div class="hello">
    <h1>{{ msg }}</h1> </div>
  <div>
    <p>
      Assista aos
      <a href="https://www.youtube.com/watch?v=KTSvrjDOyCg" target="_blank" rel="noopener">melhores momentos do último jogo.</a>.
    </p>
    <h2>Conheça o Tri da Libertadores</h2>
    <ul>
      <li><a href="https://pt.wikipedia.org/wiki/Copa_Libertadores_da_Am%C3%A9rica_de_1992" target="_blank" rel="noopener">1992</a></li>
      <li><a href="https://pt.wikipedia.org/wiki/Copa_Libertadores_da_Am%C3%A9rica_de_1993" target="_blank" rel="noopener">1993</a></li>
      <li><a href="https://pt.wikipedia.org/wiki/Copa_Libertadores_da_Am%C3%A9rica_de_2005" target="_blank" rel="noopener">2005</a></li>
    </ul>
        
  </div>
</template>

<script>
export default {
  name: 'HelloWorldNovo',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h2 {
  margin: 40px 0 0;
  text-align: left;
}
ul {
  list-style-type: none;
  padding: 0;
  text-align: left; 
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #000000;
}
main {
    background-color: aliceblue;
    border-radius: 10px;
    box-shadow: 5px 5px 15px #0c160480;
    width: px;
    padding: 10px;
    margin: auto;
}

</style>
