<template>
  <div class="middlePart">
    <div class="loginPart">
      <div class="hosgeldiniz">Hoşgeldiniz</div>
      <div class="giris">Giriş Yapın</div>
      <input type="text" class="tcKimlik" placeholder="T.C. Kimlik Numaranız" />
      <input type="text" class="sifre" placeholder="Şifreniz" />
      <!-- space between here -->
      <div class="inputChoices">
        <div class="hatirlaGroup">
          <img
            src="../../../assets/giris/check-dolu.svg"
            alt=""
            class="hatirlaLogo"
          />
          <div class="hatirlaText">Beni Hatırla</div>
        </div>
        <div class="unuttumGroup">
          <img
            class="unuttumLogo"
            src="../../../assets/giris/flash-circle-1.svg"
            alt=""
          />
          <div class="unuttumText">Şifremi Unuttum</div>
        </div>
      </div>
      <button class="tamamBtn">Tamam</button>
    </div>
    <div class="carouselPart">
      <img
        class="imageGroup-1"
        src="../../../assets/giris/imageGroup-1.svg"
        alt=""
      />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.middlePart {
  width: 100%;
  /* border: 1px solid black; */
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
  width: 29.25rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  /* border: 1px solid black; */
  padding: 0;
}
.hosgeldiniz {
  /* border: 1px solid black; */
  width: 120px;
  height: 29px;
  /* baslik3 */
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 22px;
  line-height: 130%;
  /* identical to box height, or 29px */
  text-align: center;
  /* Primary */
  color: #3c4e69;
  margin-bottom: 7px;
  /* align-self: flex-start; */
}
.giris {
  width: 177px;
  height: 47px;

  /* baslik1 */

  font-family: Nunito Sans;
  font-style: normal;
  font-weight: 800;
  font-size: 36px;
  line-height: 130%;
  /* identical to box height, or 47px */

  text-align: center;
  letter-spacing: -0.01em;

  /* Secondary */

  color: #32a5df;
  margin-bottom: 32px;
}
.tcKimlik {
  width: 468px;
  height: 60px;
  margin-bottom: 25px;
  background: #ffffff;
  /* Form Shadow */

  /* box-shadow: 0px 3px 3px rgba(0, 0, 0, 0.03); */
  border-radius: 6px;
  border: none;
}
.sifre {
  width: 468px;
  height: 60px;

  background: #ffffff;
  /* Form Shadow */

  /* box-shadow: 0px 3px 3px rgba(0, 0, 0, 0.03); */
  border-radius: 6px;
  border: none;
}
.inputChoices {
  height: auto;
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  /* border: 1px solid red; */
  margin-top: 20px;
}
.hatirlaGroup {
  width: auto;
  height: auto;
  /* border: 2px solid black; */
  display: flex;
  flex-direction: row;
  justify-self: flex-start;
  align-items: center;
}
.unuttumGroup {
  width: auto;
  height: auto;
  /* border: 2px solid black; */
  display: flex;
  flex-direction: row;
  justify-self: flex-start;
  align-items: center;
}
.hatirlaLogo {
  width: auto;
  height: auto;
  margin-right: 7px;
}
.unuttumLogo {
  width: auto;
  height: auto;
  margin-right: 7px;
}
.hatirlaText {
  /* padding-top: 2em; */
}

.unuttumText {
}
.tamamBtn {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  padding: 12px 20px 11px;

  width: 468px;
  height: 50px;

  /* Turuncu */

  background: #ff8038;
  border-radius: 6px;

  /* buton-text-orta */

  font-family: Nunito Sans;
  font-style: normal;
  font-weight: 800;
  font-size: 16px;
  line-height: 110%;
  /* identical to box height, or 18px */

  display: flex;
  align-items: center;
  text-align: center;

  /* Beyaz */

  color: #ffffff;

  /* Inside auto layout */

  flex: none;
  order: 0;
  flex-grow: 0;
  margin: 0px 10px;

  border: none;
  margin-top: 19px;
}
.carouselPart {
  width: 100%;
  height: auto;
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  align-items: center;
  /* border: 5px solid blue; */
  padding-right: 5em;
}
.imageGroup-1 {
  width: auto;
  height: auto;
  /* border: 2px solid red; */
  /* justify-self: flex-end; */
}
</style>
