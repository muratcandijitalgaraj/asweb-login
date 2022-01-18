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
  /* height: 100%;
  width: 100%; */
  background: #e5e5e5;
  width: 1920px;
  height: 465px;
  left: 0px;
  top: 0px;

  background: linear-gradient(
      180deg,
      #33a5df 16.85%,
      rgba(51, 165, 223, 0) 58.86%
    ),
    linear-gradient(0deg, #e9f3f9 12.23%, rgba(233, 243, 249, 0) 77.17%),
    url("../../../assets/giris/bulutlar.png");
}
</style>
