<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <AwesomeTitle/>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <AwesomeJumbotron/>

  </div>
</template>

<script>
/*import HelloWorld from './components/HelloWorld.vue'*/
import AwesomeTitle from './components/AwesomeTitle.vue'
import AwesomeJumbotron from './components/AwesomeJumbotron.vue'

export default {
  name: 'App',
  components: {
    AwesomeTitle,
    AwesomeJumbotron
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
