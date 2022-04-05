<template>
  <div id="app">
    <HelloWorld msg="La mia prima app con Vue CLI!" />
    <HeroSection />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import HeroSection from "./components/HeroSection.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    HeroSection,
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
