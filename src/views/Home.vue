<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <div class="footer"></div>
  </div>
</template>

<script>
export default {
  name: "Home"
};
</script>

<style scoped lang="scss">
.home {
  height: 100vh;
  border: 4px solid red;
}
.footer {
  background-color: #eee;
  position: fixed;
  bottom: 0;
  height: constant(safe-area-inset-bottom);
  width: 100%;
}
</style>
