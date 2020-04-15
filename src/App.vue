<template>
  <div id="app">
    <div id="nav-bar"></div>

  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component({
  components: {
  },
})
export default class App extends Vue {}
</script>

<style>
  body{
    padding: 0;
    margin: 0;
  }
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
  #nav-bar{
    position: absolute;
    width: 100%;
    height: 50px;
    background-color: #194c66;
    -webkit-app-region: drag;
    z-index: 9999;
  }
</style>
