<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Uygulamaya Hosgeldiniz"/>
  <bilesen1 class="ortala" @click="CartaBas" />

  <h2>Adamim ya nasilsin</h2>
</template>



<script>
import HelloWorld from './components/HelloWorld.vue' ;
import bilesen1 from './components/bilesen1.vue'

export default {
  name: 'App',
  components: { HelloWorld, bilesen1 },
  methods: {
    CartaBas()  {
      alert("Karta Bastin!");

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
  color: #20b81b;
  margin-top: 60px;
  background-color: black;
}
</style>
