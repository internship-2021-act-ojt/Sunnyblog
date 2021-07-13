<template>
  <div id="app">
    <NavBar/>
    <MainContent/>
  </div>
</template>

<script>

import NavBar from "./components/NavBar";
import MainContent from "./components/MainContent";

export default {
  name: 'App',
  components: {
    MainContent,
    NavBar

  }

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  color: #2c3e50;
  display : flex;
  flex-direction: row;
  height: 100vh;
  width : 100vh;
  align-items : center;
}


</style>
