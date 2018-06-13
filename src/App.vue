<template>
  <div id="app">
    <img src="dist/assets/logo.png">
    <h1>{{ msg }}</h1>
    <p>Powered by <a href="https://github.com/vuejs/vue" target="_blank">Vuejs</a></p>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'vue-trello'
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

a {
  color: #42b983;
}
</style>
