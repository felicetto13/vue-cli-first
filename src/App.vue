<template>
  <div id="app">
    <JumbotronComponent></JumbotronComponent>
    <TitlePage></TitlePage>
  </div>
</template>

<script>
import TitlePage from './components/TitlePage.vue'
import JumbotronComponent from './components/JumbotronComponent.vue'

export default {
  name: 'App',
  components: {
    TitlePage, JumbotronComponent
  }
}
</script>

<style lang="scss">
body{
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
