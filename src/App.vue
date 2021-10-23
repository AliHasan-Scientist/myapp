<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Hello world" />
    <Nav mes="Hello I am parent" />
    <Directives />
    <Home />
  </div>
</template>
<script>
import HelloWorld from "./components/HelloWorld.vue";
import Nav from "./components/Nav";
import Directives from "./components/Directives.vue";
import Home from "./components/Home.vue";
export default {
  name: "App",
  components: {
    HelloWorld,
    Nav,
    Directives,
    Home,
  },
};
</script>

<style>
</style>
