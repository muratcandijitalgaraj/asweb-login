<template>
  <div class="headerComponent">
    <div class="container">
      <div class="logoContainer">
        <div class="logo">
          <img class="logoImg" src="../../../assets/giris/logo.svg" alt="" />
        </div>
        <div class="islemler">ONLINE İŞLEMLER</div>
      </div>
      <div class="signupContainer">
        <div class="signupPara">Henüz üye değil misiniz?</div>
        <button class="signupBtn"><div class="btnPara">Kayıt Olun</div></button>
      </div>
    </div>
    <img class="sol-bulut" src="../../../assets/giris/sol-bulut.svg" alt="" />
    <img class="sag-bulut" src="../../../assets/giris/sag-bulut.svg" alt="" />
    <div class="middlePartContainer">
      <MiddlePart />
    </div>
  </div>
</template>

<script>
import MiddlePart from "./MiddlePart.vue";
export default { components: { MiddlePart } };
</script>

<style scoped>
.headerComponent {
  width: 100%;
  height: 465px;

  background: url("../../../assets/giris/bulutlar.png");
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  border: 1px solid red;
}
.container {
  /* border: 1px solid black; */
  width: 70%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: flex-start;
  padding-top: 1.875rem;
  /* border: 1px solid red; */
}
.logoContainer {
  /* border: 1px solid red; */
  height: auto;
  width: 100%;
  display: flex;
  flex-direction: row;
  /* justify-content: center;
  align-items: center; */
  width: auto;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  /* border: 1px solid red; */
}
.logo {
  width: 12.542rem;
  height: 4.375rem;
  margin-right: 1.458rem;
}
.logoImg {
  width: 100%;
  height: 100%;
}
.islemler {
  width: 69px;
  height: 42px;

  /* text3 */

  font-family: Nunito Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 140%;
  /* or 21px */

  letter-spacing: -0.01em;

  color: #ffffff;
}
.signupContainer {
  /* border: 1px solid red; */
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  height: auto;
  width: auto;
}
.signupPara {
  width: 170px;
  height: 17px;

  /* buton-text-kucuk */

  font-family: Nunito Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 15px;
  line-height: 110%;
  /* identical to box height, or 17px */

  display: flex;
  align-items: center;
  text-align: center;

  /* Beyaz */

  color: #ffffff;

  margin-right: 1.25rem;
}
.signupBtn {
  /* buton/kucuk/primary */

  /* Auto layout */

  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  padding: 12px 20px 11px;

  width: 114px;
  height: 40px;

  /* Beyaz */

  background: #ffffff;
  border-radius: 6px;
  border: none;
}
.btnPara {
  width: 74px;
  height: 17px;

  /* buton-text-kucuk */

  font-family: Nunito Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 15px;
  line-height: 110%;
  /* identical to box height, or 17px */

  display: flex;
  align-items: center;
  text-align: center;

  /* Button Primary */

  color: #ff7c32;

  /* Inside auto layout */

  flex: none;
  order: 0;
  flex-grow: 0;
  margin: 0px 10px;
}
.sol-bulut {
  /* border: 1px solid red; */
  width: auto;
  height: 183px;
  margin-bottom: 100%;
  /* justify-self: flex-start; */
  /* align-self: flex-start; */
  position: absolute;
  left: 0;
  top: 83px;
}
.sag-bulut {
  width: auto;
  height: 183px;
  position: absolute;
  top: 3.188rem;
  right: 0;
}
/* middle part starts */
.middlePartContainer {
  border: 5px solid black;
  width: 100%;
  margin-left: 23.188rem;
}
/* .middlePart {
  width: 70%;
  border: 1px solid black;
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  padding: 0;
  margin: 0;
  justify-self: flex-start;
  align-self: flex-start;
}
.loginPart {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
} */
</style>
