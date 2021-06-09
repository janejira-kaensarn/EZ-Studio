---
description: >-
  การใช้งานCMU EZ Studio Controller ใน Version เก่า (Version 1.0 และ 2.0)
  จะต้องทำการติดตั้งโปรแกรมที่จำเป็น และทำการตั้งค่าก่อนเริ่มใช้งาน
---

# Version 1.0, 2.0 \(Version เก่า\)

## การใช้งาน CMU EZ Studio Controller Version 1.0, 2.0 \(Version เก่า\)

           CMU EZ Studio Controller  ตั้งค่าเริ่มต้นมาเพื่อใช้กับโปรแกรม [Logitech Capture](https://www.logitech.com/th-th/product/capture) ซึ่งเป็นโปรแกรมบันทึกสื่อที่ใช้งานได้ง่าย และเป็นโปรแกรมมาตรฐานในชุด CMU EZ Studio Controller โดยแต่ละปุ่มบน  CMU EZ Studio Controller จะทำหน้าที่ดังนี้

![](https://tlic.cmu.ac.th/wp-content/uploads/2020/05/ez_studio_v3-logi-capture-mapping-808x1024.png)

* ปุ่ม Record – Start/Stop Recording
* ปุ่ม Source 1 – Scene 1
* ปุ่ม Source 2 – Scene 2
* ปุ่ม A – Scene 1 ย่อภายใน Scene 2 \(PIP\)
* ปุ่ม B – Scene 2 ย่อภายใน Scene 1 \(PIP\)
* ปุ่ม C – Scene 1 และ Scene 2 แบ่งครึ่งโดย Scene 1 อยู่ทางซ้าย
* ปุ่ม D – Scene 2 และ Scene 1 แบ่งครึ่งโดย Scene 2 อยู่ทางซ้าย

## การใช้งานร่วมกับโปรแกรมอื่น

          แม้ CMU EZ Studio Controller  ตั้งค่าเริ่มต้นไว้สำหรับโปรแกรม Logitech Capture แต่ก็สามารถนำไปใช้งานกับโปรแกรมอื่นใดๆ ที่รองรับการใช้ Keyboard Shortcut ในการควบคุม CMU EZ Studio Controller จำลองตัวเองเป็นแป้นพิมพ์และแต่ละปุ่มส่งคีย์ออกมาตามรายการต่อไปนี้

* ปุ่ม Record – ALT+R
* ปุ่ม Source 1 – ALT+1
* ปุ่ม Source 2 – ALT+2
* ปุ่ม A – ALT+3
* ปุ่ม B – ALT+4
* ปุ่ม C – ALT+5
* ปุ่ม D – ALT+6

### ตัวอย่างการใช้งานกับโปรแกรม OBS

          หากต้องการใช้งาน CMU EZ Studio Controller  กับโปรแกรม [Open Broadcaster Software \(OBS\)](https://obsproject.com/) ก็สามารถใช้ประโยชน์จากความสามารถการกำหนดคีย์ลัดของ OBS เพื่อกำหนดว่าปุ่มใดบน CMU EZ Studio Controller จะทำหน้าที่อะไรใน OBS ดังแสดงในภาพ

![](https://tlic.cmu.ac.th/wp-content/uploads/2020/05/obs-shortcut-keys.png)

## การเปลี่ยนค่าคีย์ของ CMU EZ Studio Controller 

          หากจำเป็นต้องเปลี่ยนคีย์ที่ถูกส่งออกมาจากปุ่มของ CMU EZ Studio Controller  ก็สามารถใช้โปรแกรม Configuration Tool ในการปรับแต่งได้  ซึ่งการใช้งาน config-tool จำเป็นต้องมีภาษา Python  ติดตั้งอยู่ในเครื่องและมีความรู้ในการเรียกใช้ผ่าน command line

**สามารถดาวน์โหลดได้ที่นี่ :** [Configuration Tool ](https://o365cmu-my.sharepoint.com/personal/arnan_s_cmu_ac_th1/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2Fconfig%20tool%2Fconfig%2Dtool%2Epy&parent=%2Fpersonal%2Farnan%5Fs%5Fcmu%5Fac%5Fth1%2FDocuments%2FITSC%2FTLIC%2FEz%20Studio%2Fconfig%20tool&originalPath=aHR0cHM6Ly9vMzY1Y211LW15LnNoYXJlcG9pbnQuY29tLzp1Oi9nL3BlcnNvbmFsL2FybmFuX3NfY211X2FjX3RoMS9FZmF0ZnFRaF9VdE9yb1JXVFNVSy1YVUJfakg5UlJabDRCdk5ERHRlc0Z0QVp3P3J0aW1lPV9kS283TzdzMkVn)

