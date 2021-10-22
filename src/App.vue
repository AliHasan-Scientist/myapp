<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Hello world" />
    <Nav mes="Hello I am parent" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Nav from "./components/Nav";

export default {
  name: "App",
  components: {
    HelloWorld,
    Nav,
  },
};
</script>

<style>
</style>
