<template>
  <video width="385" height="255" controls src="../assets/video.mp4"></video>
</template>

<script>
export default {
  name: "Video",
};
</script>

<style scoped>
video {
  float: right;
  z-index: 5;
  position: absolute;
  top: 19vh;
  right: 33vh;
}
</style>
