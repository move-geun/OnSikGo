<template>
  <div>
    <div class="mt-10">
      <span>π§ββοΈμ¬λ¬λΆμ λμμ΄ νμν κ³³μΌλ‘ μ°κ²°ν΄λλ¦½λλ€π§ββοΈ</span>
    </div>
    <div>
      <img src="@/assets/images/donation_need.jpg" alt="κΈ°λΆμ¬μ§μ΄μλκ².." />
      <!-- <i class="fa-solid fa-arrow-down fa-xl"></i> -->
      <br />
      <div class="mt-10">
        <span style="color: black"
          >κΈ°λΆλ μ κ΅­ νΈλλ±ν¬ μ¬μ΄νΈλ₯Ό ν΅ν΄ κ°λ₯ν©λλ€</span
        >
        <br />
        <div class="text-start mt-10 ml-8 mr-8">
          <span style="color: black; font-size: 1.3rem"
            >1. νΈλλ±ν¬ ννμ΄μ§ μ μ²­</span
          >
          <br />
          <div class="mt-5">
            <span style="color: black; font-size: 0.7rem"
              >μ κ΅­νΈλλ±ν¬ ννμ΄μ§(www.foodbank1377.org)μ μ μνμ¬
              <br />κΈ°λΆνμμΌλ‘ κ°μνμ¬ κΈ°λΆ μ μ²­μ ν  μ μμ΅λλ€.</span
            >
          </div>
        </div>
        <div class="d-flex justify-content-end mr-8">
          <button @click="moveFood" id="dona_btn">νΈλλ±ν¬ μ¬μ΄νΈ</button>
        </div>

        <div class="text-start mt-5 ml-8 mr-8">
          <span style="color: black; font-size: 1.3rem"
            >2. νΈλλ±ν¬ μ ν μ μ²­</span
          >
          <br />
          <div class="mt-5">
            <span style="color: black; font-size: 0.7rem"
              >β μ κ΅­λ¨μ λκ·λͺ¨ κΈ°λΆ μ μ²­ : β 02-713-1377 <br />
              β μ§μ­λ¨μ μκ·λͺ¨ κΈ°λΆ μ μ²­ : β 1688-1377
            </span>
          </div>
        </div>
        <div class="text-start mt-16 ml-8 mr-8">
          <span style="color: black; font-size: 1.3rem"
            >3. κΈ°λΆ μν κ΄λ ¨ λ²λ Ή</span
          >
          <br />
          <div class="mt-5">
            <span style="color: black; font-size: 0.8rem"
              >μν κΈ°λΆμ λν λ²λ Ήκ³Ό <br />
              μν κΈ°λΆν  κ²½μ°μ λ°μ μ μλ ννλ μ μ μμ΅λλ€.
            </span>
          </div>
        </div>
        <div class="d-flex justify-content-end mr-8">
          <button @click="donaLaw" id="dona_btn">κΈ°λΆ μν κ΄λ ¨ λ²λ Ή</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "DonationView",
  methods: {
    moveFood() {
      var link2 = "https://www.foodbank1377.org/";
      window.open(link2);
    },
    donaLaw() {
      var link3 =
        "https://easylaw.go.kr/CSP/CnpClsMain.laf?popMenu=ov&csmSeq=703&ccfNo=2&cciNo=1&cnpClsNo=2&menuType=cnpcls&search_put=";
      window.open(link3);
    },
  },
};
</script>

<style scoped>
img {
  height: inherit;
  width: 100%;
  margin: 5% 0%;
}
#dona_btn {
  width: 50%;
  height: 40px;
  background-color: white;
  font-size: 15px;
  font-weight: 800;
  color: rgba(140, 184, 131, 100%);
  border-radius: 20px;
  margin: 3% 0;
  padding: 3%;
  box-shadow: 10px 5px 5px rgba(0, 0, 0, 0.2);
}
</style>
