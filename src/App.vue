<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" width="25%">
    <HelloWorld msg="Hello My First Vue application!"/>
    <TestComp/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import TestComp from "./components/TestComp"
export default {
  name: "App",
  components: {
    HelloWorld,
    TestComp
  }
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
