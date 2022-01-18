<template>
  <div class="desktopComponent">
    <Header />
  </div>
</template>

<script>
import Header from "./Header.vue";
export default { components: { Header } };
</script>

<style scoped>
.desktopComponent {
  height: 100%;
  width: 100%;
  background: #e9f3f9;
}
</style>
