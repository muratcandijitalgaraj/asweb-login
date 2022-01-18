<template>
  <div class="desktopComponent">
    <Bulutlar />
  </div>
</template>

<script>
import Bulutlar from "./Bulutlar.vue";
export default { components: { Bulutlar } };
</script>

<style scoped>
.desktopComponent {
  height: 100%;
  width: 100%;
  background: #e5e5e5;
}
</style>
