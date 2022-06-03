<template>
  <img alt="Main banner" src="https://image.shutterstock.com/image-vector/set-gold-silver-crypto-currencies-260nw-775898248.jpg"/>
  <HelloWorld msg="Welcome to crypto sinhala"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
body{
  background-color: black;
  height: 100%;
}
img{

  height:auto;  
  width: 100%;
}

</style>
