<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" width="25%" />
    <todolist></todolist>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import Todolist from "./components/Todolist";

export default {
  name: "App",
  components: {
    HelloWorld,
    Todolist,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
