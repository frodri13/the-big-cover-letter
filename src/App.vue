<template>
  <Header />
  <Phone />
  <Monitor />
</template>

<script>
import Header from "./components/Header.vue";
import Phone from "./components/Phone.vue";
import Monitor from "./components/Monitor.vue";

export default {
  name: "App",
  components: {
    Phone,
    Monitor,
    Header,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  font-size: 62.5%;
}
</style>
