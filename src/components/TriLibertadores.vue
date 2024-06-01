<template>
   <div>
    <h2>Conheça o Tri Mundial</h2>
    <ul>
      <li><a href="https://pt.wikipedia.org/wiki/Copa_Libertadores_da_Am%C3%A9rica_de_1992" target="_blank" rel="noopener">1992</a></li>
      <li><a href="https://pt.wikipedia.org/wiki/Copa_Libertadores_da_Am%C3%A9rica_de_1993" target="_blank" rel="noopener">1993</a></li>
      <li><a href="https://pt.wikipedia.org/wiki/Copa_Libertadores_da_Am%C3%A9rica_de_2005" target="_blank" rel="noopener">2005</a></li>
    </ul>
        
  </div>
  <div>
    <h2>Atual Campeão da Copa do Brasil</h2>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=NkzZm8lRjuk" target="_blank" rel="noopener">São Paulo 2 X 1 Flamengo</a></li>
     </ul>  
    </div>
      <h1>Questionário</h1>
      <br>
    <form>
      <div>
      <label>Você torce para qual time?</label>
      <label>
          <input type="radio" name="time" value="SãoPaulo" checked>São Paulo
      </label>
        <input type="radio" name="time" value="OuTro">Outro
      </div>
    </form>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin: 40px 0 0;
  text-align: left;
}
p {
  text-align: left;
}
form {
  text-align: left;
}
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

</style>
