<template>
  <div class="desktopComponent">
    <div class="headerContainer">
      <Header />
    </div>
    <img class="sol-bulut" src="../../../assets/giris/sol-bulut.svg" alt="" />
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
.headerContainer {
  /* height: 100%;
  width: 100%; */
  background: #e5e5e5;
  width: 100%;
  height: 465px;
  left: 0px;
  top: 0px;
  border: 1px solid red;

  background: linear-gradient(
      180deg,
      #33a5df 16.85%,
      rgba(51, 165, 223, 0) 58.86%
    ),
    linear-gradient(0deg, #e9f3f9 12.23%, rgba(233, 243, 249, 0) 77.17%),
    url("../../../assets/giris/bulutlar.png");
  display: flex;
  justify-content: center;
  align-items: flex-start;
}
.sol-bulut {
  border: 1px solid red;
  width: 507px;
  height: 183px;
  left: 148px;
  top: 83px;

  /* background: url(19.png); */
  /* transform: matrix(-1, 0, 0, 1, 0, 0); */
}
</style>
