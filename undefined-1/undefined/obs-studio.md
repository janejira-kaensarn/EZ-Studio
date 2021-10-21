---
description: >-
  OBS Studio หรือ Open Broadcaster Software Studio เป็น
  โปรแกรมที่มีประสิทธิภาพสูง และมีความสามารถที่หลากหลาย
  ซึ่งจะช่วยให้สื่อการเรียนการสอนของท่านนั้นดูน่าสนใจและมีความเป็นมืออาชีพสูง
---

# OBS Studio

## :star: แนะนำ OBS Studio

```
Video preview
```

## เริ่มต้นใช้งาน OBS Studio

&#x20;         โปรแกรม OBS มีความสามารถสูงทั้งในส่วนของความสามารถด้าน AI ของการ์ดจอตระกูล RTX ในการกัดภาพพื้นหลังของผู้พูด และตัดเสียงรบกวนจากไมโครโฟน  ทำให้สามารถผลิตสื่อได้หลากหลายรูปแบบ แต่ก็มีขั้นตอนที่ต้องตั้งค่า และเรียนรู้มากกว่าทางเลือกอื่นๆ &#x20;

&#x20;         ดังนั้น TLIC จึงได้ออกแบบแนวปฏิบัติที่ช่วยลดขั้นตอนในการตั้งค่าและช่วยให้พร้อมใช้งานได้ในทันที โดยมีขั้นตอนในการดาวน์โหลดและติดตั้งโปรแกรมบันทึกสื่อดังต่อไปนี้

{% content-ref url="broken-reference" %}
[Broken link](broken-reference)
{% endcontent-ref %}

## 1. ติดตั้งโปรแกรม nVidia Broadcast  <a href="1-nvidia-broadcast" id="1-nvidia-broadcast"></a>

&#x20;         ทำการติดตั้งโปรแกรมเป็นลำดับแรก และเปิดใช้งานการตัดภาพพื้นหลังและตัดเสียงรบกวนในโปรแกรมให้เรียบร้อย โดยเปิดใช้ Effect "**Background removal**" สำหรับกล้อง และ "**Noise Removal" **สำหรับ Microphone

