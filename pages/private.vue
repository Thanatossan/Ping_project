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
      <!-- ลักษณะของงาน HR -->
      <div class="container-fluid">
        <center>
          <h1 class="mt-4">ลักษณะของงาน HR</h1>
        </center>
      </div>
      <div class="container">
        <p
          class="pt-5"
          id="HR1"
        >งาน HR ในปัจจุบัน มีความสำคัญต่อองค์กรมากขึ้นกว่าในอดีต เพราะปัจจุบันทรัพยากรบุคคลถือเป็นสิ่งที่มีค่าที่สุดขององค์กร HR จึงเปรียบเสมือนหุ้นส่วนทางธุรกิจ ซึ่งมีลักษณะและวิธีการดำเนินการ ดังต่อไปนี้</p>
      </div>
      <div class="container">
        <h3
          class="pt-3"
          id="HR2"
        >1. งานวางแผนกำลังคน / กลยุทธ์ / การบริหารบุคคล (HR planning)</h3>
        <p class="pt-2">คาดการณ์ความต้องการและวางแผนใช้ทรัพยากรมนุษย์ขององค์การไว้ล่วงหน้า ว่าต้องการบุคคลที่มีคุณสมบัติอย่างไร ระดับใด จำนวนเท่าใด เมื่อใด ด้วยวิธีการใด ต้องพัฒนาบุคคลให้มีความรู้ความสามารถอย่างไร จะควบคุมจำนวนทรัพยากรมนุษย์ในองค์การให้มีความเหมาะสมสอดคล้องกับการดำเนินงานขององค์การได้อย่างไร ตลอดจนการกำหนดนโยบายและระเบียบปฏิบัติต่าง ๆ เพื่อจะใช้ทรัพยากรบุคคลที่มีอยู่ให้เกิดประโยชน์สูงสุด</p>
      </div>
      <div class="container">
        <h3
          class="pt-3"
          id="HR3"
        >2. งานพัฒนาบุคลากร (Training & Development)</h3>
        <p class="pt-2">พัฒนาพนักงานให้มีความรู้ ทักษะ ประสบการณ์ และทัศนคติที่ดีขึ้น สามารถที่จะปฏิบัติหน้าที่ที่ยากขึ้นและมีความรับผิดชอบที่สูงขึ้นได้ โดยใช้วิธีการต่าง ๆ เช่น ฝึกอบรม ฝึกปฏิบัติการ ศึกษาดูงาน การสอนงาน (Job Instruction) การสอนแนะ (Coaching) การให้คำปรึกษา (Counselling) การมอบหมายหน้าที่ให้ทำเป็นครั้งคราว (Job Assignment) การให้รักษาการแทน (Acting) การโยกย้ายสับเปลี่ยนหน้าที่การงานเพื่อให้โอกาสศึกษางานที่แปลกใหม่ หรือการได้มีโอกาสศึกษาหาความรู้ และประสบการณ์จากหน่วยงานอื่น (Job Rotation) เป็นต้น</p>
      </div>
      <div class="container">
        <h3 class="pt-3">3. งานสรรหาและคัดสรรบุคลากร (Recruitment, Selection & Introduction)</h3>
        <p class="pt-2">วิเคราะห์หาความต้องการของงาน ว่าต้องการคนที่มีคุณสมบัติอย่างไร ลงประกาศรับสมัครงาน คัดกรองผู้สมัครเบื้องต้น นัดหมายสัมภาษณ์งาน ทดสอบด้วยเครื่องมือวิธีการต่าง ๆ ตรวจสอบบุคคลอ้างอิง เช็คประวัติย้อนหลัง กลั่นกรองผู้สมัครที่เข้าตาคัดเลือก แจ้งผลการสัมภาษณ์ ยื่นข้อเสนอจ้างงาน รับเข้าทำงาน ปฐมนิเทศพนักงาน และติดตามความคืบหน้าหลังรับเข้าทำงาน</p>
      </div>
      <!-- คุณสมบัติ ที่HR พึงมี -->
      <div
        class="container-fluid"
        id="HR4"
      >
        <br><br><br>
        <center>
          <h1 id="HR5">คุณสมบัติที่HRพึงมี</h1>
        </center>
      </div>
      <div class="container">
        <h3
          class="pt-4"
          id="HR6"
        >1. Critical & Enquiring Thinker :</h3>
        <p class="pt-1">ต้องเป็นคนที่ช่างวิเคราะห์วิจารณ์ เป็นนักคิด เพื่อจะได้หาข้อสรุปที่ดีที่สุด</p>
      </div>
      <div class="container">
        <h3
          class="pt-2"
          id="HR7"
        >2. Solution Driven :</h3>
        <p class="pt-1">คิดแล้วต้องชักจูงให้ได้บทสรุปให้ได้ ไม่ควรปล่อยให้พูดเพ้อเจ้อไป หาเนื้อหาไม่ได้</p>
      </div>
      <div class="container">
        <h3
          class="pt-2"
          id="HR8"
        >3. Courageous :</h3>
        <p class="pt-1">ต้องใจกล้า แม้ไม่เคยทำแต่ก็ต้องกล้าทำ หากมัวแต่แหยงก็จะทำไม่ได้</p>
      </div>
      <div class="container">
        <h3
          class="pt-2"
          id="HR9"
        >4. Collaboration :</h3>
        <p class="pt-1">เก่งเรื่องการร่วมมือ การประสานงาน ไม่ใช่ประสานธรรมดา ต้องเป็นนักประสานสิบทิศ เพราะเราต้องการเปลี่ยนทั้งองค์กร ไม่ใช่แค่จุดใดจุดหนึ่ง ต้องพร้อมยกมือไหว้แม้ใจจะไม่อยากไหว้ แต่เราทำเพื่องาน</p>
      </div>
      <div class="container">
        <h3
          class="pt-2"
          id="HR10"
        >5. Understand : </h3>
        <p class="pt-1">เป็นสิ่งที่ HR ต้องมีต้องทำอยู่แล้ว ทำงานกับคนแล้วไม่เข้าใจคนได้อย่างไร นอกจากนี้ต้องเข้าใจงานด้วย อย่ารู้แค่เรื่องงานของเรา เราต้อง Knowing the Business</p>
      </div>
      <div class="container">
        <h3
          class="pt-2"
          id="HR11"
        >6. Resolve Issues : </h3>
        <p class="pt-1">ต้องเป็นนักแก้ปัญหา อย่าปล่อยค้างคาไว้ เพราะจะเป็นอุปสรรคในการทำงานต่อไป ระดมสมองคนอื่น ฟังคนอื่นด้วยหากคิดเองไม่ออก ปัญหามีไว้แก้ ไม่ได้มีไว้เก็บใต้พรม ตั้งสติ อย่าตกใจ ค่อยๆ คิด สติมาปัญญาเกิดแน่นอน</p>
      </div>
      <div class="container">
        <h3
          class="pt-2"
          id="HR12"
        >7. Credible : </h3>
        <p class="pt-1">ต้องสร้างและสะสมเครดิต ความไว้วางใจ ความน่าเชื่อถือไว้ให้มาก หากเขาเชื่อ เขาไว้ใจ จะทำอะไรย่อมง่าย</p>
      </div>
      <div class="container">
        <h3
          class="pt-2"
          id="HR13"
        >8. Care :</h3>
        <p class="pt-1">คนเรานั้นหากลองได้รับน้ำใจ ความเอาใจใส่ แสดงออกให้เขารู้ว่าเขามีความหมายกับเรา การตอบสนองให้ความร่วมมือย่อมตามมา โดยเฉพาะคนไทย มีสำนึกนี้อยู่ในใจทุกคน</p>
      </div>
      <div class="container">
        <h3
          class="pt-2"
          id="HR14"
        >9. Future Oriented : </h3>
        <p class="pt-1">ต้องมีวิสัยทัศน์ หัดคิดยาวๆ คิดไกล คิดให้ตลอด อย่าเป็นคนสายตาสั้นที่มองอะไรไม่พ้นขอบโต๊ะทำงานตัวเอง แต่ต้องกวาดตาให้รอบ มองให้ทะลุ ถ้าทำอย่างนี้แล้วจะเป็นอย่างไร จะพบปัญหาไหม จะแก้หรือป้องกันปัญหาได้ไหม อย่างไร</p>
      </div>
      <div class="container">
        <h3
          class="pt-2"
          id="HR15"
        >10. Influencer :</h3>
        <p class="pt-1">เป็นผู้มีอิทธิพลทางความคิด สามารถชักจูง ดูดดึงให้คนคล้อยตาม หากคนใดสามารถมีพฤติกรรมข้อนี้ได้ เชื่อได้เลยว่า งานจะราบรื่น บอกอะไรไป ตั้งแต่ CEO ลงมาเห็นด้วย สนับสนุนช่วยผลักดัน แล้วผลสำเร็จจะไปไหนเสีย</p>
      </div>
      <!-- หน่วยงานเอกชนที่น่าสนใจ -->
      <div class="container-fluid">
        <br>
        <center>
          <h1 id="HR16">หน่วยงานเอกชนที่น่าสนใจ</h1>
        </center>
      </div>
      <div class="container">
        <h3 class="pt-4">1.บริษัท ปตท. จำกัด (มหาชน)</h3>
        <p class="pt-1">(อังกฤษ: PTT Public Company Limited, ชื่อย่อ: PTT) เป็นบริษัทด้านพลังงานของไทยที่แปรรูปมาจาก การปิโตรเลียมแห่งประเทศไทย ซึ่งมาจากการรวมกิจการพลังงานของรัฐทั้ง 2 องค์กร คือองค์การเชื้อเพลิงและองค์การก๊าซธรรมชาติแห่งประเทศไทย ประกอบธุรกิจก๊าซธรรมชาติและน้ำมันปิโตรเลียมครบวงจร และธุรกิจปิโตรเคมีที่เน้นการใช้ก๊าซธรรมชาติเป็นหลัก รวมทั้งธุรกิจต่อเนื่อง มีสำนักงานใหญ่ ตั้งอยู่ที่ 555 ถนนวิภาวดีรังสิต แขวงจตุจักร เขตจตุจักร กรุงเทพมหานคร 10900</p>
        <p><b>หน่วยงานต้นสังกัด :</b> กระทรวงพลังงาน</p>
        <p><b>พันธกิจ :</b>ดำเนินธุรกิจด้านพลังงานและปิโตรเคมีอย่างครบวงจรในฐานะเป็นบริษัทพลังงานแห่งชาติ โดยมีพันธกิจในการดูแลผู้มีส่วนได้ส่วนเสียอย่างสมดุล ดังนี้</p>
        <p>&nbsp;&nbsp;&nbsp;<b>1.ต่อประเทศ :</b>&nbsp;สร้างความมั่นคงด้านพลังงานในระยะยาวโดยการจัดหาพลังงานในปริมาณที่เพียงพอมีคุณภาพได้มาตรฐาน และราคาเป็นธรรมเพื่อเสริมสร้างการเติบโตทางเศรษฐกิจ</p>
        <p>&nbsp;&nbsp;&nbsp;<b>2.ต่อสังคมชุมชน :</b>&nbsp;เป็นองค์กรที่ดีของสังคมดำเนินธุรกิจที่มีการบริหารจัดการผลกระทบต่อสิ่งแวดล้อมตามมาตรฐานสากล และ มีส่วนร่วมในการพัฒนาคุณภาพชีวิตที่ดีแก่สังคมชุมชน</p>
        <p>&nbsp;&nbsp;&nbsp;<b>3.ต่อผู้ถือหุ้น :</b>&nbsp;ดำเนินธุรกิจเชิงพาณิชย์ สามารถสร้าง ผลตอบแทนที่ดี และมีการขยายธุรกิจ ให้เติบโตต่อเนื่องอย่างยั่งยืน</p>
        <p>&nbsp;&nbsp;&nbsp;<b>4.ต่อลูกค้า :</b>&nbsp;สร้างความพึงพอใจและความผูกพันแก่ลูกค้าโดยผ่านการนำเสนอผลิตภัณฑ์และบริการที่มีคุณภาพในระดับ มาตรฐานสากลด้วยราคาเป็นธรรม</p>
        <p>&nbsp;&nbsp;&nbsp;<b>5.ต่อคู่ค้า :</b>&nbsp;ดำเนินธุรกิจร่วมกันบนพื้นฐานของความเป็นธรรม มุ่งสร้างความไว้วางใจ ความสัมพันธ์และความร่วมมือที่ดี เพื่อพัฒนาศักยภาพและประสิทธิภาพ ในการดำเนินธุรกิจร่วมกันในระยะยาว</p>
        <p>&nbsp;&nbsp;&nbsp;<b>6.ต่อพนักงาน :</b>&nbsp;สนับสนุนการพัฒนาความสามารถ การทำงานระดับมืออาชีพอย่างต่อเนื่อง ให้ความมั่นใจในคุณภาพชีวิตการทำงาน ของพนักงานทัดเทียมบริษัทชั้นนำ เพื่อสร้างความผูกพันต่อองค์กร</p>
        <p><b>วิสัยทัศน์ :</b>&nbsp;บริษัทพลังงานไทยข้ามชาติชั้นนำ</p>
        <p><b>ผู้บริหาร :</b></p>
        <p>&nbsp;&nbsp;&nbsp;<b>กรรมการผู้จัดการใหญ่ :</b> &nbsp;นายชาญศิลป์ ตรีนุชกร</p>
        <p>&nbsp;&nbsp;&nbsp;<b>รองกรรมการผู้จัดการใหญ่หน่วยธุรกิจก๊าซธรรมชาติ : </b> &nbsp; นายวุฒิกร สติฐิต</p>
        <p>&nbsp;&nbsp;&nbsp;<b>รองกรรมการผู้จัดการใหญ่กลยุทธ์องค์กร : </b> &nbsp;นางอรวดี โพธิสาโร</p>
        <p>&nbsp;&nbsp;&nbsp;<b>รองกรรมการผู้จัดการใหญ่ กำกับดูแลองค์กรและกิจการสัมพันธ์ :</b> &nbsp; นายกฤษณ์ อิ่มแสง</p>
        <p>&nbsp;&nbsp;&nbsp;<b>รองกรรมการผู้จัดการใหญ่บริหารองค์กรและความยั่งยืน :</b> &nbsp; นายปรีชา โภคะธนวัฒน์</p>
        <p>&nbsp;&nbsp;&nbsp;<b>รองกรรมการผู้จัดการใหญ่บริหารกลยุทธ์กลุ่มธุรกิจปิโตรเลียมขั้นปลาย : </b> &nbsp;น.ส.ดวงพร เที่ยงวัฒนธรรม</p>
        <p>&nbsp;&nbsp;&nbsp;<b>รองกรรมการผู้จัดการใหญ่หน่วยธุรกิจการค้าระหว่างประเทศ : </b> &nbsp;นายดิษทัต ปันยารชุน</p>
        <p>&nbsp;&nbsp;&nbsp;<b>รองกรรมการผู้จัดการใหญ่นวัตกรรมและดิจิทัล : </b> &nbsp; นายวรวัฒน์ พิทยศิริ</p>
        <p>&nbsp;&nbsp;&nbsp;<b>รองกรรมการผู้จัดการใหญ่สำนักกฎหมาย : </b> &nbsp;น.ส.เพียงพนอ บุญกล่ำ</p>
        <center><img src="~/assets/private/ppt.jpg"></center>
        <h2
          class="pt-4"
          id="HR17"
        ></h2>
      </div>

      <div class="container">
        <br>
        <h3 class="pt-2">2.SCG</h3>
        <p class="pt-1">ก่อตั้งในประเทศไทยเมื่อปี พ.ศ. 2456 ตามพระบรมราชโองการในพระบาทสมเด็จพระมงกุฏเกล้าเจ้าอยู่หัว รัชกาลที่ 6 เพื่อผลิปูนซีเมนต์ ซึ่งเป็นวัสดุก่อสร้างสำคัญในการพัฒนาประเทศในขณะนั้น และได้ผ่านการเรียนรู้ ปรับตัว พัฒนาองค์กรอย่างต่อเนื่อง จนได้รับการยอมรับเป็นองค์กรต้นแบบชั้นนำในภูมิภาคอาเซียน และพร้อมก้าวสู่การแข่งขันในระดับโลก ปัจจุบันเอสซีจีดำเนินธุรกิจตามแนวทางการพัฒนาอย่างยั่งยืน ภายใต้หลักบรรษัทภิบาลที่ดี มีบริษัทย่อยภายใต้แบรนด์มากกว่า 200 บริษัท สร้างสรรค์และพัฒนานวัตกรรมผลิตภัณฑ์และบริการที่ตอบโจทย์ของผู้บริโภคทั้งในปัจจุบันและอนาคต</p>
        <center>
          <p><b>ประกอบด้วย 3 กลุ่มธุรกิจหลัก</b></p>
        </center>
        <center><img src="~/assets/private/scg1.jpg"></center>
        <center>
          <p>ธุรกิจซีเมนต์และผลิตภัณฑ์&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ธุรกิจก่อสร้างเคมิคอลส์&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ธุรกิจแพคเกจจิ้ง</p>
        </center>
        <p><b>วิสัยทัศน์ :</b>&nbsp;SCGจะเป้นผู้นำตลาดในภูมิภาคอาเซียน ด้วยการสร้างสรรค์นวัตกรรมสินค้า บริการ และโชลูชั่นที่ตอบโจทย์ความต้องการที่หลากหลายของลูกค้า พร้อมมุ่งมัั่นขับเคลื่อนธุรกิจให้เติบโตอย่างยั่งยืน ตามแนวคิดเศรษฐกิจหมุนเวียน (Circular Economy) สร้างความเจริญก้าวหน้าในทุกสังคมและชุมชนที่เข้าไปดำเนินงาน ภายใต้คำมั่นสัญญ “Passion for Better”</p>
        <p><b>โครงสร้างองค์กร :</b></P>
        <center><img src="~/assets/private/scg2.gif"></center><br>
        <h2
          class="pt-4"
          id="HR18"
        ></h2>
      </div>

      <div class="container">
        <br>
        <h3 class="pt-2">3.เครือเจริญโภคภัณฑ์ </h3>
        <p class="pt-1">มีบริษัท เครือเจริญโภคภัณฑ์ จำกัด เป็นบริษัทแม่ ดำเนินกิจกรรมในลักษณะบริษัท Holding Company ถือหุ้นบริษัทในเครือฯ ทั้งในและต่างประเทศ ซึ่งมีการดำเนินธุรกิจที่หลากหลาย ทั้งอุตสาหกรรมการผลิตและการบริการ โดยสามารถแบ่งประเภท ธุรกิจออกเป็น 8 สายธุรกิจหลัก ครอบคลุม 13 กลุ่มธุรกิจย่อย ปัจจุบัน มีการลงทุนอยู่ใน 21 ประเทศและเขตเศรษฐกิจ</p>
        <p><b>วิสัยทัศน์ :</b>“เรามุ่งมั่นในการสร้างอาหารคน อาหารสมอง โอกาสในการเข้าถึงคุณค่าเพื่อสุขภาพ และความเป็นอยู่ที่ดีสำหรับทุกคน”</P>
        <p><b>ค่านิยมองค์กร 6 ประการ :</b></p>
        <p>นับเป็นเวลาเกือบหนึ่งศตวรรษที่เครือเจริญโภคภัณฑ์ได้รับความไว้วางใจจากสังคมไทยและสังคมโลกและเครือฯ ยังคงมุ่งมั่นพัฒนาต่อไปอย่างไม่หยุดยั้งเพื่อนำความผาสุก คุณภาพชีวิตที่ดีสู่ประชาชน สร้างสรรค์ และพัฒนาเศรษฐกิจ สังคม และสิ่งแวดล้อม ให้เติบโตอย่างยั่งยืน</p>
        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ต้นไม้ใหญ่ตั้งตระหง่านอยู่ได้ต้องมีรากแก้วที่มั่นคงเช่นเดียวกับธุรกิจของเครือเจริญโภคภัณฑ์ที่ก้าวหน้า และเติบโตอย่างยั่งยืน เพราะตั้งมั่นอยู่บนค่านิยมองค์กรที่ถ่ายทอดกันมาจากรุ่นสู่รุ่น เป็นจิตวิญญาณที่มุ่งมั่นพัฒนา ต่อยอดความสามารถในการบริหารธุรกิจบนฐานของคุณธรรม จริยธรรม ภายใต้ค่านิยมองค์กร 6 ประการ</p>
        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. สามประโยชน์ (3 Benefits)</p>
        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. ทำเร็วและมีคุณภาพ (Speed & Quality)</p>
        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. ทำเรื่องยากเป็นเรื่องง่าย (Simplification)</p>
        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4. ยอมรับการเปลี่ยนแปลง (Accept change)</p>
        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5. สร้างสรรค์สิ่งใหม่ (Innovativeness)</p>
        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6. ซื่อสัตย์และมีคุณธรรม (Integrity & Honesty)</p>
        <center><img src="~/assets/private/cp.jpg"></center>
        <h2
          class="pt-4"
          id="HR19"
        ></h2>
      </div><br>
      <div class="container">
        <br>
        <h3 class="pt-2">4.บริษัทGoogle </h3><br>
        <center><img src="~/assets/private/google.jpg"></center>
        <p class="pt-5">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;เป็นบริษัทมหาชนอเมริกัน มีรายได้หลักจากการโฆษณาออนไลน์ที่ปรากฏในเสิร์ชเอนจินของกูเกิล อีเมล แผนที่ออนไลน์ ซอฟต์แวร์จัดการด้านสำนักงาน เครือข่ายออนไลน์ และวิดีโอออนไลน์ รวมถึงการขายอุปกรณ์ช่วยในการค้นหา กูเกิลสำนักงานใหญ่ที่รู้จักในชื่อกูเกิลเพล็กซ์ตั้งอยู่ที่เมืองเมาน์เทนวิว รัฐแคลิฟอร์เนีย โดยมีพนักงาน 16,805 คน (31 ธันวาคม พ.ศ. 2550)โดยกูเกิลเป็นบริษัทอเมริกันที่ใหญ่ที่สุดที่ไม่ได้เป็นส่วนหนึ่งของดัชนีดาวโจนส์ (ข้อมูล 31 ตุลาคม พ.ศ. 2550)
          กูเกิลก่อตั้งโดย แลร์รี เพจ และ เซอร์เกย์ บริน ขณะที่ทั้งคู่กำลังศึกษาอยู่ที่มหาวิทยาลัยสแตนฟอร์ด ซึ่งภายหลังทั้งคู่ได้ก่อตั้งบริษัทเมื่อวันที่ 4 กันยายน พ.ศ. 2541 ในโรงจอดรถของเพื่อนที่ เมืองเมนโลพาร์ก ในรัฐแคลิฟอร์เนีย และมีการเสนอขายหุ้นใหม่แก่ประชาชนทั่วไปเป็นครั้งแรก เมื่อ 19 สิงหาคม พ.ศ. 2547 เพิ่มมูลค่าของบริษัท 1.67 พันล้านดอลลาร์สหรัฐ และหลังจากนั้นทางกูเกิลได้มีการขยายตัวตลอดเวลาจากการพัฒนาซอฟต์แวร์ใหม่และการซื้อกิจการอื่นรวมเข้ามา เช่น กูเกิล ดีปไมด์ รวมถึงก่อตั้งบริษัทลูกอย่างกูเกิล เอกซ์กูเกิลได้ถูกจัดอันดับให้เป็นบริษัทที่น่าทำงานมากที่สุดในสหรัฐอเมริกาโดยนิตยสารฟอร์จูน ซึ่งมีคติพจน์ประจำบริษัทคือ Don't be evil อย่างไรก็ตามทางบริษัทได้รับการวิพากษ์วิจารณ์ในด้านการละเมิดข้อมูลส่วนตัว การละเมิดลิขสิทธิ์ และการเซ็นเซอร์ในหลายส่วน
          วันที่ 10 สิงหาคม พ.ศ. 2558 แลร์รี เพจ และเซอร์เกย์ บริน สองผู้ก่อตั้งกูเกิล ได้ตั้งบริษัทใหม่ชื่อ "แอลฟาเบต" (Alphabet) โดยมีแผนจะใช้บริษัทนี้เป็นบริษัทแม่แทน และลดขนาดองค์กรกูเกิลลงเพื่อความคล่องตัวทางธุรกิจ ต่อมาวันที่ 1 กันยายน ปีเดียวกัน กูเกิลได้เปลี่ยนโลโก้บริษัทใหม่
        </p>
        <center>
          <p><b>พันธกิจ</b></p>
        </center>
        <center>
          <p>คือ การจัดระเบียบข้อมูลในโลกนี้และทำให้เข้าถึงได้ง่ายในทุกที่และมีประโยชน์</p>
        </center>
        <p><b>ผลิตภัณฑ์ของกูเกิล</b></p>
        <p><u>ซอฟต์แวร์เดสก์ทอป</u>&nbsp;:&nbsp;ซอฟต์แวร์ของกูเกิล จะเป็นซอฟต์แวร์ให้ดาวน์โหลดใช้งานฟรี และทำงานผ่านระบบของกูเกิล</p>
        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. กูเกิล ทอล์ก :<br>
          ทอล์ก (Google Talk) ซอฟต์แวร์เมสเซนเจอร์และวีโอไอพี<br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. กูเกิล เอิร์ธ :<br>
          เอิร์ธ (Google Earth) ซอฟต์แวร์ดูภาพถ่ายผ่านดาวเทียมและภาพถ่ายทางอากาศ ภูมิประเทศของแต่ละประเทศ ของโลก<br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. ปีกาซา :<br>
          ปีกาซา (Picasa) ซอฟต์แวร์สำหรับดูภาพภายในเครื่องคอมพิวเตอร์ ใช้งานคู่กับเว็บไซต์ปีกาซา<br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4. กูเกิล แพ็ก :<br>
          แพ็ก (Google Pack) เป็นชุดซอฟต์แวร์พร้อมดาวน์โหลด ประกอบด้วย โปรแกรมของกูเกิลเองได้แก่ เดสก์ท็อป ปีกาซา ทูลบาร์ โฟโต้สกรีนเซฟเวอร์ เอิร์ธ ทอร์ก วิดีโอเพลย์เยอร์ และโปรแกรมอื่นรวมถึง ไฟร์ฟอกซ์ สตาร์ออฟฟิศ อะโดบี รีดเดอร์ สไกป์<br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5. กูเกิล โครม :<br>
          โครม (Google Chrome) ซอฟต์แวร์เบราว์เซอร์<br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6. สเก็ตช์อัป :<br>
          สเก็ตช์อัป (SketchUp) ซอฟต์แวร์สำหรับวาดภาพสเก็ตช์ และภาพ 3 มิติ<br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7. กูเกิล สกาย แมพ :<br>
          สกาย แมพ (Google sky map) ซอฟต์แวร์ที่ใช้ดู แผนที่ดาว ตำแหน่งดาวเคราห์ และ ดาวฤกษ์ ของ กาแล็กซี่ต่างๆๆ<br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8. กูเกิล แมพ :<br>
          แมพ (Google Map) ซอฟต์แวร์สำหรับค้นหาแผนที่บนโลก<br>
        </p>
        <p><u>ด้านเอกสาร</u>&nbsp;:</p>
        <p>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. กูเกิล เอกสาร <br>
          เอกสาร (Google Meet Docs ) ซอฟต์แวร์ที่ใช้เกี่ยวกับ การเก็บข้อมูล ภาพ ข้อมูล เหมือนกับ Microsoft word<br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. กูเกิล ชีต <br>
          ชีต (Google Meet Sheet) ซอฟต์แวร์ ที่ใช้เกี่ยวกับ การทำข้อมูล กราฟเส้น ต่างๆๆ เหมือนกับ Microsoft Excle<br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. กูเกิล สไลด์ <br>
          สไลด์ (Google Meet Slides) ซอฟแวร์ ที่ใช้เกี่ยวกับ การนำเสนอ ข้อมูล ความรู้ เหมือนกับ Microsoft power point<br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4. กูเกิล คิป <br>
          คิป (Google Keep) ซอฟแวร์ ที่ใช้เกี่ยวกับ การจดบันทึก สิ่งต่างๆๆหรือสิ่งสำคัญ ซึ่งเหมือนการเก็บข้อมูลใน สมุด หรือ ไดอารี่<br>

        </p>
        <h2
          class="pt-4"
          id="HR20"
        ></h2>
      </div>
      <div class="container">
        <br>
        <h3 class="pt-2">5.การบินไทย </h3><br>
        <p><b>วิสัยทัศน์ :</b><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;วิสัยทัศน์(Vision) “เป็นสายการบินที่ลูกค้าเลือกเป็นอันดับแรก ให้บริการดีเลิศด้วยเสน่ห์ไทย” การบินไทย มุ่งมั่นที่จะเป็นสายการบินที่ลูกค้าเลือกใช้บริการ เป็นอันดับแรก ด้วยการสร้างความพึง พอใจสูงสุดแก่ลูกค้า ให้เหนือความคาดหมาย และสร้างความผูกพันที่ยั่งยืน ระหว่างบริษัทฯ กับลูกค้า โดยการ สร้างประสบการณ์การ เดินทางที่ราบรื่นและประทับใจด้วยเอกลักษณ์ความเป็นไทย ให้แก่ลูกค้าทุกคนอย่าง ต่อเนื่อง ด้วยบริการที่ดีเลิศและ สม่่าเสมอ (Consistency of Service Excellence) ในทุกจุด สัมผัสของการ ให้บริการ</p>
        <p><b>พันธกิจ (Mission) :</b><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;พันธกิจ (Mission) พันธกิจหลักของบริษัทฯ ประกอบด้วยพันธกิจต่อ ลูกค้า ผู้ถือหุ้น พนักงาน และสังคม ดังนี้ ให้บริการขนส่งทางอากาศอย่างครบวงจรทั้งภายในและ ระหว่างประเทศ โดยมุ่งเน้นในเรื่องมาตรฐาน ความปลอดภัย ความสะดวกสบาย การบริการที่มีคุณภาพด้วยเอกลักษณ์ ความเป็นไทย เพื่อส่งมอบ ผลิตภัณฑ์ที่มีคุณค่าและ ความน่าเชื่อถือสูง รวมทั้งเสริมสร้างความประทับใจและ ความสัมพันธ์ที่ดี กับ ลูกค้า มีการก่ากับดูแลกิจการที่ดีตามมาตรฐานสากล เพื่อสร้าง การเติบโตอย่างยั่งยืนให้แก่องค์กรและสร้าง ผลตอบแทน การลงทุนที่สูงให้แก่ ผู้ถือหุ้น เป็นองค์กรแห่งการเรียนรู้ที่สร้างความแข็งแกร่งให้กับ พนักงาน เพื่อให้ท่างานได้อย่างเต็มศักยภาพ ตระหนักถึง การให้ความส่าคัญแก่ลูกค้า เสริมสร้างขีดความสามารถ ทักษะ และความรับผิดชอบ ตลอดจนเพิ่มพูนความผูกพัน ต่อองค์กร ช่วยเหลือ ส่งเสริม และแสดงความรับผิดชอบต่อ สังคม และสิ่งแวดล้อม ในฐานะเป็นสายการบิน แห่งชาติ</p>
        <p><b>คุณค่าหลัก (Core Values) :</b><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;คุณค่าหลัก (Core Values) เพื่อให้บริษัทฯ สามารถเติบโตอย่างแข็งแกร่งและยั่งยืน และ สามารถแข่งขันได้ในสภาวะแวดล้อม ทางธุรกิจที่มีการ เปลี่ยนแปลงอย่างรวดเร็ว บริษัทฯ ส่งเสริมและยึดมั่นในคุณค่า หลักส่าคัญ 3 ประการ ได้แก่
          <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1) มุ่งเน้นการสร้างความพึงพอใจให้กับลูกค้า (Customer Satisfaction)
          <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2) ให้การบริการระดับโลก (World Class Services)
          <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3) สร้างคุณค่าในทุกมิติ (Value Creation)
        </p>
        <p><b>โครงสร้าง</b></p><br><br>
        <center><img src="~/assets/private/ta.jpg"></center>
      </div>

    </div>

  </div>
</template>

<script>
import sidebar from "~/components/private/sidebar";
import navbar from "~/components/navbar";
export default {
  components: {
    sidebar,
    navbar
  }
};
</script>

<style>
html {
  scroll-behavior: smooth;
}
#page-content-wrapper {
  width: auto;
  position: absolute;
  padding: 50px;
  margin-left: 200px;
}
</style>