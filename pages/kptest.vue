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
        <h4 class="mt-4">-	พรบ.ข้าราชการพลเรือน 2551</h4><br>
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
            <h6 class="mb-0">3. ใครเป็นผู้รักษาการพระราชบัญญัติระเบียบข้าราชการพลเรือน พ.ศ. 2551</h6>

          </template>
          <b-card-text>ก. ประธานรัฐสภา .</b-card-text>
          <b-card-text>ข. ประธานสภาผู้แทนราษฎร .</b-card-text>
          <b-card-text>ค. นายกรัฐมนตรี .</b-card-text>
          <b-card-text>ง. ประธานศาลฎีกา.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b>ค. นายกรัฐมนตรี <br>
              <b>อธิบาย :</b> นายกรัฐมนตรี เป็นผู้รักษาการพระราชบัญญัติระเบียบข้าราชการพลเรือน พ.ศ. 2551</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">4. ก.พ. ย่อมาจากอะไร</h6>

          </template>
          <b-card-text>ก. กรรมการข้าราชการ .</b-card-text>
          <b-card-text>ข. กรรมการข้าราชการพลเรือน  .</b-card-text>
          <b-card-text>ค. คณะกรรมการข้าราชการ  .</b-card-text>
          <b-card-text>ง. คณะกรรมการข้าราชการพลเรือน .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ง. คณะกรรมการข้าราชการพลเรือน
            <br><b>อธิบาย</b> ก.พ. ย่อมาจาก คณะกรรมการข้าราชการพลเรือน
            </em>
           </template>
        </b-card>
        </b-card-group>

        <!-- 3 -->
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">5. ข้อใดไม่ใช่อำนาจหน้าที่ของ ก.พ.</h6>

          </template>
          <b-card-text>ก. กำหนดนโยบายและออกระเบียบเกี่ยวกับทุนของรัฐบาล .</b-card-text>
          <b-card-text>ข. พิจารณาการเกลี่ยอัตรากำลังระหว่างส่วนราชการต่างๆ ภายในกระทรวง .</b-card-text>
          <b-card-text>ค. กำกับ ดูแล ติดตาม ตรวจสอบ และประเมินผลการบริหารทรัพยากรบุคคลของข้าราชการพลเรือน  .</b-card-text>
          <b-card-text>ง. กำหนดอัตราค่าธรรมเนียมในการปฏิบัติการเกี่ยวกับการบริหารทรัพยากรบุคคล.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ข. พิจารณาการเกลี่ยอัตรากำลังระหว่างส่วนราชการต่างๆ ภายในกระทรวง <br>
              <b>อธิบาย :</b> อำนาจหน้าที่ของ ก.พ. คือ ก. กำหนดนโยบายและออกระเบียบเกี่ยวกับทุนของรัฐบาล, ข. กำกับ ดูแล ติดตาม ตรวจสอบ และประเมินผลการบริหารทรัพยากรบุคคลของข้าราชการพลเรือน, ค. กำหนดอัตราค่าธรรมเนียมในการปฏิบัติการเกี่ยวกับการบริหารทรัพยากรบุคคล
                 ส่วนข้อ ข. พิจารณาการเกลี่ยอัตรากำลังระหว่างส่วนราชการต่างๆ ภายในกระทรวง เป็นอำนาจหน้าที่ของ อ.ก.พ. กระทรวง
            </em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">6. ใครเป็นผู้บังคับบัญชาข้าราชการและบริหารราชการของ "สำนักงาน ก.พ."</h6>

          </template>
          <b-card-text>ก. นายกรัฐมนตรี.</b-card-text>
          <b-card-text>ข. รองนายกรัฐมนตรี  .</b-card-text>
          <b-card-text>ค. ปลัดกระทรวงการคลัง  .</b-card-text>
          <b-card-text>ง. เลขาธิการ ก.พ..</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ง. เลขาธิการ ก.พ.
            <br><b>อธิบาย</b> เลขาธิการ ก.พ. เป็นผู้บังคับบัญชาข้าราชการและบริหารราชการของ "สำนักงาน ก.พ."
            </em>
           </template>
        </b-card>
        </b-card-group>
        <!-- 4 -->
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">7. ข้อใดไม่ใช่ตำแหน่งข้าราชการพลเรือน</h6>

          </template>
          <b-card-text>ก. วิชาการ.</b-card-text>
          <b-card-text>ข. บริหาร .</b-card-text>
          <b-card-text>ค. อำนวยการ .</b-card-text>
          <b-card-text>ง. ปฏิบัติการ .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ง. ปฏิบัติการ <br>
              <b>อธิบาย :</b> ตำแหน่งข้าราชการพลเรือนสามัญ มี 4 ตำแหน่ง ได้แก่ บริหาร, อำนวยการ, วิชาการ และ ทั่วไป</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">8. ข้อใดกล่าวไม่ถูกต้องเกี่ยวกับองค์ประกอบของ ก.พ.</h6>

          </template>
          <b-card-text>ก. จำนวนกรรมการต้องไม่น้อยกว่า 3 คน แต่ไม่เกิน 7 คน.</b-card-text>
          <b-card-text>ข. ประธานของ ก.พ. คือ นายกรัฐมนตรี.</b-card-text>
          <b-card-text>ค. เลขาธิการ ก.พ. เป็นกรรมการและเลขานุการ.</b-card-text>
          <b-card-text>ง. มีปลัดกระทรวงการคลังเป็นกรรมการโดยตำแหน่ง.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก. จำนวนกรรมการต้องไม่น้อยกว่า 3 คน แต่ไม่เกิน 7 คน
            <br><b>อธิบาย</b> จำนวนกรรมการต้องไม่น้อยกว่า 5 คน แต่ไม่เกิน 7 คน
            </em>
           </template>
        </b-card>
        </b-card-group>
        <!-- 5 -->
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">9. สำนักงาน ก.พ. ต้องขึ้นตรงกับใคร</h6>

          </template>
          <b-card-text>ก. นายกรัฐมนตรี.</b-card-text>
          <b-card-text>ข. ปลัดกระทรวงการคลัง  .</b-card-text>
          <b-card-text>ค. เลขาธิการ ก.พ.  .</b-card-text>
          <b-card-text>ง. ผู้อำนวยการสำนักงบประมาณ .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก. นายกรัฐมนตรี <br>
              <b>อธิบาย :</b> สำนักงาน ก.พ. ต้องขึ้นตรงกับ นายกรัฐมนตรี</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">10. ข้อใดคืออำนาจหน้าที่ของสำนักงาน ก.พ.</h6>

          </template>
          <b-card-text>ก. จัดทำรายงานประจำปีเกี่ยวกับการบริหารทรัพยากรบุคคลในราชการพลเรือน .</b-card-text>
          <b-card-text>ข. เป็นศูนย์กลางข้อมูลทรัพยากรบุคคลภาครัฐ .</b-card-text>
          <b-card-text>ค. ดำเนินการเกี่ยวกับทุนเล่าเรียนหลวง  .</b-card-text>
          <b-card-text>ง. ถูกทุกข้อ.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ง. ถูกทุกข้อ
            <br><b>อธิบาย</b> -
            </em>
           </template>
        </b-card>
        </b-card-group>
        
        <!-- 6 -->
        <br><h4 class="mt-4">-	วิธีปฏิบัติราชการทางปกครอง</h4><br>

        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">1. ผู้ที่มีอำนาจออกกฎกระทรวงและประกาศเพื่อปฏิบัติการตาม พ.ร.บ. วิธีปฏิบัติราชการทางการปกครอง คือใคร</h6>

          </template>
          <b-card-text>ก. นายกรัฐมนตรี.</b-card-text>
          <b-card-text>ข. คณะรัฐมนตรี .</b-card-text>
          <b-card-text>ค. สำนักเลขาธิการนายกรัฐมนตรี  .</b-card-text>
          <b-card-text>ง. ประธานศาลปกครอง.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก. นายกรัฐมนตรี <br>
              <b>อธิบาย :</b> -</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">2. ข้อใดกล่าวไม่ถูกต้องเกี่ยวกับสิทธิประชาชนเมื่อติดต่อหน่วยงานราชการ</h6>

          </template>
          <b-card-text>ก. มีสิทธิที่จะมีที่ปรึกษาหรือผู้ทำการแทน .</b-card-text>
          <b-card-text>ข. มีสิทธิที่จะโต้แย้งแสดงพยานหลักฐาน .</b-card-text>
          <b-card-text>ค. มีสิทธิในการติดต่อโดยไม่ต้องแจ้งเจ้าหน้าที่ล่วงหน้า   .</b-card-text>
          <b-card-text>ง. มีสิทธิจะได้ตรวจดูเอกสารของเจ้าหน้าที่ .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค. มีสิทธิในการติดต่อโดยไม่ต้องแจ้งเจ้าหน้าที่ล่วงหน้า
            <br><b>อธิบาย</b>• สิทธิประโยชน์ประชาชนเมื่อติดต่อหน่วยงานราชการ<br>
                            •	สิทธิมีที่ปรึกษาหรือผู้ทำการแทน (มาตรา 23, 24)<br>
                            •	สิทธิที่ได้รับการพิจารณาจากเจ้าหน้าที่ซึ่งมีความเป็นกลาง (มาตรา 13, 14, 16)<br>
                            •	สิทธิที่จะได้รับคำแนะนำและได้รับแจ้งสิทธิหน้าที่ต่างๆ ในการติดต่อเจ้าหน้าที่ (มาตรา 27)<br>
                            •	สิทธิที่จะได้รับการแจ้งจากเจ้าหน้าที่ในกรณีคำสั่งมีผลกระทบต่อตน (มาตรา 30)<br>
                            •	สิทธิที่จะโต้แย้งแสดงพยานหลักฐาน (มาตรา 30)<br>
                            •	สิทธิที่จะได้ตรวจดูเอกสารของเจ้าหน้าที่ (มาตรา 31)<br>
                            •	สิทธิที่จะได้รับทราบเหตุผลของคำสั่ง (มาตรา 37)<br>
                            •	สิทธิที่จะได้รับแจ้งวิธีการอุทธรณ์หรือโต้แย้งและสิทธิในการอุทธรณ์คำสั่ง (มาตรา 49, 44)<br>
                            •	สิทธิในการขอให้พิจารณาใหม่ (มาตรา 54)

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
            <h6 class="mb-0">3. "สิทธิที่จะมีที่ปรึกษาหรือผู้กระทำแทน" ข้อใดไม่ถูกต้อง</h6>

          </template>
          <b-card-text>ก. ทนายความ.</b-card-text>
          <b-card-text>ข. วิศวกร  .</b-card-text>
          <b-card-text>ค. ผู้เชี่ยวชาญ .</b-card-text>
          <b-card-text>ง. เจ้าหน้าที่รัฐ .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ง. เจ้าหน้าที่รัฐ <br>
              <b>อธิบาย :</b> สิทธิที่จะมีที่ปรึกษาหรือผู้กระทำแทน ตามมาตรา 23,24<br>
                            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ในการติดต่อกับเจ้าหน้าที่เพื่อขอออกใบอนุญาตหรือใบรับรอง ท่านอาจไม่มีความรู้ในรายละเอียด และต้องมีผู้เชี่ยวชาญเป็นที่ปรึกษากฎหมาย จึงให้ท่านมีสิทธิที่จะนำบุคคลอื่นที่มีความรู้ในเรื่องนั้นๆ เช่น ทนายความ วิศวกร นักบัญชี เภสัชกร หรือผู้เชี่ยวชาญอื่นๆ มาพร้อมกับท่าน เพื่อให้คำแนะนำหรือช่วยชี้แจงต่อเจ้าหน้าที่ได้ รวมถึงท่านมีสิทธิมอบหมายให้ผู้อื่นดำเนินการแทนท่านได้
            </em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">4. หากท่านไม่พอใจในคำสั่ง ท่านสามารถยื่นอุทธรณ์โต้แย้งคำสั่งได้ภายในกี่วัน นับแต่วันที่ได้รับแจ้งคำสั่ง</h6>

          </template>
          <b-card-text>ก. 7 วัน.</b-card-text>
          <b-card-text>ข. 15 วัน .</b-card-text>
          <b-card-text>ค. 20 วัน  .</b-card-text>
          <b-card-text>ง. 30 วัน .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ข. 15 วัน
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
            <h6 class="mb-0">5. คู่กรณี หมายถึงข้อใด</h6>

          </template>
          <b-card-text>ก. เอกชนผู้เกี่ยวข้องในกระบวนการพิจารณา เพื่อออกคำสั่งทางปกครอง.</b-card-text>
          <b-card-text>ข. ผู้กระทำผิดที่เข้าสู่กระบวนการพิจารณาคดี  .</b-card-text>
          <b-card-text>ค. ผู้เกี่ยวข้องในการพิจารณาคดี ที่มีส่วนขัดแย้งกับภาครัฐ .</b-card-text>
          <b-card-text>ง. เอกชนผู้เกี่ยวข้องที่มีอุทธรณ์ความขัดแย้งเข้าสู่พิจารณา .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก. เอกชนผู้เกี่ยวข้องในกระบวนการพิจารณา เพื่อออกคำสั่งทางปกครอง <br>
              <b>อธิบาย :</b> -</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">6. ข้อใดกล่าวไม่ถูกต้องในการพิจารณาออกคำสั่งทางปกครอง</h6>

          </template>
          <b-card-text>ก. ภาษาที่ใช้ในการพิจารณา เอกสารที่ยื่นต่อเจ้าหน้าที่ สามารถใช้ภาษาไทย หรือภาษาต่างประเทศได้ .</b-card-text>
          <b-card-text>ข. คู่กรณีมีสิทธิโต้แย้งข้อเท็จจริงในกระบวนการพิจารณา  .</b-card-text>
          <b-card-text>ค. หากข้อเท็จจริงของคู่กรณีไม่เพียงพอ เจ้าหน้าที่มีสิทธิยุติการพิจาณา  .</b-card-text>
          <b-card-text>ง. เจ้าหน้าที่ต้องแจ้งสิทธิและหน้าที่ต่างๆ อย่างชัดเจนให้แก่คู่กรณี.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค. หากข้อเท็จจริงของคู่กรณีไม่เพียงพอ เจ้าหน้าที่มีสิทธิยุติการพิจาณา
            <br><b>อธิบาย</b> หลักการพิจารณาแบบไต่สวน เจ้าหน้าที่มีหน้าที่ตรวจสอบข้อเท็จจริง ดังนั้น ถ้าข้อเท็จจริงที่ได้มาจากคู่กรณีไม่เพียงพอ ก็จะต้องมีการตรวจสอบโดยแสวงหาพยานหลักฐานเพิ่มเติม หรือฟังความเห็นของผู้เชี่ยวชาญตามมาตรา 29
            </em>
           </template>
        </b-card>
        </b-card-group>
        <!-- 9 -->
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">7.ข้อใดไม่ใช่รูปแบบคำสั่งทางปกครอง</h6>

          </template>
          <b-card-text>ก. คำสั่งด้วยวาจา .</b-card-text>
          <b-card-text>ข. คำสั่งเป็นหนังสือ  .</b-card-text>
          <b-card-text>ค. คำสั่งอิเล็กทรอนิกส์ .</b-card-text>
          <b-card-text>ง. คำสั่งโดยวิธีอื่น.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค. คำสั่งอิเล็กทรอนิกส์ <br>
              <b>อธิบาย :</b> - </em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">8. คู่กรณีสามารถยื่นขอให้พิจารณาใหม่ภายในกี่วัน</h6>

          </template>
          <b-card-text>ก. 30 วัน .</b-card-text>
          <b-card-text>ข. 50 วัน  .</b-card-text>
          <b-card-text>ค. 60 วัน  .</b-card-text>
          <b-card-text>ง. 90 วัน .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ง. 90 วัน
            <br><b>อธิบาย</b> คำขอให้พิจารณาใหม่ คู่กรณีต้องยื่นภายใน 90 วัน นับแต่ได้รู้ถึงเหตุซึ่งอาจขอให้มีการพิจารณาใหม่ได้ (มาตรา 54 วรรค 3)
            </em>
           </template>
        </b-card>
        </b-card-group>
        <!-- 10 -->
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">9. ข้อใดไม่ใช่หลักการที่สำคัญของการบังคับทางปกครอง</h6>

          </template>
          <b-card-text>ก. ความถูกต้อง.</b-card-text>
          <b-card-text>ข. ความสมเหตุสมผล  .</b-card-text>
          <b-card-text>ค. หลักการบังคับทางปกครองเท่าที่จำเป็น  .</b-card-text>
          <b-card-text>ง. ความแน่นอนและความชัดเจน.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก. ความถูกต้อง <br>
              <b>อธิบาย :</b> -</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">10.  ข้อใดไม่ใช่มาตรการบังคับ ทางปกครองกรณีคำสั่งทางปกครองที่กำหนดให้ชำระเงิน</h6>

          </template>
          <b-card-text>ก. การยึด.</b-card-text>
          <b-card-text>ข. การปรับ  .</b-card-text>
          <b-card-text>ค. การอายัด  .</b-card-text>
          <b-card-text>ง. การขายทอดตลาด.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ข. การปรับ
            <br><b>อธิบาย</b> -
            </em>
           </template>
        </b-card>
        </b-card-group> 
        <!-- 11 -->
        <br><h4 class="mt-4">-	ระเบียบบริหารราชการแผ่นดิน</h4><br>
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">1. การจัดระเบียบบริหารราชการแบ่งได้กี่ประเภท</h6>

          </template>
          <b-card-text>ก. 2 ประเภท คือ ส่วนกลาง และส่วนภูมิภาค.</b-card-text>
          <b-card-text>ข. 2 ประเภท คือ ส่วนกลาง และส่วนท้องถิ่น  .</b-card-text>
          <b-card-text>ค. 3 ประเภท คือ ส่วนกลาง ส่วนภูมิภาค และส่วนท้องถิ่น  .</b-card-text>
          <b-card-text>ง. 3 ประเภท คือ ส่วนกลาง ส่วนภูมิภาค และส่วนพิเศษ .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค. 3 ประเภท คือ ส่วนกลาง ส่วนภูมิภาค และส่วนท้องถิ่น <br>
              <b>อธิบาย :</b> -</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">2. ข้อใดไม่ใช่จุดประสงค์ของการบริหารราชการแผ่นดิน ตามมาตรา 3/1</h6>

          </template>
          <b-card-text>ก. เพื่อประโยชน์สุข .</b-card-text>
          <b-card-text>ข. เกิดความสงบสุข  .</b-card-text>
          <b-card-text>ค. อำนวยความสะดวก   .</b-card-text>
          <b-card-text>ง. การกระจายภารกิจ.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ข. เกิดความสงบสุข
            <br><b>อธิบาย</b> -
            </em>
           </template>
        </b-card>
        </b-card-group>
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">3. การเปลี่ยนชื่อกระทรวง กำหนดให้ตราขึ้นเป็นอะไร</h6>

          </template>
          <b-card-text>ก. พระราชบัญญัติ.</b-card-text>
          <b-card-text>ข. พระบรมราชโองการ .</b-card-text>
          <b-card-text>ค. พระราชกำหนด .</b-card-text>
          <b-card-text>ง. พระราชกฤษฎีกา .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ง. พระราชกฤษฎีกา <br>
              <b>อธิบาย :</b> ตามมาตรา 8 ตรีการเปลี่ยนชื่อกระทรวง ทบวง กรม ส่วนราชการ ให้ตราเป็นพระราชกฤษฎีกา</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">4. ฐานะของสำนักนายกรัฐมนตรี คืออะไร</h6>

          </template>
          <b-card-text>ก. กระทรวง .</b-card-text>
          <b-card-text>ข. ทบวง  .</b-card-text>
          <b-card-text>ค. กรม   .</b-card-text>
          <b-card-text>ง. สำนักงาน .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก. กระทรวง
            <br><b>อธิบาย</b> ตามมาตรา 7 สำนักนายกรัฐมนตรี มีฐานะเป็น กระทรวง
            </em>
           </template>
        </b-card>
        </b-card-group>
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">5. ผู้บังคับบัญชาของสำนักเลขาธิการนายกรัฐมนตรี คือใคร</h6>

          </template>
          <b-card-text>ก. นายกรัฐมนตรี .</b-card-text>
          <b-card-text>ข. เลขาธิการนายกรัฐมนตรี .</b-card-text>
          <b-card-text>ค. คณะรัฐมนตรี  .</b-card-text>
          <b-card-text>ง. รองนายกรัฐมนตรี .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ข. เลขาธิการนายกรัฐมนตรี <br>
              <b>อธิบาย :</b> ตามมาตรา 13 ผู้บังคับบัญชาของสำนักเลขาธิการนายกรัฐมนตรี คือ เลขาธิการนายกรัฐมนตรี</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">6. การแบ่งเขตและการปกครองบังคับบัญชาของตำรวจให้กำหนดโดยใช้สิ่งใด</h6>

          </template>
          <b-card-text>ก. พระราชกฤษฎีกา.</b-card-text>
          <b-card-text>ข. พระราชบัญญัติ  .</b-card-text>
          <b-card-text>ค. พระราชกำหนด   .</b-card-text>
          <b-card-text>ง. คำสั่งสำนักนายกรัฐมนตรี .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก. พระราชกฤษฎีกา
            <br><b>อธิบาย</b> -
            </em>
           </template>
        </b-card>
        </b-card-group>
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">7. ข้อใครหมายถึงการจัดระเบียบบริหารราชการส่วนภูมิภาค</h6>

          </template>
          <b-card-text>ก. จังหวัด.</b-card-text>
          <b-card-text>ข. ตำบล .</b-card-text>
          <b-card-text>ค. เทศบาล .</b-card-text>
          <b-card-text>ง. ท้องถิ่น .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก. จังหวัด <br>
              <b>อธิบาย :</b> -</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">8. ผู้บังคับบัญชาสูงสุดของกรมคือใคร</h6>

          </template>
          <b-card-text>ก. รัฐมนตรีว่าการทบวง .</b-card-text>
          <b-card-text>ข. รองอธิบดี .</b-card-text>
          <b-card-text>ค. รัฐมนตรีว่าการกรม  .</b-card-text>
          <b-card-text>ง. อธิบดี .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ง. อธิบดี
            <br><b>อธิบาย</b> -
            </em>
           </template>
        </b-card>
        </b-card-group>
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">9. การปกครองแบบพิเศษ เช่น กรุงเทพมหานคร เมืองพัทยา จัดเป็นการจัดระเบียบบริหารราชการในส่วนใด</h6>

          </template>
          <b-card-text>ก. ส่วนกลาง.</b-card-text>
          <b-card-text>ข. ส่วนภูมิภาค .</b-card-text>
          <b-card-text>ค. ส่วนท้องถิ่น .</b-card-text>
          <b-card-text>ง. ส่วนพิเศษ .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค. ส่วนท้องถิ่น <br>
              <b>อธิบาย :</b> การบริหารราชการส่วนท้องถิ่น คือ การปกครองในส่วน อบต. เทศบาล อบจ. รวมถึงการปกครองแบบพิเศษ กรุงเทพมหานคร และพัทยา</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">10. การจัดระเบียบบริหาราชการส่วนภูมิภาค ใช้หลักการใดในการบริหาร</h6>

          </template>
          <b-card-text>ก. กระจายอำนาจ.</b-card-text>
          <b-card-text>ข. รวมอำนาจ  .</b-card-text>
          <b-card-text>ค. กระจายอำนาจ  .</b-card-text>
          <b-card-text>ง. ถูกทุกข้อ .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค. สภานิติบัญญัติแห่งชาติ
            <br><b>อธิบาย</b> พระราชบัญญัติระเบียบข้าราชการพลเรือน พ.ศ. 2551 ตราขึ้นโดยคำแนะนำและยินยอมของ สภานิติบัญญัติแห่งชาติ
            </em>
           </template>
        </b-card>
        </b-card-group>
        <div class="container-fluid">
          <h1 class="mt-4">วิชาความรู้ความสามารถทั่วไป และภาษาไทย</h1>
        </div>
        <br><h4 class="mt-4">-	อุปมาอุปไมย</h4><br>
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">1. ยะลา : เบตง </h6>

          </template>
          <b-card-text>ก. เชียงใหม่ : ดอยสุเทพ.</b-card-text>
          <b-card-text>ข. แม่ฮ่องสอน : แม่สะเรียง .</b-card-text>
          <b-card-text>ค. เชียงราย : แม่สาย .</b-card-text>
          <b-card-text>ง. เชียงใหม่ : สันป่าตอง.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค. เชียงราย : แม่สาย <br>
              <b>แนวคิด :</b> เป็นความสัมพันธ์ในเรื่องของการจับคู่อําเภอเหนือสุดและใต้สุดของประเทศไทย และพื้นที่ตั้ง จากโจทย์ อําเภอเบตง เป็นอําเภอสุดท้ายที่อยู่ในจังหวัดยะลา ถือเป็นจุดที่อยู่ใต้สุดซึ่ง ข้อ ค. เชียงราย : แม่สาย เป็นคําตอบที่ถูกที่สุด เพราะอําเภอแม่สายคืออําเภอที่เหนือสุดของประเทศไทย อยู่ในจังหวัดเชียงราย</em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">2. วัณโรค : อหิวาตกโรค</h6>

          </template>
          <b-card-text>ก. เบาหวาน : ไต.</b-card-text>
          <b-card-text>ข. ไขข้อเสื่อม : หอบหืด .</b-card-text>
          <b-card-text>ค. ภูมิแพ้ : ความดันโลหิตสูง   .</b-card-text>
          <b-card-text>ง. พิษสุนัขบ้า : ไข้เลือดออก.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ง. พิษสุนัขบ้า : ไข้เลือดออก
            <br><b>แนวคิด</b> เป็นความสัมพันธ์ในเรื่องของโรคติดต่อ ซึ่งจากโจทย์ เป็นชื่อโรคที่เป็นโรคติดต่อ เช่นเดียวกับข้อ ง. ทั้งสองคําเป็นโรคติดต่อ<br>
                            สําหรับ <br>	ข้อ ก. เบาหวานและไต เป็นโรคไม่ติดต่อ
        	 	                       <br> ข้อ ข. ไขข้อเสื่อมและหอบหืด เป็นโรคไม่ติดต่อ
                                    <br>ข้อ ค. ภูมิแพ้และความดันโลหิตสูง เป็นโรคไม่ติดต่อ

            </em>
           </template>
        </b-card>
        </b-card-group>
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">3.  ครู : นักบัญชี        </h6>

          </template>
          <b-card-text>ก. สอนหนังสือ : การเงิน.</b-card-text>
          <b-card-text>ข. หมอ : สถาปนิก .</b-card-text>
          <b-card-text>ค. อาคาร : บริหาร  .</b-card-text>
          <b-card-text>ง. ให้ความรู้ : ออกแบบ.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก. สอนหนังสือ : การเงิน<br>
              <b>แนวคิด :</b> เป็นลักษณะความสัมพันธ์ในเรื่องของอาชีพกับลักษณะงานที่ทํา หรือเกี่ยวข้อง
              </em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">4. ฤดูฝน : เข้าพรรษา          </h6>

          </template>
          <b-card-text>ก. ฤดูร้อน : เมษายน .</b-card-text>
          <b-card-text>ข. ฤดูร้อน : สงกรานต์.</b-card-text>
          <b-card-text>ค. ฤดูหนาว : ธันวาคม    .</b-card-text>
          <b-card-text>ง. ลอยกระทง : พฤศจิกายน .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ข. ฤดูร้อน : สงกรานต์
            <br><b>แนวคิด</b> เป็นความสัมพันธ์เกี่ยวกับฤดูกาลและช่วงวันสําคัญ ซึ่ง ฤดูฝน จะตรงกับช่วงวันเข้าพรรษา เช่นเดียวกับ ฤดูร้อน จะตรงกับวันสงกรานต์
            </em>
           </template>
        </b-card>
        </b-card-group>
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">5. ล้ม : สะดุด           </h6>

          </template>
          <b-card-text>ก. ดักแด้ : ผีเสื้อ.</b-card-text>
          <b-card-text>ข. เคี้ยว : กลืน .</b-card-text>
          <b-card-text>ค. สุก : งอม  .</b-card-text>
          <b-card-text>ง. แต่ง : หมั้น .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ง. แต่ง : หมั้น <br>
              <b>แนวคิด :</b> เป็นความสัมพันธ์แบบ คํา หลังไปคําหน้า สะดุดก่อน แล้วถึงล้ม เช่นเดียวกับข้อ ง. มีพิธีหมั้นก่อน ถึงจะแต่งงาน<br>
                <br>สําหรับ <br>	ข้อ ก., ข.และ ข้อ ค. เป็นความสัมพันธ์แบบ คําหน้าไปคําหลัง
                <br>ข้อ ก. ดักแด้ แล้วเปลี่ยนเป็นผีเสื้อ
                <br>ข้อ ข.เคี้ยวแล้วจึงกลืน
                <br>ข้อ ค. สุก เมื่อสุกมากขึ้นจะกลายเป็นงอม

              </em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">6. วิตามิน : ผลไม้       </h6>

          </template>
          <b-card-text>ก. คาร์โบไฮเดรต : ข้าว .</b-card-text>
          <b-card-text>ข. ผักใบเขียว : วิตามิน .</b-card-text>
          <b-card-text>ค. โปรตีน : เกลือแร่    .</b-card-text>
          <b-card-text>ง. แป้ง : โปรตีน.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก. คาร์โบไฮเดรต : ข้าว
            <br><b>แนวคิด</b> เป็นความสัมพันธ์ในเรื่องของแหล่งที่มาในที่นี้ คือแหล่งที่มาของสารอาหาร
                  จากโจทย์ วิตามิน มีแหล่งที่มาจากผลไม้ เช่นเดียวกับ คาร์โบไฮเดรต มีแหล่งที่มา คือ ข้าว

            </em>
           </template>
        </b-card>
        </b-card-group>
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">7. เฮโรอีน : ยาเสพติด           </h6>

          </template>
          <b-card-text>ก. บุหรี่ : มะเร็ง.</b-card-text>
          <b-card-text>ข. เฟิร์น : ผักตบชวา  .</b-card-text>
          <b-card-text>ค. โปรตีน : ไก่  .</b-card-text>
          <b-card-text>ง. ยาฆ่าแมลง : สารเคมี .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ง. ยาฆ่าแมลง : สารเคมี <br>
              <b>แนวคิด :</b> เป็นความสัมพันธ์ในเรื่องการเป็นส่วนหนึ่งของสิ่งนั้นๆ
              </em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">8. แมงป่อง : หาง           </h6>

          </template>
          <b-card-text>ก. สิงโต : ขา .</b-card-text>
          <b-card-text>ข. นก : ปีก  .</b-card-text>
          <b-card-text>ค. ปู : ก้าม  .</b-card-text>
          <b-card-text>ง. ปลา : ครีบ.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค. ปู : ก้าม
            <br><b>แนวคิด</b> เป็นความสัมพันธ์เกี่ยวกับอวัยวะที่ใช้ป้องกันตัวของสัตว์ ซึ่งจากโจทย์ แมงป่องจะใช้หางในการต่อสู้และป้องกันตัว เช่นเดียวกับ ปู จะใช้ก้ามในการป้องกันตัว
            </em>
           </template>
        </b-card>
        </b-card-group>
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">9. กลางคืน : สว่าง    </h6>

          </template>
          <b-card-text>ก. มืด : สีดํา .</b-card-text>
          <b-card-text>ข. กลางวัน : สีดํา  .</b-card-text>
          <b-card-text>ค. กลางวัน : มืด  .</b-card-text>
          <b-card-text>ง. สว่าง : มืด .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค. กลางวัน : มืด <br>
              <b>แนวคิด :</b> เป็นความสัมพันธ์ในเรื่องของคําตรงข้ามกัน
              </em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">10. กรรไกร : เกวียน     </h6>

          </template>
          <b-card-text>ก. กระดาษ : มีด .</b-card-text>
          <b-card-text>ข. ช้าง : บ้าน  .</b-card-text>
          <b-card-text>ค. ม้า : ขลุ่ย    .</b-card-text>
          <b-card-text>ง. หนังสือ : เข็ม .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ง. หนังสือ : เข็ม
            <br><b>แนวคิด</b> เป็นความสัมพันธ์ในลักษณะของการใช้ลักษณนามที่เหมือนกัน
                    จากโจทย์ กรรไกร และ เกวียน มีลักษณนาม คือ เล่ม เช่นเดียวกับ หนังสือ และ เข็ม ที่ใช้ลักษณนามเหมือนกัน คือ เล่ม<br>
                    สําหรับ<br>	ข้อ ก. กระดาษ (แผ่น) : มีด (เล่ม)
                    <br>ข้อ ข. ช้าง (เชือก) : บ้าน (หลัง)
                    <br>ข้อ ค. ม้า (ตัว) : ขลุ่ย (เลา)

            </em>
           </template>
        </b-card>
        </b-card-group>
        <br><h4 class="mt-4">-	การเรียงข้อความ</h4><br>
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">1. ข้อใดเป็นลำดับที่ 2 </h6>

          </template>
          <b-card-text>ก. การที่หน่วยงาน หลายๆหน่วยงาน .</b-card-text>
          <b-card-text>ข. มีการปฏิบัติงานที่คล้ายๆกัน  .</b-card-text>
          <b-card-text>ค. โดยมุ่งเน้นการทํางานร่วมกันเพื่อประโยชน์ต่อองค์กร.</b-card-text>
          <b-card-text>ง. ในองค์กรทั้งภาครัฐและเอกชน.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ง. ในองค์กรทั้งภาครัฐและเอกชน <br>
              <b>คำอธิบาย :</b> จากคำถามที่กำหนดให้ สามารถเรียงลำดับได้ดังนี้     ก - ง - ข – ค
              </em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">2. ข้อใดเป็นลำดับที่ 3</h6>

          </template>
          <b-card-text>ก. ประเทศสมาชิกภาคีทุกประเทศ.</b-card-text>
          <b-card-text>ข. เพื่อต้องการเปิดโอกาสให้เกิดการลงทุน.</b-card-text>
          <b-card-text>ค. ทั้งการลงทุนแบบระยะสั้นและระยะยาว   .</b-card-text>
          <b-card-text>ง. ได้มีนโยบายเกี่ยวกับเศรษฐกิจ.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ข. เพื่อต้องการเปิดโอกาสให้เกิดการลงทุน
            <br><b>คำอธิบาย</b> จากคำถามที่กำหนดให้ สามารถเรียงลำดับได้ดังนี้  ก - ง - ข - ค
            </em>
           </template>
        </b-card>
        </b-card-group>
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">3. ข้อใดเป็นลำดับที่ 2 </h6>

          </template>
          <b-card-text>ก. ในการเรียนรู้ มากกว่าประเทศที่กําลังพัฒนากว่า 6 เท่า.</b-card-text>
          <b-card-text>ข. การศึกษาของประเทศที่พัฒนาแล้ว มีศักยภาพและความพร้อม .</b-card-text>
          <b-card-text>ค. จากผลการสอบ Pisa เท่ากับว่าเด็กชั้นประถม 3 ในกลุ่มประเทศที่พัฒนาแล้ว เช่น ฟินแลนด์ สิงคโปร์ ญี่ปุ่น  .</b-card-text>
          <b-card-text>ง. มีระดับสติปัญญาเท่ากับเด็กมัธยมศึกษาปีที่ 3 ของไทย .</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก. ในการเรียนรู้ มากกว่าประเทศที่กําลังพัฒนากว่า 6 เท่า <br>
              <b>คำอธิบาย :</b> จากคำถามที่กำหนดให้ สามารถเรียงลำดับได้ดังนี้   ข - ก - ค – ง
              </em>
           </template>
        </b-card>  

          

        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">4. ข้อใดเป็นลำดับที่ 3</h6>

          </template>
          <b-card-text>ก. และไม่เตือนลูกว่ากําลังต้องเจอกับความร้ายแรงใดบ้าง.</b-card-text>
          <b-card-text>ข. ประเทศไทยกําลังเข้าสู่ “สังคมอิ่มตัว” .</b-card-text>
          <b-card-text>ค. ในขณะที่ต่างประเทศพ่อแม่จะสอนให้ลูกเอาตัวรอด  .</b-card-text>
          <b-card-text>ง. ด้วยการเลี้ยงดูของพ่อแม่ที่สร้างเกราะคุ้มกัน.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ก. และไม่เตือนลูกว่ากําลังต้องเจอกับความร้ายแรงใดบ้าง
            <br><b>คำอธิบาย</b> จากคำถามที่กำหนดให้ สามารถเรียงลำดับได้ดังนี้  ข - ง - ก - ค
            </em>
           </template>
        </b-card>
        </b-card-group>
        <br>
        <b-card-group deck>
        <b-card  header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">5. ข้อใดเป็นลำดับที่ 4</h6>

          </template>
          <b-card-text>ก. ที่น่าสนใจคือภายในปี 2045 ที่จะถึง AI จะมีความฉลาดเท่ามนุษย์ .</b-card-text>
          <b-card-text>ข. ในปัจจุบัน AI ฉลาดเท่ากับเด็กอายุ 6 ขวบ .</b-card-text>
          <b-card-text>ค. นั้นแปลว่า ไม่มีทางที่มนุษย์จะแข่งขันได้ชนะ ในเรื่องความถูกต้อง  .</b-card-text>
          <b-card-text>ง. แต่ที่ AI ชนะมนุษย์ได้นั้น เนื่องจาก AI คิดได้เร็วกว่ามนุษย์ถึง 30,000 เท่า.</b-card-text>

          <template v-slot:footer>
            <em><b>ตอบ</b> ค. นั้นแปลว่า ไม่มีทางที่มนุษย์จะแข่งขันได้ชนะ ในเรื่องความถูกต้อง>
              <b>คำอธิบาย :</b> จากคำถามที่กำหนดให้ สามารถเรียงลำดับได้ดังนี้   ข - ง - ก – ค
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