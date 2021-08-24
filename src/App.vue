<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome Olka2, to Your Vue.js App" />
  <Button label="Hello2" @click="handleClick" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Button from "primevue/button";
export default {
  name: "App",
  components: {
    HelloWorld,
    Button,
  },
  setup() {
    const handleClick = () => {
      console.log("hello");
    };

    return {
      handleClick,
    };
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
