<template>
  <footer>
    <h4>Fabio Rodriguez &copy; 2021</h4>
    <ul>
      <li>
        <a href="https://github.com/frodri13" target="_blank"
          ><img src="" alt="github page"
        /></a>
      </li>
      <li>
        <a href="https://www.linkedin.com/in/rodriguezfabio/" target="_blank"
          ><img src="" alt="linkedin page"
        /></a>
      </li>
    </ul>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
footer {
  background: gray;
  color: white;
  min-height: 10vh;
  padding: 0% 5%;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  flex-direction: row;
}
ul {
  flex: 1 1 40rem;
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-direction: row;
}
h4 {
  flex: 1 1 40rem;
  margin-top: 2.5rem;
}
li {
  margin-top: 1rem;
  margin-right: 10rem;
}
</style>
