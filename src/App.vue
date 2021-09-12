<template>
  <Header />
  <Phone />
  <Monitor />
  <Footer />
</template>

<script>
import Header from "./components/Header.vue";
import Phone from "./components/Phone.vue";
import Monitor from "./components/Monitor.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Phone,
    Monitor,
    Header,
    Footer,
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
