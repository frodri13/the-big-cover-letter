<template>
  <div>
    <div>
      <Phone @phoneKey="btnClicked" />
    </div>
    <div class="container">
      <Monitor :video="videoName" />
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
  methods: {
    btnClicked(e) {
      if (e == "btn-1") {
        console.log(this.videoName);
        this.videoName = "video2.mp4";
        console.log(this.videoName);
      }
    },
  },
  data() {
    return {
      videoName: "video1.mp4",
    };
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
