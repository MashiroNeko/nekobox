<template>
  <div id="app">
    <nav-bar></nav-bar>
    <img alt="Vue logo" src="./assets/logo.png" />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HelloWorld from "./components/HelloWorld.vue";
import NavBar from "@/components/navBar.vue";

@Component({
  components: {
    NavBar
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
* {
  scrollbar-3dlight-color: #d4d0c8;
  scrollbar-highlight-color: #fff;
  scrollbar-face-color: #e4e4e4;
  scrollbar-arrow-color: #666;
  scrollbar-shadow-color: #808080;
  scrollbar-darkshadow-color: #d7dce0;
  scrollbar-base-color: #d7dce0;
}
</style>
