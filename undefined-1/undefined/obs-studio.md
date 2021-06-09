---
description: >-
  OBS Studio หรือ Open Broadcaster Software Studio เป็น
  โปรแกรมที่มีประสิทธิภาพสูง และมีความสามารถที่หลากหลาย
  ซึ่งจะช่วยให้สื่อการเรียนการสอนของท่านนั้นดูน่าสนใจและมีความเป็นมืออาชีพสูง
---

# OBS Studio

## ⭐ แนะนำ OBS Studio

```text
Video preview
```

## เริ่มต้นใช้งาน OBS Studio

          โปรแกรม OBS มีความสามารถสูงทั้งในส่วนของความสามารถด้าน AI ของการ์ดจอตระกูล RTX ในการกัดภาพพื้นหลังของผู้พูด และตัดเสียงรบกวนจากไมโครโฟน  ทำให้สามารถผลิตสื่อได้หลากหลายรูปแบบ แต่ก็มีขั้นตอนที่ต้องตั้งค่า และเรียนรู้มากกว่าทางเลือกอื่นๆ  

          ดังนั้น TLIC จึงได้ออกแบบแนวปฏิบัติที่ช่วยลดขั้นตอนในการตั้งค่าและช่วยให้พร้อมใช้งานได้ในทันที โดยมีขั้นตอนในการดาวน์โหลดและติดตั้งโปรแกรมบันทึกสื่อดังต่อไปนี้

{% page-ref page="../../undefined/undefined-3.md" %}

## 1. ติดตั้งโปรแกรม nVidia Broadcast  <a id="1-nvidia-broadcast"></a>

          ทำการติดตั้งโปรแกรมเป็นลำดับแรก และเปิดใช้งานการตัดภาพพื้นหลังและตัดเสียงรบกวนในโปรแกรมให้เรียบร้อย โดยเปิดใช้ Effect "**Background removal**" สำหรับกล้อง และ "**Noise Removal"** สำหรับ Microphone

* [ดาวโหลด nVidia Broadcast](../../undefined/undefined-3.md)

