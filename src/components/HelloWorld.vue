   <template>
    <main>
    <div class="hello">
    <h1>{{ msg }}</h1>
    <img src="" alt="">
    <div class="bloco">

    
    <h2>Loja Oficial</h2>
    <ul>
      <li><a href="https://www.saostore.com.br/?gad_source=1&gclid=CjwKCAjwx-CyBhAqEiwAeOcTdVSsn663n8iw-QvPeR1wlH1-23iFqSgVwuULQmlApgwElmJja9oYtBoCoEQQAvD_BwE" target="_blank" rel="noopener">SaoStore</a></li>
        </ul>
    <h2>Mídias Sociais</h2>
    <ul>
      <li><a href="https://www.instagram.com/saopaulofc/" target="_blank" rel="noopener">Instagram</a></li>
      <li><a href="https://www.youtube.com/spfctv" target="_blank" rel="noopener">YouTube</a></li>
      <li><a href="https://x.com/SaoPauloFC?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor" target="_blank" rel="noopener">Twitter</a></li>
    </ul>
    <h2>Conheça o MorumBis</h2>
    <ul>
      <li><a href="https://passaportefc.com/produto/morumbis-tour/" target="_blank" rel="noopener">MorumBis Tour</a></li>
      </ul> </div>
  </div> </main>
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
div.bloco {
  height: 350px;
  border: 1px solid black;
  border-radius: 20px;
  margin: 10px;
  
}
</style>
