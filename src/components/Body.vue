<template>
  <div>
    <div>
      <Phone />
    </div>
    <div class="container">
      <Monitor video="video.mp4" />
    </div>
  </div>
</template>

<script>
import Phone from "./Phone.vue";
import Monitor from "./Monitor.vue";

export default {
  name: "Body",
  components: {
    Phone,
    Monitor,
  },
};
</script>

<style scoped>
div {
  display: flex;
  height: 90vh;
  width: 100vh;
}
.container {
  position: relative;
}
</style>
