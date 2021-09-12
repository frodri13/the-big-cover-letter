<template>
  <Phone />
</template>

<script>
import Phone from "./components/Phone.vue";

export default {
  name: "App",
  components: {
    Phone,
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
