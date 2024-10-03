---
description: >-
  เวอร์ชันปัจจุบันคือ เวอร์ชันที่ 3
  สามารถใช้งานได้โดยไม่ต้องทำการติดตั้งโปรแกรมใดๆเหมือนกับ เวอร์ชันที่ 1 และ 2
---

# คู่มือการใช้เครื่อง CMU EZ Studio Controller

![](<../../../.gitbook/assets/1 (1).png>)

เครื่อง **CMU EZ Studio Controller** เป็นอุปกรณ์ที่ช่วยอำนวยความสะดวกในการควบคุมและเปลี่ยนแปลงหน้าจอการทำงานเพียงกดปุ่มแหล่งสัญญาณที่ได้ตั้งค่าไว้เท่านั้น โดยไม่ต้องทำการตัดต่อ&#x20;

เครื่อง **CMU EZ Studio Controller** นั้นมีทั้งหมด 3 Versions ด้วยกัน โดยใน Version ที่ 1 และ 2 จะต้องทำการ Setting เพิ่มเติมก่อนเริ่มใช้งาน แต่ใน Version ที่ 3 นั้น เป็นรุ่นที่ได้รับการพัฒนามาอย่างต่อเนื่อง จนสามารถที่จะทำงานได้ทันที่โดยไม่ต้องทำการตั้งค่าใดๆ&#x20;

## รายละเอียดส่วนต่างๆ ของเครื่อง **EZ Controller (Version 3.0)**

![](<../../../.gitbook/assets/image (40).png>)

**คุณสมบัติของ EZ-Controller (Version 3.0)**

* มีปุ่มขนาดใหญ่สำหรับการ เริ่ม/หยุด บันทึก, สลับ Source หลัก (เช่น Video หน้าอาจารย์ กับ สื่อนำเสนอ)
* มีปุ่มย่อย 4 ปุ่มให้ตั้งค่าใช้งานได้ในกรณีที่ต้องการปุ่มเพิ่มเติม
* เสียบใช้งานผ่านพอร์ท USB โดยจะปรากฏตัวเป็นแป้นพิมพ์ ใช้งานได้ทันที ไม่ต้องติดตั้งโปรแกรมเสริมใดๆ
* สามารถตั้งค่าของปุ่มได้ผ่านทางโปรแกรมจัดการ

## การใช้งาน  EZ Controller Version 1.0, 2.0 (Version เก่า)

&#x20;         Ez-Controller ตั้งค่าเริ่มต้นมาเพื่อใช้กับโปรแกรม [Logitech Capture](https://www.logitech.com/th-th/product/capture) ซึ่งเป็นโปรแกรมบันทึกสื่อที่ใช้งานได้ง่าย และเป็นโปรแกรมมาตรฐานในชุด [CMU Ez-Studio](https://tlic.cmu.ac.th/cmuezstudio/)  โดยแต่ละปุ่มบน Ez-Controller จะทำหน้าที่ดังนี้

![](https://tlic.cmu.ac.th/wp-content/uploads/2020/05/ez\_studio\_v3-logi-capture-mapping-808x1024.png)

* ปุ่ม Record – Start/Stop Recording
* ปุ่ม Source 1 – Scene 1
* ปุ่ม Source 2 – Scene 2
* ปุ่ม A – Scene 1 ย่อภายใน Scene 2 (PIP)
* ปุ่ม B – Scene 2 ย่อภายใน Scene 1 (PIP)
* ปุ่ม C – Scene 1 และ Scene 2 แบ่งครึ่งโดย Scene 1 อยู่ทางซ้าย
* ปุ่ม D – Scene 2 และ Scene 1 แบ่งครึ่งโดย Scene 2 อยู่ทางซ้าย

## การใช้งานร่วมกับโปรแกรมอื่น

&#x20;         แม้ Ez-Controller ตั้งค่าเริ่มต้นไว้สำหรับโปรแกรม Logitech Capture แต่ก็สามารถนำไปใช้งานกับโปรแกรมอื่นใดๆ ที่รองรับการใช้ Keyboard Shortcut ในการควบคุม Ez-Controller จำลองตัวเองเป็นแป้นพิมพ์และแต่ละปุ่มส่งคีย์ออกมาตามรายการต่อไปนี้

* ปุ่ม Record – ALT+R
* ปุ่ม Source 1 – ALT+1
* ปุ่ม Source 2 – ALT+2
* ปุ่ม A – ALT+3
* ปุ่ม B – ALT+4
* ปุ่ม C – ALT+5
* ปุ่ม D – ALT+6

### ตัวอย่างการใช้งานกับโปรแกรม OBS

&#x20;         หากต้องการใช้งาน CMU EZ Studio Controller กับโปรแกรม [Open Broadcaster Software (OBS)](https://obsproject.com/) ก็สามารถใช้ประโยชน์จากความสามารถการกำหนดคีย์ลัดของ OBS เพื่อกำหนดว่าปุ่มใดบน CMU EZ Studio Controller จะทำหน้าที่อะไรใน OBS ดังแสดงในภาพ

![](https://tlic.cmu.ac.th/wp-content/uploads/2020/05/obs-shortcut-keys.png)

## การเปลี่ยนค่าคีย์ของ CMU EZ Studio

&#x20;         หากจำเป็นต้องเปลี่ยนคีย์ที่ถูกส่งออกมาจากปุ่มของ EZ Studio Controller ก็สามารถใช้โปรแกรม Configuration Tool ในการปรับแต่งได้  ซึ่งการใช้งาน Configuration Tool จำเป็นต้องมีภาษา Python  ติดตั้งอยู่ในเครื่อง และมีความรู้ในการเรียกใช้ผ่าน command line

**สามารถดาวน์โหลดได้ที่นี่ :** [Configuration Tool ](https://o365cmu-my.sharepoint.com/personal/arnan\_s\_cmu\_ac\_th1/\_layouts/15/onedrive.aspx?id=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2Fconfig%20tool%2Fconfig%2Dtool%2Epy\&parent=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2Fconfig%20tool\&originalPath=aHR0cHM6Ly9vMzY1Y211LW15LnNoYXJlcG9pbnQuY29tLzp1Oi9nL3BlcnNvbmFsL2FybmFuX3NfY211X2FjX3RoMS9FZmF0ZnFRaF9VdE9yb1JXVFNVSy1YVUJfakg5UlJabDRCdk5ERHRlc0Z0QVp3P3J0aW1lPV9kS283TzdzMkVn)