![&#xE40;&#xE1B;&#xE34;&#xE14;&#xE43;&#xE0A;&#xE49; Effect &quot;Background removal&quot; &#xE2A;&#xE33;&#xE2B;&#xE23;&#xE31;&#xE1A;&#xE01;&#xE25;&#xE49;&#xE2D;&#xE07; &#xE41;&#xE25;&#xE30; Noise Removal &#xE2A;&#xE33;&#xE2B;&#xE23;&#xE31;&#xE1A; Microphone](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb11GznRqeEU6YNCfJ6%2F-Mb196R_9s-ua9mG_y8R%2Fimage.png?alt=media&token=5f7e7af3-16e8-4757-a617-d0847b11c8e6)

## 2. โหลดภาพสัญลักษณ์และภาพฉากหลัง <a id="2"></a>

          ท่านสามารถดาวน์โหลดภาพสัญลักษณ์และภาพฉากหลังที่ TLIC จัดหาให้ เพื่อให้สามารถฝังภาพสัญลักษณ์ของมหาวิทยาลัยเชียงใหม่ได้โดยโดยง่าย

* [ดาวน์โหลดไฟล์ภาพสัญลักษณ์และฉากหลัง](../../undefined/undefined-3.md)

          แตกไฟล์ไว้ใน Folder ชื่อ `c:/obs-pics/` หากท่านเก็บไฟล์ในตำแหน่งอื่น จะต้องทำการแก้ไข Scene ให้ชี้ไปยังไฟล์ในตำแหน่งเหล่านั้นในภายหลังด้วย

## 3. โหลด OBS Scene Collection ที่ตั้งค่าไว้ให้แล้ว <a id="3-obs-scene-collection"></a>

          TLIC ได้สร้าง Scene เพื่อใช้บันทึกสื่อการสอนไว้เป็นต้นแบบ ท่านสามารถโหลดและนำเข้าในโปรแกรม OBS ได้โดยตรง สามารถดาวน์โหลดได้ที่นี่

* [ดาวน์โหลด Scene Collection](../../undefined/undefined-3.md)

รายการของ Scene ที่ TLIC จัดทำไว้ให้ มีดังนี้

### 3.1 Speaker Only <a id="3-1-speaker-only"></a>

          แสดงภาพผู้พูดเต็มจอ โดยสามารถเลือก **"แสดง"** หรือ **"ซ่อน"** ภาพฉากหลัง และตราสัญลักษณ์มหาวิทยาลัยได้ตามความต้องการ

![](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb11GznRqeEU6YNCfJ6%2F-Mb17aADETL0Q1x12NGm%2Fimage.png?alt=media&token=bd8a1c35-c694-4263-b00a-c3f312fad088)

สามารถเลือกแสดงหรือซ่อนภาพพื้นหลังและตราสัญลักษณ์ได้ในช่องตัวเลือก "**Sources**" คลิ๊กสัญลักษณ์รูปดวงตาเพื่อสลับสถานะ "**แสดง**" และ "**ซ่อน**"

![&#xE17;&#xE14;&#xE25;&#xE2D;&#xE07;&#xE41;&#xE2A;&#xE14;&#xE07;&#xE2B;&#xE23;&#xE37;&#xE2D;&#xE0B;&#xE48;&#xE2D;&#xE19;&#xE20;&#xE32;&#xE1E;&#xE1E;&#xE37;&#xE49;&#xE19;&#xE2B;&#xE25;&#xE31;&#xE07; &#xE41;&#xE25;&#xE30;&#xE2A;&#xE31;&#xE0D;&#xE25;&#xE31;&#xE01;&#xE29;&#xE13;&#xE4C;&#xE44;&#xE14;&#xE49;&#xE08;&#xE32;&#xE01;&#xE15;&#xE31;&#xE27;&#xE40;&#xE25;&#xE37;&#xE2D;&#xE01;&#xE40;&#xE2B;&#xE25;&#xE48;&#xE32;&#xE19;&#xE35;&#xE49;](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb11GznRqeEU6YNCfJ6%2F-Mb17sgOT2jt9iEkaOzR%2Fimage.png?alt=media&token=d7cc43c1-3897-40aa-99d9-027feadc5327)

{% hint style="info" %}
หากไม่ได้ใช้โปรแกรม nVidia Broadcast ผู้ใช้จะต้องแก้ไขแหล่งภาพและเสียงใน Scene ให้ตรงกับกล้องและไมโครโฟนที่ใช้จริง เช่นในรายการในภาพข้างต้นจะต้องแก้ไข nVidia Broadcast Camera และ nVidia Broadcast Mic 
{% endhint %}

### 3.2 Slide Only <a id="3-2-slide-only"></a>

           Scene นี้จะแสดงภาพบนหน้าจอที่สอง ดังนั้นหากนำสื่อนำเสนอแสดงไว้บนหน้าจอนี้ก็จะช่วยให้บันทึกสื่อได้อย่างชัดเจน

![](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb11GznRqeEU6YNCfJ6%2F-Mb16gyAG2aVPwW3o0im%2Fimage.png?alt=media&token=201bd04c-aa78-4a5a-a507-4ebdffaa9630)

### 3.3 PiP - Right และ PiP - Left <a id="3-3-pip-right-pip-left"></a>

          **PiP** หรือ **Picture in Picture** นั้น จะแสดงภาพสื่อและภาพของผู้พูดแทรกลงไปพร้อมกัดฉากหลังออก โดยท่านสามารถกำหนดได้ว่าจะแทรก **PiP** หรือ **Picture in Picture** ในมุมซ้ายหรือมุมขวา 

#### ตัวอย่าง  PiP - Right หรือ **Picture in Picture** แทรกผู้พูดด้านมุมขวา

![&#xE15;&#xE31;&#xE27;&#xE2D;&#xE22;&#xE48;&#xE32;&#xE07; PiP &#xE41;&#xE17;&#xE23;&#xE01;&#xE1C;&#xE39;&#xE49;&#xE1E;&#xE39;&#xE14;&#xE14;&#xE49;&#xE32;&#xE19;&#xE21;&#xE38;&#xE21;&#xE02;&#xE27;&#xE32;](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb19JFcF2zQ-45d-mbE%2F-Mb19vyL8voQQPoYnGZT%2Fimage.png?alt=media&token=a90e3041-d919-4eba-9ca7-da846a8a9a54)

#### ตัวอย่าง  PiP - Left หรือ **Picture in Picture** แทรกผู้พูดด้านมุมซ้าย

![&#xE15;&#xE31;&#xE27;&#xE2D;&#xE22;&#xE48;&#xE32;&#xE07; PiP &#xE41;&#xE17;&#xE23;&#xE01;&#xE1C;&#xE39;&#xE49;&#xE1E;&#xE39;&#xE14;&#xE14;&#xE49;&#xE32;&#xE19;&#xE21;&#xE38;&#xE21;&#xE0B;&#xE49;&#xE32;&#xE22;](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb19JFcF2zQ-45d-mbE%2F-Mb1ADdbdhZFR8cR6xqg%2Fimage.png?alt=media&token=12f51364-116a-4c09-af95-0a2bdd97baa7)

## 4. โหลด Profile ที่ตั้งค่าไว้ให้แล้ว <a id="4-profile"></a>

          ค่าความละเอียดของการบันทึก รวมถึงคีย์ลัดในการเริ่ม/หยุดการบันทึก ตลอดจนการเปลี่ยน Scene ได้ถูกกำหนดมาให้แล้ว ท่านสามารถโหลดและติดตั้งใน OBS ได้ทันที

* [ดาวน์โหลด OBS Profile ](../../undefined/undefined-3.md)

เมื่อติดตั้ง Profile แล้วให้เปิดใช้งานโดยเลือกเมนู `"Profile / EZ Studio"`

          คีย์ลัดที่ตั้งค่าไว้จะช่วยให้ท่านสามารถใช้งานกล่อง EZ Controller ในการเลือก Scene รูปแบบต่างๆ ได้ทันที รวมไปถึงควบคุมการเริ่ม, หยุด, หยุดชั่วคราว ในการบันทึกได้

![&#xE20;&#xE32;&#xE1E;&#xE41;&#xE2A;&#xE14;&#xE07;&#xE2B;&#xE19;&#xE49;&#xE32;&#xE17;&#xE35;&#xE48;&#xE02;&#xE2D;&#xE07;&#xE1B;&#xE38;&#xE48;&#xE21;&#xE1A;&#xE19;&#xE41;&#xE1C;&#xE07; EZ Controller &#xE15;&#xE32;&#xE21;&#xE17;&#xE35;&#xE48;&#xE01;&#xE33;&#xE2B;&#xE19;&#xE14;&#xE44;&#xE27;&#xE49;&#xE43;&#xE2B;&#xE49;&#xE43;&#xE19; Profile](https://gblobscdn.gitbook.com/assets%2F-MacQbJEhin4rokH3Cup%2F-Mb1B61xAkZ_u3NFpZm4%2F-Mb1DaL15vKIiaRm5bhf%2Fimage.png?alt=media&token=1dfb3743-4d9d-40a2-b03b-9b534ada7330)

## การตั้งค่า OBS สำหรับ CMU EZ Studio Controller <a id="obs-ez-studio"></a>

<table>
  <thead>
    <tr>
      <th style="text-align:left">&#xE0A;&#xE37;&#xE48;&#xE2D;</th>
      <th style="text-align:left">Download</th>
      <th style="text-align:left">&#xE04;&#xE33;&#xE2D;&#xE18;&#xE34;&#xE1A;&#xE32;&#xE22;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">&#xE20;&#xE32;&#xE1E;&#xE1E;&#xE37;&#xE49;&#xE19;&#xE2B;&#xE25;&#xE31;&#xE07;&#xE41;&#xE25;&#xE30;&#xE2A;&#xE31;&#xE0D;&#xE25;&#xE31;&#xE01;&#xE29;&#xE13;&#xE4C;&#xE21;&#xE2B;&#xE32;&#xE27;&#xE34;&#xE17;&#xE22;&#xE32;&#xE25;&#xE31;&#xE22;</td>
      <td
      style="text-align:left"><a href="https://o365cmu-my.sharepoint.com/personal/arnan_s_cmu_ac_th1/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings%2Fobs%2Dpics%2Ezip&amp;parent=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings&amp;originalPath=aHR0cHM6Ly9vMzY1Y211LW15LnNoYXJlcG9pbnQuY29tLzp1Oi9nL3BlcnNvbmFsL2FybmFuX3NfY211X2FjX3RoMS9FY3Y2cG4yZExIbE9wQXJsQWYtMXJCY0JJc3FFVXJ6YklRZ2VtWW5VdDN3OU9nP3J0aW1lPTFWUmRkZzhyMlVn">Download</a>
        </td>
        <td style="text-align:left">
          <p>&#xE20;&#xE32;&#xE1E;&#xE1E;&#xE37;&#xE49;&#xE19;&#xE10;&#xE32;&#xE19;&#xE17;&#xE35;&#xE48;&#xE23;&#xE27;&#xE1A;&#xE23;&#xE27;&#xE21;&#xE44;&#xE27;&#xE49;&#xE40;&#xE1E;&#xE37;&#xE48;&#xE2D;&#xE04;&#xE27;&#xE32;&#xE21;&#xE2A;&#xE30;&#xE14;&#xE27;&#xE01;
            &#xE1B;&#xE23;&#xE30;&#xE01;&#xE2D;&#xE1A;&#xE44;&#xE1B;&#xE14;&#xE49;&#xE27;&#xE22;&#xE2A;&#xE31;&#xE0D;&#xE25;&#xE31;&#xE01;&#xE29;&#xE13;&#xE4C;&#xE21;&#xE2B;&#xE32;&#xE27;&#xE34;&#xE17;&#xE22;&#xE32;&#xE25;&#xE31;&#xE22;&#xE40;&#xE0A;&#xE35;&#xE22;&#xE07;&#xE43;&#xE2B;&#xE21;&#xE48;
            &#xE02;&#xE19;&#xE32;&#xE14;&#xE43;&#xE2B;&#xE0D;&#xE48; &#xE41;&#xE25;&#xE30;&#xE02;&#xE19;&#xE32;&#xE14;&#xE40;&#xE25;&#xE47;&#xE01;
            &#xE20;&#xE32;&#xE1E;&#xE1E;&#xE37;&#xE49;&#xE19;&#xE2B;&#xE25;&#xE31;&#xE07;&#xE17;&#xE35;&#xE48;&#xE1E;&#xE23;&#xE49;&#xE2D;&#xE21;&#xE43;&#xE0A;&#xE49;&#xE07;&#xE32;&#xE19;</p>
          <p>&#x200B;</p>
          <p>&#xE02;&#xE2D;&#xE43;&#xE2B;&#xE49;&#xE15;&#xE34;&#xE14;&#xE15;&#xE31;&#xE49;&#xE07;&#xE44;&#xE1F;&#xE25;&#xE4C;&#xE44;&#xE27;&#xE49;&#xE43;&#xE19;
            folder &#xE0A;&#xE37;&#xE48;&#xE2D; <code>c:/obs-pics</code>
          </p>
        </td>
    </tr>
    <tr>
      <td style="text-align:left">OBS Scene Collection</td>
      <td style="text-align:left"><a href="https://o365cmu-my.sharepoint.com/personal/arnan_s_cmu_ac_th1/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings%2FTLIC%5FEZ%5FStudio%2Ejson&amp;parent=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings&amp;originalPath=aHR0cHM6Ly9vMzY1Y211LW15LnNoYXJlcG9pbnQuY29tLzp1Oi9nL3BlcnNvbmFsL2FybmFuX3NfY211X2FjX3RoMS9FZWJhM21lTGJONUJwX3NTeWtzRGdmSUJhb19kWWJsS01IVkVYVG5MUVdnZi1BP3J0aW1lPTFIeXVTcFlwMlVn">Download</a>
      </td>
      <td style="text-align:left">Scene &#xE2A;&#xE33;&#xE40;&#xE23;&#xE47;&#xE08;&#xE23;&#xE39;&#xE1B;&#xE2A;&#xE33;&#xE2B;&#xE23;&#xE31;&#xE1A;
        OBS &#xE43;&#xE19;&#xE0A;&#xE38;&#xE14;&#xE2A;&#xE32;&#xE21;&#xE32;&#xE23;&#xE16;&#xE40;&#xE25;&#xE37;&#xE2D;&#xE01;&#xE41;&#xE2A;&#xE14;&#xE07;
        &#xE1C;&#xE39;&#xE49;&#xE1E;&#xE39;&#xE14;, &#xE2A;&#xE37;&#xE48;&#xE2D;&#xE19;&#xE33;&#xE40;&#xE2A;&#xE19;&#xE2D;,
        &#xE41;&#xE17;&#xE23;&#xE01;&#xE1C;&#xE39;&#xE49;&#xE1E;&#xE39;&#xE14;&#xE43;&#xE19;&#xE21;&#xE38;&#xE21;&#xE0B;&#xE49;&#xE32;&#xE22;
        &#xE41;&#xE25;&#xE30;&#xE02;&#xE27;&#xE32; &#xE15;&#xE34;&#xE14;&#xE15;&#xE31;&#xE49;&#xE07;&#xE43;&#xE19;
        OBS &#xE42;&#xE14;&#xE22;&#xE40;&#xE25;&#xE37;&#xE2D;&#xE01;&#xE40;&#xE21;&#xE19;&#xE39; <code>Scene Collection / Import</code>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">OBS Profile</td>
      <td style="text-align:left"><a href="https://o365cmu-my.sharepoint.com/personal/arnan_s_cmu_ac_th1/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings%2FEZ%5FStudio%5FProfile%2Ezip&amp;parent=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings&amp;originalPath=aHR0cHM6Ly9vMzY1Y211LW15LnNoYXJlcG9pbnQuY29tLzp1Oi9nL3BlcnNvbmFsL2FybmFuX3NfY211X2FjX3RoMS9FYlh2NFlpOUlzMVBvMzlyT2E1TWVTNEIwS2pQX2VLZ01vRVZtWGxudDNtZ2N3P3J0aW1lPUlIMTRVNVlwMlVn">Download</a>
      </td>
      <td style="text-align:left">
        <p>Profile &#xE17;&#xE35;&#xE48;&#xE15;&#xE31;&#xE49;&#xE07;&#xE04;&#xE48;&#xE32;&#xE04;&#xE35;&#xE22;&#xE4C;&#xE25;&#xE31;&#xE14;&#xE44;&#xE27;&#xE49;&#xE40;&#xE1E;&#xE37;&#xE48;&#xE2D;&#xE43;&#xE0A;&#xE49;&#xE07;&#xE32;&#xE19;&#xE01;&#xE25;&#xE48;&#xE2D;&#xE07;
          EZ Controller &#xE01;&#xE31;&#xE1A; Scene Collection &#xE44;&#xE14;&#xE49;&#xE42;&#xE14;&#xE22;&#xE07;&#xE48;&#xE32;&#xE22;
          &#xE19;&#xE2D;&#xE01;&#xE08;&#xE32;&#xE01;&#xE19;&#xE31;&#xE49;&#xE19;&#xE22;&#xE31;&#xE07;&#xE15;&#xE31;&#xE49;&#xE07;&#xE04;&#xE48;&#xE32;&#xE04;&#xE27;&#xE32;&#xE21;&#xE25;&#xE30;&#xE40;&#xE2D;&#xE35;&#xE22;&#xE14;&#xE02;&#xE2D;&#xE07;&#xE01;&#xE25;&#xE49;&#xE2D;&#xE07;
          Webcam &#xE43;&#xE2B;&#xE49;&#xE40;&#xE1B;&#xE47;&#xE19; Full HD</p>
        <p>&#x200B;</p>
        <p>&#xE15;&#xE34;&#xE14;&#xE15;&#xE31;&#xE49;&#xE07;&#xE43;&#xE19; OBS &#xE42;&#xE14;&#xE22;&#xE40;&#xE25;&#xE37;&#xE2D;&#xE01;&#xE40;&#xE21;&#xE19;&#xE39; <code>Profile / Import</code>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">&#xE42;&#xE1B;&#xE2A;&#xE40;&#xE15;&#xE2D;&#xE23;&#xE4C;&#xE41;&#xE2A;&#xE14;&#xE07;&#xE04;&#xE35;&#xE22;&#xE4C;&#xE25;&#xE31;&#xE14;</td>
      <td
      style="text-align:left"><a href="https://o365cmu-my.sharepoint.com/personal/arnan_s_cmu_ac_th1/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings%2FEz%20Controller%20Key%20Mappings%2Epdf&amp;parent=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings&amp;originalPath=aHR0cHM6Ly9vMzY1Y211LW15LnNoYXJlcG9pbnQuY29tLzpiOi9nL3BlcnNvbmFsL2FybmFuX3NfY211X2FjX3RoMS9FWElMZlVvXzB0Qkx2LWNhZG5GNURvRUJib2VhSVNLTkNoNUNqOHZsWXpydFZBP3J0aW1lPUJMUnhYSllwMlVn">PDF</a>,
        <a
        href="https://o365cmu-my.sharepoint.com/personal/arnan_s_cmu_ac_th1/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings%2Fez%20controller%20key%20mappings%2Epng&amp;parent=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2FOBS%20Settings&amp;originalPath=aHR0cHM6Ly9vMzY1Y211LW15LnNoYXJlcG9pbnQuY29tLzppOi9nL3BlcnNvbmFsL2FybmFuX3NfY211X2FjX3RoMS9FZHpzWDVmX2ptUk1oTkV3VnRoOG1Zd0JSTWFiNUdVSktkSy02MUxSQWkyYTl3P3J0aW1lPXFMNDBaSllwMlVn">PNG</a>
          </td>
          <td style="text-align:left">
            <p>&#xE20;&#xE32;&#xE1E;&#xE41;&#xE2A;&#xE14;&#xE07;&#xE1C;&#xE31;&#xE07;&#xE41;&#xE25;&#xE30;&#xE2B;&#xE19;&#xE49;&#xE32;&#xE17;&#xE35;&#xE48;&#xE02;&#xE2D;&#xE07;&#xE1B;&#xE48;&#xE38;&#xE21;
              EZ Controller &#xE17;&#xE35;&#xE48;&#xE43;&#xE0A;&#xE49;&#xE23;&#xE48;&#xE27;&#xE21;&#xE01;&#xE31;&#xE1A;
              Profile &#xE02;&#xE49;&#xE32;&#xE07;&#xE15;&#xE49;&#xE19;</p>
            <p>&#x200B;</p>
          </td>
    </tr>
  </tbody>
</table>

## การติดตั้ง OBS Studio 

**ดาวน์โหลดได้ที่นี่** : [https://obsproject.com/](https://obsproject.com/)

