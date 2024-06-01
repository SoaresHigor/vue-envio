<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Agradecimentos</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit labore voluptas natus beatae blanditiis earum consequatur laudantium, laborum veritatis omnis, exercitationem sed iste at qui quae, iure quod id dignissimos. Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea quos ex, tenetur porro dicta aliquam quam laudantium veniam error magni sed voluptatem dignissimos hic aut, iste nihil corporis deleniti tempore?</p>
    
    <h2>2024</h2>
    
  </div>
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
  text-align: center
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
p {
  text-align: justify;
}
</style>
