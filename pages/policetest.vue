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
        <h1 class="mt-4">วิชาความรู้ทั่วไป</h1>
      </div>
      <!-- 1 -->
      <div>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">1. 6 7 11 20 36...</h6>

          </template>
          <b-card-text>ก. 60.</b-card-text>
          <b-card-text>ข. 61 .</b-card-text>
          <b-card-text>ค. 62 .</b-card-text>
          <b-card-text>ง. 67.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ข <br>
              <b>อธิบาย :</b> -</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">2. 1 93 5 110 9 127 13...</h6>

          </template>
          <b-card-text>ก. 132.</b-card-text>
          <b-card-text>ข. 139 .</b-card-text>
          <b-card-text>ค. 142  .</b-card-text>
          <b-card-text>ง. 144 .</b-card-text>

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
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">3. กบ : จรเข้ </h6>

          </template>
          <b-card-text>ก. วาฬ : นกกระจอกเทศ .</b-card-text>
          <b-card-text>ข. มด : เต่า .</b-card-text>
          <b-card-text>ค. นกเอี้ยง : ฮูก  .</b-card-text>
          <b-card-text>ง. คน : เพนกวิน.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b>ค<br>
              <b>อธิบาย :</b> -</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">4. พัทยา : กรุงเทพ </h6>

          </template>
          <b-card-text>ก. เทศบาล : สุขาภิบาล .</b-card-text>
          <b-card-text>ข. กรม : กอง  .</b-card-text>
          <b-card-text>ค. กงสุล : สถานีอนามัย  .</b-card-text>
          <b-card-text>ง. ทหาร : สถานทูต .</b-card-text>

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
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">5. ตำรวจ : อัยการ</h6>

          </template>
          <b-card-text>ก. วิศวกร : นักร้อง .</b-card-text>
          <b-card-text>ข. ทนาย : ผู้พิพากษา.</b-card-text>
          <b-card-text>ค. นักมวย : นักดนตรี  .</b-card-text>
          <b-card-text>ง. ครู : พยาบาล.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ข <br>
              -
            </em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">6. 3 + 7 x 10 / 5 - 2 = ?"</h6>

          </template>
          <b-card-text>ก. 13.</b-card-text>
          <b-card-text>ข. 14 .</b-card-text>
          <b-card-text>ค. 15  .</b-card-text>
          <b-card-text>ง. 18.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค
            <br><b>อธิบาย</b> -
            </em>
           </template>
        </b-card>
        </b-card-group>
        <!-- 4 -->
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">7. ถ้า a^3 = 27 และ abc = 12 และ (ab)^2 = 36 อยากทราบว่า c เท่ากับเท่าไร</h6>

          </template>
          <b-card-text>ก. 2.</b-card-text>
          <b-card-text>ข. 3 .</b-card-text>
          <b-card-text>ค. 4 .</b-card-text>
          <b-card-text>ง. 6 .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก <br>
              <b>อธิบาย :</b> -</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">8. ปริมาตรของรูปทรงปิรามิดฐานสี่เหลียมจัตุรัสยาวด้านละ 3 นิ้ว สูง 4 นิ้ว เมื่อนำไปรวมกับปริมาตรของปรึซึมฐานสามเหลี่ยมด้านเท่า ซึ่งยาวด้านละ 4 นิ้ว และปริซึมสูง 4 นิ้ว จะได้ปริมาตรรวมเท่ากับเท่าไร</h6>

          </template>
          <b-card-text>ก. 39.</b-card-text>
          <b-card-text>ข. 40.</b-card-text>
          <b-card-text>ค. 41.</b-card-text>
          <b-card-text>ง. 42.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ข
            <br><b>อธิบาย</b> -
            </em>
           </template>
        </b-card>
        </b-card-group>
        <!-- 5 -->
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">9. อัตราส่วนของผู้เข้าสอบกับผู้สอบได้เท่ากับ 200 : 3 ในการสอบครั้งนี้มีผู้สอบได้จำนวน 330 คน อยากทราบว่ามีผู้เข้าสอบทั้งหมดกี่คน</h6>

          </template>
          <b-card-text>ก. 2,500.</b-card-text>
          <b-card-text>ข. 23,000  .</b-card-text>
          <b-card-text>ค. 22,000  .</b-card-text>
          <b-card-text>ง. 20,000 .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค <br>
              <b>อธิบาย :</b> -</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">10. มุมภายในของรูป 7 เหลี่ยมเท่ากับเท่าไร</h6>

          </template>
          <b-card-text>ก. 720 .</b-card-text>
          <b-card-text>ข. 840 .</b-card-text>
          <b-card-text>ค. 900   .</b-card-text>
          <b-card-text>ง. 1,100.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค
            <br><b>อธิบาย</b> -
            </em>
           </template>
        </b-card>
        </b-card-group>
        
        <!-- 6 -->
        <div class="container-fluid">
          <h1 class="mt-4">พ.ร.บ.ตำรวจแห่งชาติ พ.ศ.2547</h1>
        </div>
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">1. พระราชบัญญัติตำรวจแห่งชาติ 2547 มีผลบังคับใช้เมื่อใด</h6>

          </template>
          <b-card-text>ก. ตั้งแต่วันถัดจากวันประกาศในราชกิจจานุเบกษา .</b-card-text>
          <b-card-text>ข. ตั้งแต่วันประกาศในราชกิจจานุเบกษา .</b-card-text>
          <b-card-text>ค. ตั้งแต่วันประกาศในราชกิจจานุเบกษา 180 วัน  .</b-card-text>
          <b-card-text>ง. วันที่ 14 เม.ย.2547.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ข <br>
              <b>อธิบาย :</b> -</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">2. “ประธานกรรมการ” หมายความว่า</h6>

          </template>
          <b-card-text>ก. ประธาน ก.ตร. .</b-card-text>
          <b-card-text>ข. ประธาน ก.ตช. .</b-card-text>
          <b-card-text>ค. ประธานกรรมการนโยบายตำรวจแห่งชาติ   .</b-card-text>
          <b-card-text>ง. ประธาน ตร. .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค
            <br><b>อธิบาย</b>-
            </em>
           </template>
        </b-card>
        </b-card-group>
        <!-- 3 -->
        <!-- 7 -->
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">3. “กองทุน” หมายความว่า</h6>

          </template>
          <b-card-text>ก. กองทุนเพื่อการสืบสวนคดีอาญา.</b-card-text>
          <b-card-text>ข. กองทุนเพื่อการสอบสวนคดีอาญา .</b-card-text>
          <b-card-text>ค. กองทุนเพื่อการสืบสวนและสอบสวนคดีอาญา  .</b-card-text>
          <b-card-text>ง. กองทุนเพื่อการสืบสวนสอบสวนและป้องกันปาบปรามคดีอาญา .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค <br>
              <b>อธิบาย :</b> -            
              </em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">4. ผู้ใด เป็นผู้รักษาการตามพระราชบัญญัตินี้</h6>

          </template>
          <b-card-text>ก. นายกรัฐมนตรี .</b-card-text>
          <b-card-text>ข. รองนายกรัฐมนตรี ที่ได้รับมอบหมายให้ควบคุมดูแลสำนักงานตำรวจแห่งชาติ .</b-card-text>
          <b-card-text>ค. รัฐมนตรีว่าการกระทรวงยุติธรรม  .</b-card-text>
          <b-card-text>ง. ถูกเฉพาะข้อ ก. และ ข้อ ข. .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก
            <br><b>อธิบาย</b> -
            </em>
           </template>
        </b-card>
        </b-card-group>
        <!-- 8 -->
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">5. การออกกฎกระทรวงเพื่อปฏิบัติการตามพระราชบัญญัตินี้ เป็นอำนาจของ</h6>

          </template>
          <b-card-text>ก. นายกรัฐมนตรี .</b-card-text>
          <b-card-text>ข. รองนายกรัฐมนตรี ที่ได้รับมอบหมายให้ควบคุมดูแลสำนักงานตำรวจแห่งชาติ .</b-card-text>
          <b-card-text>ค. รัฐมนตรีว่าการกระทรวงยุติธรรม.</b-card-text>
          <b-card-text>ง. คณะรัฐมนตรี.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก <br>
              <b>อธิบาย :</b> -</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">6. ข้อใดกล่าวถูกต้อง</h6>

          </template>
          <b-card-text>ก. สำนักงานตำรวจแห่งชาติเป็นส่วนราชการมีฐานะเป็นนิติบุคคลอยู่ในบังคับบัญชาของปลัดสำนักนายกรัฐมนตรี .</b-card-text>
          <b-card-text>ข. สำนักงานตำรวจแห่งชาติเป็นส่วนราชการมีฐานะเป็นนิติบุคคลอยู่ในบังคับบัญชาของรัฐมนตรีประจำนายกรัฐมนตรี  .</b-card-text>
          <b-card-text>ค. สำนักงานตำรวจแห่งชาติเป็นส่วนราชการมีฐานะเป็นนิติบุคคลอยู่ในบังคับบัญชาของนายกรัฐมนตรี   .</b-card-text>
          <b-card-text>ง. สำนักงานตำรวจแห่งชาติอยู่ในบังคับบัญชาของนายกรัฐมนตรี.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค
            <br><b>อธิบาย</b> -            
            </em>
           </template>
        </b-card>
        </b-card-group>
        <!-- 9 -->
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">7. สำนักงานตำรวจแห่งชาติมีอำนาจหน้าที่กี่ประการ</h6>

          </template>
          <b-card-text>ก. 6 ประการ .</b-card-text>
          <b-card-text>ข. 7 ประการ   .</b-card-text>
          <b-card-text>ค. 8 ประการ .</b-card-text>
          <b-card-text>ง. 9 ประการ.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ข <br>
              <b>อธิบาย :</b> - </em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">8. สำนักงานตำรวจแห่งชาติมีหน้าที่ส่งเสริมให้ท้องถิ่นและชุมชน มีส่วนร่วมในกิจการตำรวจเพื่อป้องกันและปราบปรามการกระทำความผิดทางอาญา รักษาความสงบเรียบร้อยและรักษาความปลอดภัยของประชาชนตามความเหมาะสม และความต้องการของแต่ละพื้นที่ ทั้งนี้ การดำเนินการมีส่วนร่วมให้เป็นไปตามหลักเกณฑ์และวิธีการที่.........กำหนด</h6>

          </template>
          <b-card-text>ก. ก.ต.ช.  .</b-card-text>
          <b-card-text>ข. ก.ตร. .</b-card-text>
          <b-card-text>ค. กฎกระทรวง .</b-card-text>
          <b-card-text>ง. พระราชกฤษฎีกา .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก
            <br><b>อธิบาย</b> -
            </em>
           </template>
        </b-card>
        </b-card-group>
        <!-- 10 -->
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">9. ข้าราชการตำรวจตำแหน่งใดหรือปฏิบัติหน้าที่ใด จะเป็นข้าราชการตำรวจประเภทไม่มียศให้ตราเป็น</h6>

          </template>
          <b-card-text>ก. ก.ต.ช..</b-card-text>
          <b-card-text>ข. ก.ตร. .</b-card-text>
          <b-card-text>ค. กฎกระทรวง  .</b-card-text>
          <b-card-text>ง. พระราชกฤษฎีกา .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ง <br>
              <b>อธิบาย :</b> -</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">10. กรณีที่ ก.ต.ช. เห็นว่ามีความจำเป็นเพื่อประโยชน์ในการปฏิบัติหน้าที่ ก.ต.ช. จะกำหนดให้ข้าราชการตำรวจต้องปฏิบัติหน้าที่ตามวันหยุดราชการตามที่คณะรัฐมนตรีกำหนดก็ได้หรือไม่</h6>

          </template>
          <b-card-text>ก. ได้ แต่ต้องได้รับอนุมัติจากคณะรัฐมนตรี.</b-card-text>
          <b-card-text>ข. ได้ ไม่ต้องขออนุมัติผู้ใด  .</b-card-text>
          <b-card-text>ค. ไม่ได้ เพราะขัดต่อมติของคณะรัฐมนตรีที่ทุกส่วนราชการต้องถือปฏิบัติตาม .</b-card-text>
          <b-card-text>ง. ไม่ได้ เพราะเป็นการขัดต่อสิทธิขั้นพื้นฐานของประชาชนตามรัฐธรรมนูญ.</b-card-text>

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