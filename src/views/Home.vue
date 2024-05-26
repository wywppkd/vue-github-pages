<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <div class="footer">123</div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style scoped lang="scss">
.footer {
  background-color: #eee;
  position: fixed;
  bottom: 0;
  padding-bottom: env(safe-area-inset-bottom);
  border-bottom: 1px solid #ccc;
  width: 100%;
}
</style>