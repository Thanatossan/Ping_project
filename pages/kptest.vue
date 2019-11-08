<template>
  <div>
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
      integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T"
      crossorigin="anonymous"
    >
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.11.2/css/all.css"
    >
    <script
      src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
      integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"
      integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
      integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
      crossorigin="anonymous"
    ></script>

    <navbar />
    <sidebar />
    <div id="page-content-wrapper">
      <div class="container-fluid">
        <h1 class="mt-4">วิชาความรู้ด้านกฎหมาย</h1>
      </div>
      <!-- 1 -->
      <div>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">1. พระราชบัญญัติระเบียบข้าราชการพลเรือนพ.ศ. 2551 ประกาศในราชกิจจานุเบกษาเมื่อไร</h6>

          </template>
          <b-card-text>ก. 22 มกราคม 2551.</b-card-text>
          <b-card-text>ข. 23 มกราคม 2551 .</b-card-text>
          <b-card-text>ค. 24 มกราคม 2551 .</b-card-text>
          <b-card-text>ง. 25 มกราคม 2551.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ข. 23 มกราคม 2551 <br>
              <b>อธิบาย :</b> พระราชบัญญัติระเบียบข้าราชการพลเรือน พ.ศ. 2551 พระบาทสมเด็จพระปรมินทรมหาภูมิพลอดุลยเดช ทรงมีพระบรมราชโองการโปรดเกล้าฯ ให้ตราขึ้นไว้เมื่อ 23 มกราคม พ.ศ. 2551</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">2. พระราชบัญญัติระเบียบข้าราชการพลเรือน พ.ศ. 2551 ตราขึ้นโดยคำแนะนำและยินยอมของหน่วยงานใด</h6>

          </template>
          <b-card-text>ก. รัฐสภา.</b-card-text>
          <b-card-text>ข. สำนักนายกรัฐมนตรี .</b-card-text>
          <b-card-text>ค. สภานิติบัญญัติแห่งชาติ  .</b-card-text>
          <b-card-text>ง. วุฒิสภา.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค. สภานิติบัญญัติแห่งชาติ
            <br><b>อธิบาย</b> พระราชบัญญัติระเบียบข้าราชการพลเรือน พ.ศ. 2551 ตราขึ้นโดยคำแนะนำและยินยอมของ สภานิติบัญญัติแห่งชาติ
            </em>
           </template>
        </b-card>
        </b-card-group>
         <!-- 2 -->
         <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">1. พระราชบัญญัติระเบียบข้าราชการพลเรือนพ.ศ. 2551 ประกาศในราชกิจจานุเบกษาเมื่อไร</h6>

          </template>
          <b-card-text>ก. 22 มกราคม 2551.</b-card-text>
          <b-card-text>ข. 23 มกราคม 2551 .</b-card-text>
          <b-card-text>ค. 24 มกราคม 2551 .</b-card-text>
          <b-card-text>ง. 25 มกราคม 2551.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ข. 23 มกราคม 2551 <br>
              <b>อธิบาย :</b> พระราชบัญญัติระเบียบข้าราชการพลเรือน พ.ศ. 2551 พระบาทสมเด็จพระปรมินทรมหาภูมิพลอดุลยเดช ทรงมีพระบรมราชโองการโปรดเกล้าฯ ให้ตราขึ้นไว้เมื่อ 23 มกราคม พ.ศ. 2551</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">2. พระราชบัญญัติระเบียบข้าราชการพลเรือน พ.ศ. 2551 ตราขึ้นโดยคำแนะนำและยินยอมของหน่วยงานใด</h6>

          </template>
          <b-card-text>ก. รัฐสภา.</b-card-text>
          <b-card-text>ข. สำนักนายกรัฐมนตรี .</b-card-text>
          <b-card-text>ค. สภานิติบัญญัติแห่งชาติ  .</b-card-text>
          <b-card-text>ง. วุฒิสภา.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค. สภานิติบัญญัติแห่งชาติ
            <br><b>อธิบาย</b> พระราชบัญญัติระเบียบข้าราชการพลเรือน พ.ศ. 2551 ตราขึ้นโดยคำแนะนำและยินยอมของ สภานิติบัญญัติแห่งชาติ
            </em>
           </template>
        </b-card>
        </b-card-group>
          
      </div>
       
      

    </div>
  </div>
</template>

<script>
import navbar from "~/components/navbar";
import sidebar from "~/components/KPtest/sidebar";
export default {
  components: {
    navbar,
    sidebar
  }
};
</script>

<style>
#page-content-wrapper {
  width: auto;
  position: absolute;
  padding: 50px;
  margin-left: 220px;
}
</style>