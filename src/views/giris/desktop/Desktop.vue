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
  background: #e5e5e5;
}
</style>
