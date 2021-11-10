<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Title :titolo="title" />
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" :desk="title"/> -->
    <!-- <HelloWorld msg="Secondo componente" :desk="title"/> -->
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Title from './components/Title.vue'

export default {
  name: 'App',
  data(){
    return {
      title: "La mia prima app con Vue CLI!"
    }
  },
  components: {
    //HelloWorld,
    Title
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
