<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Hola></Hola>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import Hola from "@/components/Hola.vue";

export default {
  name: "home",
  components: {
    HelloWorld,
    Hola
  }
};
</script>
