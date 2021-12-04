<template>
  
   <section>

  <HelloWorld msg="Welcome to Docker served Vue3 App !"/>
   </section>

   <img alt="C64" src="./assets/c64_small.png">

 <section>

  <bilesen1 class="ortala" @click="CartaBas" />

   </section>

  
 <section>

  <h2>This is just a footer section</h2>

   </section>

</template>



<script>
import HelloWorld from './components/HelloWorld.vue' ;
import bilesen1 from './components/bilesen1.vue'

export default {
  name: 'App',
  components: { HelloWorld, bilesen1 },
  methods: {
    CartaBas()  {
      alert("You have just Clicked !");

    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #111311;
  margin-top: 60px;
  background-color: rgb(191, 196, 193);   
  }

  section{
  background-color: rgb(80, 9, 9);
  border: outset rgb(126, 255, 51);
  color: white;
  padding: 20px 2px;
  margin: 50px 200px;
  align-content: center;
  /* background-image: url(./assets/c64_small.png); 
  background-size: 50%; 
  background-repeat:no-repeat;
  background-position: center; */
  
  }

  h3 {
  font-family: Helvetica, "Trebuchet MS", Verdana, sans-serif;
  font-weight: bold;
  font-size: 150%;
  font:comic;
  text-shadow: 2px 2px 2px rgb(38, 105, 7);              
  }

  h1 {
  font-size: 2rem;
  text-transform: capitalize;
  text-shadow: 1px 1px 1px rgb(58, 51, 51),
               2px 2px 1px rgb(197, 186, 186);
  text-align: center;
  letter-spacing: 2px;
  }

  img {
  border-radius: 60%;
  }

</style>