* [ดาวโหลด nVidia Broadcast](https://drive.google.com/drive/u/2/folders/1Yn0Lp0pvyA1u6dWYfmNOop2Uml6ARj6Q)

![เปิดใช้ Effect "Background removal" สำหรับกล้อง และ Noise Removal สำหรับ Microphone](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb11GznRqeEU6YNCfJ6%2F-Mb196R\_9s-ua9mG\_y8R%2Fimage.png?alt=media\&token=5f7e7af3-16e8-4757-a617-d0847b11c8e6)

## 2. โหลดภาพสัญลักษณ์และภาพฉากหลัง <a href="2" id="2"></a>

&#x20;         ท่านสามารถดาวน์โหลดภาพสัญลักษณ์และภาพฉากหลังที่ TLIC จัดหาให้ เพื่อให้สามารถฝังภาพสัญลักษณ์ของมหาวิทยาลัยเชียงใหม่ได้โดยโดยง่าย

* [ดาวน์โหลดไฟล์ภาพสัญลักษณ์และฉากหลัง](https://drive.google.com/drive/u/2/folders/1Yn0Lp0pvyA1u6dWYfmNOop2Uml6ARj6Qhttps://drive.google.com/drive/u/2/folders/1Yn0Lp0pvyA1u6dWYfmNOop2Uml6ARj6Q)

&#x20;         แตกไฟล์ไว้ใน Folder ชื่อ `c:/obs-pics/` หากท่านเก็บไฟล์ในตำแหน่งอื่น จะต้องทำการแก้ไข Scene ให้ชี้ไปยังไฟล์ในตำแหน่งเหล่านั้นในภายหลังด้วย

## 3. โหลด OBS Scene Collection ที่ตั้งค่าไว้ให้แล้ว <a href="3-obs-scene-collection" id="3-obs-scene-collection"></a>

&#x20;         TLIC ได้สร้าง Scene เพื่อใช้บันทึกสื่อการสอนไว้เป็นต้นแบบ ท่านสามารถโหลดและนำเข้าในโปรแกรม OBS ได้โดยตรง สามารถดาวน์โหลดได้ที่นี่

* [ดาวน์โหลด Scene Collection](https://drive.google.com/drive/u/2/folders/1Yn0Lp0pvyA1u6dWYfmNOop2Uml6ARj6Qhttps://drive.google.com/drive/u/2/folders/1Yn0Lp0pvyA1u6dWYfmNOop2Uml6ARj6Qhttps://drive.google.com/drive/u/2/folders/1Yn0Lp0pvyA1u6dWYfmNOop2Uml6ARj6Q)

รายการของ Scene ที่ TLIC จัดทำไว้ให้ มีดังนี้

### 3.1 Speaker Only <a href="3-1-speaker-only" id="3-1-speaker-only"></a>

&#x20;         แสดงภาพผู้พูดเต็มจอ โดยสามารถเลือก **"แสดง"** หรือ **"ซ่อน"** ภาพฉากหลัง และตราสัญลักษณ์มหาวิทยาลัยได้ตามความต้องการ

![](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb11GznRqeEU6YNCfJ6%2F-Mb17aADETL0Q1x12NGm%2Fimage.png?alt=media\&token=bd8a1c35-c694-4263-b00a-c3f312fad088)

สามารถเลือกแสดงหรือซ่อนภาพพื้นหลังและตราสัญลักษณ์ได้ในช่องตัวเลือก "**Sources**" คลิ๊กสัญลักษณ์รูปดวงตาเพื่อสลับสถานะ "**แสดง**" และ "**ซ่อน**"

![ทดลองแสดงหรือซ่อนภาพพื้นหลัง และสัญลักษณ์ได้จากตัวเลือกเหล่านี้](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb11GznRqeEU6YNCfJ6%2F-Mb17sgOT2jt9iEkaOzR%2Fimage.png?alt=media\&token=d7cc43c1-3897-40aa-99d9-027feadc5327)

{% hint style="info" %}
หากไม่ได้ใช้โปรแกรม nVidia Broadcast ผู้ใช้จะต้องแก้ไขแหล่งภาพและเสียงใน Scene ให้ตรงกับกล้องและไมโครโฟนที่ใช้จริง เช่นในรายการในภาพข้างต้นจะต้องแก้ไข nVidia Broadcast Camera และ nVidia Broadcast Mic&#x20;
{% endhint %}

### 3.2 Slide Only <a href="3-2-slide-only" id="3-2-slide-only"></a>

&#x20;          Scene นี้จะแสดงภาพบนหน้าจอที่สอง ดังนั้นหากนำสื่อนำเสนอแสดงไว้บนหน้าจอนี้ก็จะช่วยให้บันทึกสื่อได้อย่างชัดเจน

![](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb11GznRqeEU6YNCfJ6%2F-Mb16gyAG2aVPwW3o0im%2Fimage.png?alt=media\&token=201bd04c-aa78-4a5a-a507-4ebdffaa9630)

### 3.3 PiP - Right และ PiP - Left <a href="3-3-pip-right-pip-left" id="3-3-pip-right-pip-left"></a>

&#x20;         **PiP** หรือ **Picture in Picture** นั้น จะแสดงภาพสื่อและภาพของผู้พูดแทรกลงไปพร้อมกัดฉากหลังออก โดยท่านสามารถกำหนดได้ว่าจะแทรก **PiP** หรือ **Picture in Picture **ในมุมซ้ายหรือมุมขวา&#x20;

#### ตัวอย่าง  PiP - Right หรือ **Picture in Picture** แทรกผู้พูดด้านมุมขวา

![ตัวอย่าง PiP แทรกผู้พูดด้านมุมขวา](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb19JFcF2zQ-45d-mbE%2F-Mb19vyL8voQQPoYnGZT%2Fimage.png?alt=media\&token=a90e3041-d919-4eba-9ca7-da846a8a9a54)

#### ตัวอย่าง  PiP - Left หรือ **Picture in Picture** แทรกผู้พูดด้านมุมซ้าย

![ตัวอย่าง PiP แทรกผู้พูดด้านมุมซ้าย](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb19JFcF2zQ-45d-mbE%2F-Mb1ADdbdhZFR8cR6xqg%2Fimage.png?alt=media\&token=12f51364-116a-4c09-af95-0a2bdd97baa7)

## 4. โหลด Profile ที่ตั้งค่าไว้ให้แล้ว <a href="4-profile" id="4-profile"></a>

&#x20;         ค่าความละเอียดของการบันทึก รวมถึงคีย์ลัดในการเริ่ม/หยุดการบันทึก ตลอดจนการเปลี่ยน Scene ได้ถูกกำหนดมาให้แล้ว ท่านสามารถโหลดและติดตั้งใน OBS ได้ทันที

* [ดาวน์โหลด OBS Profile ](https://drive.google.com/drive/u/2/folders/1Yn0Lp0pvyA1u6dWYfmNOop2Uml6ARj6Q)

เมื่อติดตั้ง Profile แล้วให้เปิดใช้งานโดยเลือกเมนู `"Profile / EZ Studio"`

&#x20;         คีย์ลัดที่ตั้งค่าไว้จะช่วยให้ท่านสามารถใช้งานกล่อง EZ Controller ในการเลือก Scene รูปแบบต่างๆ ได้ทันที รวมไปถึงควบคุมการเริ่ม, หยุด, หยุดชั่วคราว ในการบันทึกได้

![ภาพแสดงหน้าที่ของปุ่มบนแผง EZ Controller ตามที่กำหนดไว้ให้ใน Profile](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb1B61xAkZ\_u3NFpZm4%2F-Mb1DaL15vKIiaRm5bhf%2Fimage.png?alt=media\&token=1dfb3743-4d9d-40a2-b03b-9b534ada7330)

## การตั้งค่า OBS สำหรับ CMU EZ Studio Controller <a href="obs-ez-studio" id="obs-ez-studio"></a>

| ชื่อ                               | Download                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | คำอธิบาย                                                                                                                                                                                                                                |
| ---------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ภาพพื้นหลังและสัญลักษณ์มหาวิทยาลัย | [Download](https://o365cmu-my.sharepoint.com/personal/arnan\_s\_cmu\_ac\_th1/\_layouts/15/onedrive.aspx?id=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings%2Fobs%2Dpics%2Ezip\&parent=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings\&originalPath=aHR0cHM6Ly9vMzY1Y211LW15LnNoYXJlcG9pbnQuY29tLzp1Oi9nL3BlcnNvbmFsL2FybmFuX3NfY211X2FjX3RoMS9FY3Y2cG4yZExIbE9wQXJsQWYtMXJCY0JJc3FFVXJ6YklRZ2VtWW5VdDN3OU9nP3J0aW1lPTFWUmRkZzhyMlVn)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | <p>ภาพพื้นฐานที่รวบรวมไว้เพื่อความสะดวก ประกอบไปด้วยสัญลักษณ์มหาวิทยาลัยเชียงใหม่ ขนาดใหญ่ และขนาดเล็ก ภาพพื้นหลังที่พร้อมใช้งาน</p><p>​</p><p>ขอให้ติดตั้งไฟล์ไว้ใน folder ชื่อ <code>c:/obs-pics</code></p>                           |
| OBS Scene Collection               | [Download](https://o365cmu-my.sharepoint.com/personal/arnan\_s\_cmu\_ac\_th1/\_layouts/15/onedrive.aspx?id=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings%2FTLIC%5FEZ%5FStudio%2Ejson\&parent=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings\&originalPath=aHR0cHM6Ly9vMzY1Y211LW15LnNoYXJlcG9pbnQuY29tLzp1Oi9nL3BlcnNvbmFsL2FybmFuX3NfY211X2FjX3RoMS9FZWJhM21lTGJONUJwX3NTeWtzRGdmSUJhb19kWWJsS01IVkVYVG5MUVdnZi1BP3J0aW1lPTFIeXVTcFlwMlVn)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Scene สำเร็จรูปสำหรับ OBS ในชุดสามารถเลือกแสดง ผู้พูด, สื่อนำเสนอ, แทรกผู้พูดในมุมซ้าย และขวา ติดตั้งใน OBS โดยเลือกเมนู `Scene Collection / Import`                                                                                    |
| OBS Profile                        | [Download](https://o365cmu-my.sharepoint.com/personal/arnan\_s\_cmu\_ac\_th1/\_layouts/15/onedrive.aspx?id=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings%2FEZ%5FStudio%5FProfile%2Ezip\&parent=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings\&originalPath=aHR0cHM6Ly9vMzY1Y211LW15LnNoYXJlcG9pbnQuY29tLzp1Oi9nL3BlcnNvbmFsL2FybmFuX3NfY211X2FjX3RoMS9FYlh2NFlpOUlzMVBvMzlyT2E1TWVTNEIwS2pQX2VLZ01vRVZtWGxudDNtZ2N3P3J0aW1lPUlIMTRVNVlwMlVn)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | <p>Profile ที่ตั้งค่าคีย์ลัดไว้เพื่อใช้งานกล่อง EZ Controller กับ Scene Collection ได้โดยง่าย นอกจากนั้นยังตั้งค่าความละเอียดของกล้อง Webcam ให้เป็น Full HD</p><p>​</p><p>ติดตั้งใน OBS โดยเลือกเมนู <code>Profile / Import</code></p> |
| โปสเตอร์แสดงคีย์ลัด                | [PDF](https://o365cmu-my.sharepoint.com/personal/arnan\_s\_cmu\_ac\_th1/\_layouts/15/onedrive.aspx?id=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings%2FEz%20Controller%20Key%20Mappings%2Epdf\&parent=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings\&originalPath=aHR0cHM6Ly9vMzY1Y211LW15LnNoYXJlcG9pbnQuY29tLzpiOi9nL3BlcnNvbmFsL2FybmFuX3NfY211X2FjX3RoMS9FWElMZlVvXzB0Qkx2LWNhZG5GNURvRUJib2VhSVNLTkNoNUNqOHZsWXpydFZBP3J0aW1lPUJMUnhYSllwMlVn),[PNG](https://o365cmu-my.sharepoint.com/personal/arnan\_s\_cmu\_ac\_th1/\_layouts/15/onedrive.aspx?id=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings%2Fez%20controller%20key%20mappings%2Epng\&parent=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings\&originalPath=aHR0cHM6Ly9vMzY1Y211LW15LnNoYXJlcG9pbnQuY29tLzppOi9nL3BlcnNvbmFsL2FybmFuX3NfY211X2FjX3RoMS9FZHpzWDVmX2ptUk1oTkV3VnRoOG1Zd0JSTWFiNUdVSktkSy02MUxSQWkyYTl3P3J0aW1lPXFMNDBaSllwMlVn) | <p>ภาพแสดงผังและหน้าที่ของปุ่ม EZ Controller ที่ใช้ร่วมกับ Profile ข้างต้น</p><p>​</p>                                                                                                                                                  |

{% hint style="success" %}
ดาวโหลดไฟล์ทั้งหมด[กดที่นี่](https://drive.google.com/drive/folders/1Yn0Lp0pvyA1u6dWYfmNOop2Uml6ARj6Q?usp=sharing)
{% endhint %}

## การติดตั้ง OBS Studio&#x20;

**ดาวน์โหลดได้ที่นี่** : [https://obsproject.com/](https://obsproject.com)
