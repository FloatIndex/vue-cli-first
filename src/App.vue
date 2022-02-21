<template>
  <div id="app">
    <TitleComponent></TitleComponent>
    <JumboComponent></JumboComponent>
  </div>
</template>

<script>
import TitleComponent from './components/TitleComponent.vue'
import JumboComponent from './components/JumboComponent.vue'

export default {
  name: 'App',
  components: {
    TitleComponent,
    JumboComponent
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #1D1727;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
