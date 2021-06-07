---
description: >-
  OBS Studio หรือ Open Broadcaster Software Studio เป็น
  โปรแกรมที่มีประสิทธิภาพสูง และมีความสามารถที่หลากหลาย
  ซึ่งจะช่วยให้สื่อการเรียนการสอนของท่านนั้นดูน่าสนใจและมีความเป็นมืออาชีพสูง
---

# ด้วย OBS Studio

## ⭐ แนะนำ OBS Studio

```text
Video preview
```

## เริ่มต้นใช้งาน OBS Studio

          โปรแกรม OBS มีความสามารถสูงทั้งในส่วนของความสามารถด้าน AI ของการ์ดจอตระกูล RTX ในการกัดภาพพื้นหลังของผู้พูด และตัดเสียงรบกวนจากไมโครโฟน  ทำให้สามารถผลิตสื่อได้หลากหลายรูปแบบ แต่ก็มีขั้นตอนที่ต้องตั้งค่า และเรียนรู้มากกว่าทางเลือกอื่นๆ  

          ดังนั้น TLIC จึงได้ออกแบบแนวปฏิบัติที่ช่วยลดขั้นตอนและช่วยให้พร้อมใช้งาน ดังต่อไปนี้

## 1. ติดตั้งโปรแกรม nVidia Broadcast  <a id="1-nvidia-broadcast"></a>

          ทำการติดตั้งโปรแรกมเป็นลำดับแรก และเปิดใช้งานการตัดภาพพื้นหลังและตัดเสียงรบกวนในโปรแกรมให้เรียบร้อย โดยเปิดใช้ Effect "**Background removal**" สำหรับกล้อง และ "**Noise Removal"** สำหรับ Microphone

![](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb11GznRqeEU6YNCfJ6%2F-Mb196R_9s-ua9mG_y8R%2Fimage.png?alt=media&token=5f7e7af3-16e8-4757-a617-d0847b11c8e6)

## 2. โหลดภาพสัญลักษณ์และภาพฉากหลัง <a id="2"></a>

          โหลดภาพเหล่านี้ เพื่อให้สามารถฝังภาพสัญลักษณ์ของมหาวิทยาลัยเชียงใหม่ และใช้ฉากหลังที่ TLIC จัดหาให้ได้โดยง่าย

          แตกไฟล์ไว้ใน Folder ชื่อ c:/obs-pics/ หากเก็บไฟล์ในตำแหน่งอื่น จะต้องแก้ไข Scene ให้ชี้ไปยังไฟล์ในตำแหน่งเหล่านั้นในภายหลังด้วย

## 3. โหลด OBS Scene Collection ที่ตั้งค่าไว้ให้แล้ว <a id="3-obs-scene-collection"></a>

          TLIC ได้สร้าง Scene เพื่อใช้บันทึกสื่อการสอนไว้เป็นต้นแบบ สามารถโหลดและนำเข้าในโปรแกรม OBS ได้โดยตรง

โหลด Scene Collection

​

รายการของ Scene มีดังนี้

### 3.1 Speaker Only <a id="3-1-speaker-only"></a>

แสดงภาพผู้พูดเต็มจอ โดยสามารถเลือกแสดงหรือซ่อนภาพฉากหลัง และตราสัญลักษณ์มหาวิทยาลัยได้ตามความต้องการ

![](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb11GznRqeEU6YNCfJ6%2F-Mb17aADETL0Q1x12NGm%2Fimage.png?alt=media&token=bd8a1c35-c694-4263-b00a-c3f312fad088)

สามารถเลือกแสดงหรือซ่อนภาพพื้นหลังและตราสัญลักษณ์ได้ในช่องตัวเลือก "Sources" คลิ๊กสัญลักษณ์รูปดวงตาเพื่อสลับสถานะ "แสดง" และ "ซ่อน"

![](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb11GznRqeEU6YNCfJ6%2F-Mb17sgOT2jt9iEkaOzR%2Fimage.png?alt=media&token=d7cc43c1-3897-40aa-99d9-027feadc5327)

ทดลองแสดงหรือซ่อนภาพพื้นหลัง และสัญลักษณ์ได้จากตัวเลือกเหล่านี้

### 3.2 Slide Only <a id="3-2-slide-only"></a>

Scene นี้จะแสดงภาพบนหน้าจอที่สอง ดังนั้นหากนำสื่อนำเสนอแสดงไว้บนหน้าจอนี้ก็จะช่วยให้บันทึกสื่อได้อย่างชัดเจน

![](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb11GznRqeEU6YNCfJ6%2F-Mb16gyAG2aVPwW3o0im%2Fimage.png?alt=media&token=201bd04c-aa78-4a5a-a507-4ebdffaa9630)

### 3.3 PiP - right และ PiP - left <a id="3-3-pip-right-pip-left"></a>

Scene ทั้งสองนี้จะแสดงภาพสื่อและแทรกผู้พูดลงไป \(Picture in Picture\) ในมุมซ้ายและมุมขวาตามลำดับพร้อมกัดฉากหลังออก

![](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb19JFcF2zQ-45d-mbE%2F-Mb19vyL8voQQPoYnGZT%2Fimage.png?alt=media&token=a90e3041-d919-4eba-9ca7-da846a8a9a54)

ตัวอย่าง PiP แทรกผู้พูดด้านมุมขวา

![](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb19JFcF2zQ-45d-mbE%2F-Mb1ADdbdhZFR8cR6xqg%2Fimage.png?alt=media&token=12f51364-116a-4c09-af95-0a2bdd97baa7)

ตัวอย่าง PiP แทรกผู้พูดด้านมุมซ้าย

## 4. โหลด Profile ที่ตั้งค่าไว้ให้แล้ว <a id="4-profile"></a>

         ค่าความละเอียดของการบันทึก ตลอดจนคีย์ลัดในการเริ่ม/หยุดการบันทึก ตลอดจนการเปลี่ยน Scene ได้ถูกกำหนดมาให้แล้ว สามารถโหลดและติดตั้งใน OBS ได้ทันที

          คีย์ลัดที่ตั้งค่าไว้จะช่วยให้สามารถใช้งานกล่อง EZ Controller ในการเลือก Scene และควบคุมการเริ่ม, หยุด, หยุดชั่วคราว การบันทึกได้

![](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb1B61xAkZ_u3NFpZm4%2F-Mb1DaL15vKIiaRm5bhf%2Fimage.png?alt=media&token=1dfb3743-4d9d-40a2-b03b-9b534ada7330)

แสดงหน้าที่ของปุ่มบนแผง EZ Controller ตามที่กำหนดไว้ให้ใน Profile

## การติดตั้ง OBS Studio 

**ดาวน์โหลดได้ที่นี่** : [https://obsproject.com/](https://obsproject.com/)

