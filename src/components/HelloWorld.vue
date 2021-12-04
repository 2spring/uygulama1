<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      This is our Vue3  Application running in a Docker Container and 
      serving through a custom build httpd 2.4 (Apache) webserver image..

      <br> <br />
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">We are using the vue3 as cli </a>.
    </p>
    <h4>Download the project repository (test) </h4>
            <button>Download</button>

    <ul>
      <h3> You can reach to me via : </h3> 
      <li><a href="https://www.datasciencebase.com" target="_blank" rel="noopener">Data Science Base</a></li>
      <li><a href="https://www.linkedin.com/in/uygarh/" target="_blank" rel="noopener">linkedin</a></li>
    </ul>
    
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
