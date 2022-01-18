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
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.headerComponent {
  width: 100%;
  height: 465px;

  background: linear-gradient(
      180deg,
      #33a5df 16.85%,
      rgba(51, 165, 223, 0) 58.86%
    ),
    linear-gradient(0deg, #e9f3f9 12.23%, rgba(233, 243, 249, 0) 77.17%),
    url("../../../assets/giris/bulutlar.png");
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: flex-start;
  /* border: 1px solid red; */
}
.container {
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
</style>
