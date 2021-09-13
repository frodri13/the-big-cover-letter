<template>
  <video width="383" height="220" controls>
    <source :src="resolve_img_url(video_name)" />
  </video>
</template>

<script>
export default {
  name: "Video",
  props: {
    video_name: String,
  },
  methods: {
    resolve_img_url: function(path) {
      let videos = require.context("../assets", false, /\.mp4$/);
      return videos("./" + path);
    },
  },
};
</script>

<style scoped>
video {
  float: right;
  z-index: 5;
  position: absolute;
  top: 25vh;
  right: 33vh;
}
</style>
