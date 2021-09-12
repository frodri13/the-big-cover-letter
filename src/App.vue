<template>
  <Phone />
  <Monitor />
</template>

<script>
import Phone from "./components/Phone.vue";
import Monitor from "./components/Monitor.vue";

export default {
  name: "App",
  components: {
    Phone,
    Monitor,
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
