<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <Kader />
</template>

<script>
//import HelloWorldVue from "./components/HelloWorld.vue";
import Kader from "./components/Kader";

export default {
  name: "App",
  components: {
    //HelloWorld: HelloWorldVue,
    Kader: Kader,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
