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
        <h1 class="mt-4">ข้อสอบท้องถิ่น</h1>
      </div>
      <!-- 1 -->
      <div>
        <b-card-group deck>
          <b-card
            header-tag="header"
            footer-tag="footer"
          >
            <template v-slot:header>
              <h6 class="mb-0">1.กระทรวง ทบวง กรม จะมอบอำนาจ หรือสั่งการไปยังหัวหน้าคณะผู้แทนให้แจ้งผ่านหน่วยงานใด </h6>

            </template>
            <b-card-text>ก. สถานกงสุลใหญ่.</b-card-text>
            <b-card-text>ข. สถานเอกอัครราชทูต .</b-card-text>
            <b-card-text>ค. กรมพิธีการทูต .</b-card-text>
            <b-card-text>ง. กระทรวงการต่างประเทศ.</b-card-text>

            <template v-slot:footer>
              <em><b>ตอบ</b> ง <br>
                <b>อธิบาย :</b> -</em>
            </template>
          </b-card>

          <b-card
            header-tag="header"
            footer-tag="footer"
          >
            <template v-slot:header>
              <h6 class="mb-0">2. ใครที่สามารถวางแผนและประสานกิจกรรมให้มีการใช้ทรัพยากรร่วมกันได้</h6>

            </template>
            <b-card-text>ก. ปลัดกระทรวง.</b-card-text>
            <b-card-text>ข. หัวหน้ากลุ่มภารกิจ.</b-card-text>
            <b-card-text>ค. หัวหน้าส่วนระดับกรมขึ้นไป .</b-card-text>
            <b-card-text>ง. ถูกทุกข้อ .</b-card-text>

            <template v-slot:footer>
              <em><b>ตอบ</b> ง
                <br><b>อธิบาย</b> -
              </em>
            </template>
          </b-card>
        </b-card-group>

        <!-- 2 -->

        <br>
        <b-card-group deck>
          <b-card
            header-tag="header"
            footer-tag="footer"
          >
            <template v-slot:header>
              <h6 class="mb-0">3. การจัดระเบียบราชการของกระทรวง ประกอบด้วยอะไรบ้าง </h6>

            </template>
            <b-card-text>ก. สำนักงานรัฐมนตรี .</b-card-text>
            <b-card-text>ข. สำนักงานปลัดกระทรวง.</b-card-text>
            <b-card-text>ค. กรม .</b-card-text>
            <b-card-text>ง. ถูกทุกข้อ.</b-card-text>

            <template v-slot:footer>
              <em><b>ตอบ</b>ง<br>
                <b>อธิบาย :</b> -</em>
            </template>
          </b-card>

          <b-card
            header-tag="header"
            footer-tag="footer"
          >
            <template v-slot:header>
              <h6 class="mb-0">4.บุคคลใดเป็นข้าราชการเมือง</h6>

            </template>
            <b-card-text>ก. เลขาธิการนายกรัฐมนตรี.</b-card-text>
            <b-card-text>ข. รองเลขาธิการคณะรัฐมนตรี .</b-card-text>
            <b-card-text>ค. เลขาธิการคณะรัฐมนตรี .</b-card-text>
            <b-card-text>ง. ผู้ช่วยเลขาธิการคณะรัฐมนตรี.</b-card-text>

            <template v-slot:footer>
              <em><b>ตอบ</b> ก
                <br><b>อธิบาย</b> -
              </em>
            </template>
          </b-card>
        </b-card-group>

        <!-- 3 -->
        <br>
        <b-card-group deck>
          <b-card
            header-tag="header"
            footer-tag="footer"
          >
            <template v-slot:header>
              <h6 class="mb-0">5. ใครเป็นผู้บังคับบัญชาข้าราชการในสำนักงานเลขาธิการนายกรัฐมนตรี</h6>

            </template>
            <b-card-text>ก. เลขาธิการนายกรัฐมนตรี .</b-card-text>
            <b-card-text>ข. เลขาธิการคณะรัฐมนตรี.</b-card-text>
            <b-card-text>ค. ปลัดสำนักนายกรัฐมนตรี .</b-card-text>
            <b-card-text>ง. นายกรัฐมนตรี.</b-card-text>

            <template v-slot:footer>
              <em><b>ตอบ</b> ก <br>
                -
              </em>
            </template>
          </b-card>

          <b-card
            header-tag="header"
            footer-tag="footer"
          >
            <template v-slot:header>
              <h6 class="mb-0">6. ข้อใดไม่ใช่อำนาจหน้าที่ของสำนักงานปลัดสำนักนายกรัฐมนตรี"</h6>

            </template>
            <b-card-text>ก. ควบคุมข้าราชการประจำในสำนักนายก.</b-card-text>
            <b-card-text>ข. อำนาจเกี่ยวกับ คณะรัฐมนตรี รัฐสภา และราชการในพระองค์ .</b-card-text>
            <b-card-text>ค. บังคับบัญชาข้าราชการองจาก นายกรัฐมนตรี รองนายก รมต.ประจำสำนักนายก .</b-card-text>
            <b-card-text>ง. บังคับบัญชาข้าราชการใน สำนักงานปลัดสำนักนายกรัฐมนตรี.</b-card-text>

            <template v-slot:footer>
              <em><b>ตอบ</b> ข
                <br><b>อธิบาย</b> -
              </em>
            </template>
          </b-card>
        </b-card-group>
        <!-- 4 -->
        <br>
        <b-card-group deck>
          <b-card
            header-tag="header"
            footer-tag="footer"
          >
            <template v-slot:header>
              <h6 class="mb-0">7. ผู้บังคับบัญชาข้าราชการในสำนักงานปลัดสำนักนายกรัฐมนตรีคือ</h6>

            </template>
            <b-card-text>ก. ปลัดกระทรวงมหาดไทย.</b-card-text>
            <b-card-text>ข. ปลัดสำนักนายกรัฐมนตรี.</b-card-text>
            <b-card-text>ค. นายกรัฐมนตรี .</b-card-text>
            <b-card-text>ง. รองนายกรัฐมนตรี.</b-card-text>

            <template v-slot:footer>
              <em><b>ตอบ</b> ข <br>
                <b>อธิบาย :</b> -</em>
            </template>
          </b-card>

          <b-card
            header-tag="header"
            footer-tag="footer"
          >
            <template v-slot:header>
              <h6 class="mb-0">8. เมื่อนายกรัฐมนตรี ตาย, ขาดคุณสมบัติ, จำคุก, สภาลงมติไม่ไว้วางใจ, ศาลวินิจฉัยความเป็นนายกสิ้นสุดลง</h6>

            </template>
            <b-card-text>ก. ให้คณะรัฐมนตรี มอบหมายให้ รองนายกรัฐมนตรี ปฏิบัติหน้าที่แทน.</b-card-text>
            <b-card-text>ข. ให้คณะรัฐมนตรี มอบหมายให้ รองนายกรัฐมนตรี รักษาราชการแทน.</b-card-text>
            <b-card-text>ค. ให้นายกรัฐมนตรี มอบหมายให้ รองนายกรัฐมนตรี ปฏิบัติหน้าที่แทน.</b-card-text>
            <b-card-text>ง. ให้นายกรัฐมนตรี มอบหมายให้ รัฐมนตรีประจำสำนักนายกรัฐมนตรี รักษาราชการแทน.</b-card-text>

            <template v-slot:footer>
              <em><b>ตอบ</b> ก
                <br><b>อธิบาย</b> -
              </em>
            </template>
          </b-card>
        </b-card-group>
        <!-- 5 -->
        <br>
        <b-card-group deck>
          <b-card
            header-tag="header"
            footer-tag="footer"
          >
            <template v-slot:header>
              <h6 class="mb-0">9. การเปลี่ยนชื่อส่วนราชการ ของ สำนักนายกรัฐมนตรี กระทรวง ทบวง หรือกรม ให้ออกเป็นกฎหมายใด</h6>

            </template>
            <b-card-text>ก. พระราชบัญญัติ.</b-card-text>
            <b-card-text>ข. พระราชกฤษฎีกา .</b-card-text>
            <b-card-text>ค. กฎกระทรวง .</b-card-text>
            <b-card-text>ง. พระราชกำหนด .</b-card-text>

            <template v-slot:footer>
              <em><b>ตอบ</b> ข <br>
                <b>อธิบาย :</b> -</em>
            </template>
          </b-card>

          <b-card
            header-tag="header"
            footer-tag="footer"
          >
            <template v-slot:header>
              <h6 class="mb-0">10. การยุบส่วนราชการ ของ สำนักนายกรัฐมนตรี กระทรวง ทบวง หรือกรม ให้ออกเป็นกฎหมายใด</h6>

            </template>
            <b-card-text>ก. พระราชบัญญัติ .</b-card-text>
            <b-card-text>ข. พระราชกฤษฎีกา .</b-card-text>
            <b-card-text>ค. กฎกระทรวง .</b-card-text>
            <b-card-text>ง. ประการกระทรวง.</b-card-text>

            <template v-slot:footer>
              <em><b>ตอบ</b> ข
                <br><b>อธิบาย</b> -
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
import sidebar from "~/components/localtest/sidebar";
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