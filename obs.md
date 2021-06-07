# การตั้งค่า OBS สำหรับ EZ Studio

โปรแกรม OBS มีความสามารถสูง สามารถผลิตสื่อได้หลากหลายรูปแบบ แต่ก็มีขั้นตอนที่ต้องตั้งค่า และเรียนรู้มากกว่าทางเลือกอื่นๆ ดังนั้น TLIC จึงได้ออกแบบแนวปฏิบัติที่ช่วยลดขั้นตอนและช่วยให้พร้อมใช้งาน ดังต่อไปนี้

## 1. ติดตั้งโปรแกรม nVidia Broadcast 

โปรแกรมนี้ใช้ความสามารถด้าน AI ของการ์ดจอตระกูล RTX ในการกัดภาพพื้นหลังของผู้พูด และตัดเสียงรบกวนจากไมโครโฟน ดังนั้นควรติดตั้งให้เรียบร้อยเป็นลำดับแรก  และเปิดใช้งานการตัดภาพพื้นหลังและตัดเสียงรบกวนในโปรแกรมให้เรียบร้อย

![&#xE40;&#xE1B;&#xE34;&#xE14;&#xE43;&#xE0A;&#xE49; Effect &quot;Background removal&quot; &#xE2A;&#xE33;&#xE2B;&#xE23;&#xE31;&#xE1A;&#xE01;&#xE25;&#xE49;&#xE2D;&#xE07; &#xE41;&#xE25;&#xE30; Noise Removal &#xE2A;&#xE33;&#xE2B;&#xE23;&#xE31;&#xE1A; Microphone](.gitbook/assets/image%20%284%29.png)

## 2. โหลดภาพสัญลักษณ์และภาพฉากหลัง

โหลดภาพเหล่านี้ เพื่อให้สามารถฝังภาพสัญลักษณ์ของมหาวิทยาลัยเชียงใหม่ และใช้ฉากหลังที่ TLIC จัดหาให้ได้โดยง่าย 

แตกไฟล์ไว้ใน Folder ชื่อ c:/obs-pics/    
หากเก็บไฟล์ในตำแหน่งอื่น จะต้องแก้ไข Scene ให้ชี้ไปยังไฟล์ในตำแหน่งเหล่านั้นในภายหลังด้วย 

## 3. โหลด OBS Scene Collection ที่ตั้งค่าไว้ให้แล้ว

TLIC ได้สร้าง Scene เพื่อใช้บันทึกสื่อการสอนไว้เป็นต้นแบบ สามารถโหลดและนำเข้าในโปรแกรม OBS ได้โดยตรง

โหลด Scene Collection



รายการของ Scene มีดังนี้

### 3.1 Speaker Only

แสดงภาพผู้พูดเต็มจอ โดยสามารถเลือกแสดงหรือซ่อนภาพฉากหลัง และตราสัญลักษณ์มหาวิทยาลัยได้ตามความต้องการ

![](.gitbook/assets/image%20%285%29.png)

สามารถเลือกแสดงหรือซ่อนภาพพื้นหลังและตราสัญลักษณ์ได้ในช่องตัวเลือก "Sources"  คลิ๊กสัญลักษณ์รูปดวงตาเพื่อสลับสถานะ "แสดง" และ "ซ่อน"   


![&#xE17;&#xE14;&#xE25;&#xE2D;&#xE07;&#xE41;&#xE2A;&#xE14;&#xE07;&#xE2B;&#xE23;&#xE37;&#xE2D;&#xE0B;&#xE48;&#xE2D;&#xE19;&#xE20;&#xE32;&#xE1E;&#xE1E;&#xE37;&#xE49;&#xE19;&#xE2B;&#xE25;&#xE31;&#xE07; &#xE41;&#xE25;&#xE30;&#xE2A;&#xE31;&#xE0D;&#xE25;&#xE31;&#xE01;&#xE29;&#xE13;&#xE4C;&#xE44;&#xE14;&#xE49;&#xE08;&#xE32;&#xE01;&#xE15;&#xE31;&#xE27;&#xE40;&#xE25;&#xE37;&#xE2D;&#xE01;&#xE40;&#xE2B;&#xE25;&#xE48;&#xE32;&#xE19;&#xE35;&#xE49;](.gitbook/assets/image%20%289%29.png)

### 3.2 Slide Only

Scene นี้จะแสดงภาพบนหน้าจอที่สอง ดังนั้นหากนำสื่อนำเสนอแสดงไว้บนหน้าจอนี้ก็จะช่วยให้บันทึกสื่อได้อย่างชัดเจน

![](.gitbook/assets/image%20%288%29.png)

### 3.3 PiP - right และ PiP - left

Scene ทั้งสองนี้จะแสดงภาพสื่อและแทรกผู้พูดลงไป \(Picture in Picture\) ในมุมซ้ายและมุมขวาตามลำดับพร้อมกัดฉากหลังออก

![&#xE15;&#xE31;&#xE27;&#xE2D;&#xE22;&#xE48;&#xE32;&#xE07; PiP &#xE41;&#xE17;&#xE23;&#xE01;&#xE1C;&#xE39;&#xE49;&#xE1E;&#xE39;&#xE14;&#xE14;&#xE49;&#xE32;&#xE19;&#xE21;&#xE38;&#xE21;&#xE02;&#xE27;&#xE32;](.gitbook/assets/image%20%2810%29.png)

![&#xE15;&#xE31;&#xE27;&#xE2D;&#xE22;&#xE48;&#xE32;&#xE07; PiP &#xE41;&#xE17;&#xE23;&#xE01;&#xE1C;&#xE39;&#xE49;&#xE1E;&#xE39;&#xE14;&#xE14;&#xE49;&#xE32;&#xE19;&#xE21;&#xE38;&#xE21;&#xE0B;&#xE49;&#xE32;&#xE22;](.gitbook/assets/image%20%286%29.png)

## 4. โหลด Profile ที่ตั้งค่าไว้ให้แล้ว

ค่าความละเอียดของการบันทึก ตลอดจนคีย์ลัดในการเริ่ม/หยุดการบันทึก ตลอดจนการเปลี่ยน Scene ได้ถูกกำหนดมาให้แล้ว สามารถโหลดและติดตั้งใน OBS ได้ทันที

โหลด Profile 

คีย์ลัดที่ตั้งค่าไว้จะช่วยให้สามารถใช้งานกล่อง EZ Controller ในการเลือก Scene และควบคุมการเริ่ม, หยุด, หยุดชั่วคราว การบันทึกได้ 

![&#xE41;&#xE2A;&#xE14;&#xE07;&#xE2B;&#xE19;&#xE49;&#xE32;&#xE17;&#xE35;&#xE48;&#xE02;&#xE2D;&#xE07;&#xE1B;&#xE38;&#xE48;&#xE21;&#xE1A;&#xE19;&#xE41;&#xE1C;&#xE07; EZ Controller &#xE15;&#xE32;&#xE21;&#xE17;&#xE35;&#xE48;&#xE01;&#xE33;&#xE2B;&#xE19;&#xE14;&#xE44;&#xE27;&#xE49;&#xE43;&#xE2B;&#xE49;&#xE43;&#xE19; Profile](.gitbook/assets/image%20%287%29.png)


