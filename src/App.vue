<template>
  <div id="app">
    <titlecom/>
  </div>
</template>

<script>
import TitleCom from './components/TitleCom.vue'

export default {
  name: 'App',
  components: {
    TitleCom
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
