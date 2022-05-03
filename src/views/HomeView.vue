<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <SayHello />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import SayHello from "@/components/SayHello.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
    SayHello,
  },
};
</script>
