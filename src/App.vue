<template>
  <div id="app">
    <TitlePage></TitlePage>
  </div>
</template>

<script>
import TitlePage from './components/TitlePage.vue'

export default {
  name: 'App',
  components: {
    TitlePage
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
