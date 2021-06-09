---
description: >-
  โปรแกรมที่จะช่วยให้สื่อของท่านมีพื้นหลังที่สวยงามโดยไม่ต้องใช้ Green Screen
  มาพร้อมกับระบบตัดเสียงรบกวนที่จะช่วยให้สื่อของท่าน
  ดูมีความเป็นมืออาชีพมากยิ่งขึ้น
---

# NVIDIA Broadcast

## ⭐ แนะนำ NVIDIA Broadcast

{% embed url="https://www.youtube.com/watch?v=0p9nc11wya0" caption="แนะนำ NVIDIA Broadcast" %}

## **NVIDIA Broadcast** คืออะไร?

**NVIDIA Broadcast** เป็นซอฟต์แวร์ใหม่สำหรับการสตรีมเกม, ถ่ายทอดสด, หรือ จัดประชุมออนไลน์ **โดยไม่ต้องลงทุนอุปกรณ์**อย่าง ไมโครโฟนคุณภาพสูง, ห้องเก็บเสียง, หรือฉากหลัง **แต่ใช้ปัญญาประดิษฐ์\(AI\)เฉพาะ ที่เรียกว่า "Tensor Core"** บน GeForce RTX GPU ซึ่งเครือข่าย AI จะสามารถเรียกใช้เอฟเฟกต์คุณภาพสูงแบบเรียลไทม์ เข้ามาประมวลผลภาพและเสียงแทน โดยมี 3 ฟีเจอร์ได้แก่

1. **ตัดเสียงรบกวน : NVIDIA Broadcast** จะตัดเสียงรบกวนให้เหลือแต่เสียงพูด โดยตัดได้ทั้งเสียงมอเตอร์ \(ไดร์เป่าผม\), เสียงกดคีย์บอร์ด, เสียงรถ, เสียงหมาเห่า, เสียงคลิ๊กเม้าส์ หรือแม้แต่เสียงกริ่งบ้าน รวมถึงสามารถตัดเสียงจากอินพุต \(Input\) เช่น เสียงของเพื่อนที่กำลังร่วมสตรีมไปพร้อมกัน 
2. **ฉากหลังเสมือน : NVIDIA Broadcast** จะเบลอฉากหลังเพื่อซ่อนความรกของบ้าน หรือ ท่านสามารถเปลี่ยนไปใช้ภาพฉากหลังอื่นได้ ไปจนถึงการใช้สตรีมหน้าจอเป็นฉากหลังได้อีกด้วย 
3. **แพนภาพอัตโนมัติ : NVIDIA Broadcast** จะทำการซูมภาพจากกล้องเว็บแคมแล้วใช้ปัญญาประดิษฐ์ \(AI\)เลือกโซนที่จะซูมตามใบหน้า ทำให้เหมือนมีตากล้องแพนภาพตามความเคลื่อนไหวของท่านแบบเรียลไทม์ รวมทั้งทำการครอปและซูมภาพโดยอัตโนมัติ ให้ท่านยังคงโดดเด่น แม้ว่าท่านจะเคลื่อนไหวไปรอบๆก็ตจาม

**NVIDIA Broadcast** นั้นสามารถทำงานร่วมกับระบบสตรีมยอดนิยมได้หลากหลาย เช่น OBS, Stream labs, Twitch Studio, และ XSplit หรือแม้แต่ระบบประชุมออนไลน์อย่าง Zoom หรือ Discord สามารถใช้งานกับการ์ด GeForce RTX, TITAN RTX, หรือ Quadro RTX รุ่นใดก็ได้ 

![](../../.gitbook/assets/image%20%28164%29.png)

## การตั้งค่า NVIDIA Broadcast

### **1.** ตั้งค่า NVIDIA Broadcast

1. เปิดแอป NVIDIA Broadcast
2. ไปที่อุปกรณ์แต่ละตัว แล้วเลือกอุปกรณ์อินพุตที่บริเวณด้านบน
3. เลือกเอฟเฟกต์ที่ท่านต้องการใช้สำหรับกล้อง
4. ท่านสามารถเปิดหรือปิดสวิตช์ได้ \(ขอแนะนำให้ท่านเปิดเฉพาะสิ่งที่ท่านจะใช้ เพื่อหลีกเลี่ยงการใช้ทรัพยากรที่มากเกินจำเป็น\)
5. หากจำเป็น ท่านสามารถกำหนดค่าความแรงหรือการตั้งค่าเอฟเฟกต์ได้โดยใช้แถบเลื่อนด้านล่าง

![](https://www.nvidia.com/content/dam/en-zz/Solutions/geforce/news/broadcast-app-setup-guide/RBX.png)

### **2**. กำหนดค่าแอปสตรีมสดหรือการประชุมทางวิดีโอของท่าน

1. เปิดแอปที่ท่านต้องการใช้
2. ไปที่การตั้งค่า แล้วไปที่ส่วนของเสียงและวิดีโอ
3. เลือกอุปกรณ์ NVIDIA Broadcast
4. ไมโครโฟน \(NVIDIA Broadcast\)
5. ลำโพง \(NVIDIA Broadcast\)
6. กล้อง \(NVIDIA Broadcast\)

![](https://www.nvidia.com/content/dam/en-zz/Solutions/geforce/news/broadcast-app-setup-guide/Discord-2.png)

### 3. การตั้งค่าขั้นสูง

* **หลีกเลี่ยงปัญหาเกี่ยวกับตัวกรองของบุคคลที่สาม** 

         บางครั้งแอปพลิเคชันสามารถใช้เอฟเฟกต์ เช่น การตัดเสียงรบกวน ซึ่งคล้ายกับใน NVIDIA Broadcast การใช้เอฟเฟกต์ซ้ำซ้อนมักจะทำให้เอฟเฟกต์ทำงานไม่ถูกต้อง _ขอแนะนำให้ปิดใช้งานเอฟเฟกต์ดังกล่าวในแอปและไดร์เวอร์ของท่านเพื่อป้องกันการทำงานผิดพลาดซึ่งเกิดจากการทำงานซ้ำซ้อนของเอฟเฟกต์_

* **การเปลี่ยนความละเอียด** 

        หากท่านต้องการปรับความละเอียดของกล้อง ท่านต้องทำด้วย NVIDIA Broadcast ในแอปสตรีม หรือ การประชุมทางวิดีโอ และ_ควรตั้งค่าเป็นค่าเริ่มต้นหรือตั้งค่าให้ตรงกับการตั้งค่า NVIDIA Broadcast ของท่าน_

* **หากท่านเชื่อมต่อ/ยกเลิกการเชื่อมต่อไมโครโฟน/ลำโพงบ่อยครั้ง** 

         หากท่านเปลี่ยนไมโครโฟนหรือลำโพงบ่อย ๆ \(เช่น เสียบและถอดปลั๊กบ่อยๆ\) _ท่านสามารถตั้งค่าอุปกรณ์เริ่มต้น เป็นอินพุตของท่านใน NVIDIA Broadcastได้_  ซึ่งจะทำให้ท่านไม่ต้องทำการตั้งค่าใหม่ทุกครั้งที่มีการเชื่อมต่อ โดยการตั้งค่านี้จะใช้ไมโครโฟนหรือลำโพงใด ๆ ที่ Windows ตรวจพบเป็นค่าเริ่มต้นใหม่โดยอัตโนมัติ ท่านจึงไม่ต้องกำหนดค่าใหม่ทุกครั้ง

* **การตั้งค่า NVIDIA Broadcast เป็นไมโครโฟนเริ่มต้น** 

        ท่านสามารถเลือก NVIDIA Broadcast เป็นไมโครโฟนเริ่มต้นของท่านใน Windows เพื่อที่ท่านจะได้ไม่ต้องเปลี่ยนในทุกแอปพลิเคชัน โดยตรวจสอบให้แน่ใจว่าท่านได้เลือกไมโครโฟนที่ท่านใช้จริงใน NVIDIA Broadcast  

## วิธีการทดสอบความพร้อมของอุปกรณ์

**NVIDIA Broadcast** มีฟีเจอร์การทดสอบที่ฝังอยู่ในตัวแอป แบ่งเป็นการทดสอบอุปกรณ์หลัก 3 แบบดังนี้

### 1. ไมโครโฟน

          หากต้องการทดสอบไมโครโฟนของท่าน ให้ลองบันทึกเสียงตนเอง ว่าขณะพูดนั้นมีเสียงรบกวนรอบข้างหรือไม่ ท่านสามารถเล่นไฟล์เสียงของท่าน พร้อมกับเปิดหรือปิดเอฟเฟกต์ รวมทั้งปรับความแรงของเอฟเฟกต์ได้ เพื่อดูว่าเอฟเฟกต์นั้นเปลี่ยนเสียงรบกวนและเสียงพูดของท่านอย่างไร

### 2. ลำโพง

         หากต้องการทดสอบลำโพงของท่าน  **NVIDIA Broadcast** นั้นได้รวมเสียงบันทึกหลายรายการที่ท่านสามารถลองฟังในขณะที่เปิดหรือปิดเอฟเฟกต์เพื่อดูความเปลี่ยนแปลงไว้ให้แล้ว  นอกจากนี้ ท่านยังสามารถปรับความแรงของเอฟเฟกต์ได้อีกด้วย

### 3. กล้องเว็บแคม

         หากต้องการทดสอบเว็บแคมของท่าน ท่านสามารถใช้หน้าต่างแสดงตัวอย่างเพื่อทดสอบการติดตามความเคลื่อนไหวตามที่ท่านได้ตั้งค่าไว้

## การทำงานร่วมกับแอปอื่นๆ

### Zoom

**1.** หากต้องการกำหนดค่าแอปพลิเคชันเดสก์ท็อป ให้ไปที่ Settings ⚙ &gt; Audio Settings

![](https://www.nvidia.com/content/dam/en-zz/Solutions/geforce/news/broadcast-app-setup-guide/Zoom-1.jpg)

**2.** เลือก **NVIDIA Broadcast** เป็น Speaker และ Microphone ของท่าน

![](https://www.nvidia.com/content/dam/en-zz/Solutions/geforce/news/broadcast-app-setup-guide/Zoom-2.png)

**3.** ไปที่ Video แล้วเลือก **Camera \(NVIDIA Broadcast\)**

ท่านยังสามารถกำหนดค่าอุปกรณ์ของท่านภายในการประชุมได้

1. คลิกที่ลูกศรเล็ก ๆ ในตัวเลือกด้านล่างซ้าย
2. เลือก **NVIDIA Broadcast** Microphone and Speakers เป็นอุปกรณ์ของท่าน

![](https://www.nvidia.com/content/dam/en-zz/Solutions/geforce/news/broadcast-app-setup-guide/Zoom-3.png)

**3.** ทำเช่นเดียวกันในตัวเลือก Video \(ตัวเลือกที่สองด้านล่างซ้าย\) เพื่อเลือก **Camera \(NVIDIA Broadcast\)**

### 

### Microsoft Teams

**1.** คลิกที่ไอคอนบัญชีของท่านบริเวณด้านบนขวา แล้วเลือก Settings ⚙ 

![](https://www.nvidia.com/content/dam/en-zz/Solutions/geforce/news/broadcast-app-setup-guide/Teams-1.jpg)

**2.** ไปที่เมนู **Devices** &gt; Audio devices &gt; **Custom Setup**

**3.** กำหนดค่า **NVIDIA Broadcast** เป็นอุปกรณ์ของท่าน

![](https://www.nvidia.com/content/dam/en-zz/Solutions/geforce/news/broadcast-app-setup-guide/Teams-2.png)

### 

### Skype

**1.** คลิกที่ Settings ⚙ แล้วไปที่ Audio & Video

**2.** เลื่อนไปที่บริเวณด้านล่างและเปลี่ยนอุปกรณ์ให้เป็น **NVIDIA Broadcast**

![](https://www.nvidia.com/content/dam/en-zz/Solutions/geforce/news/broadcast-app-setup-guide/Skype-1.png)

### 

### Google Chrome

1. ไปที่ Settings ⚙
2. ไปที่เมนู Site Settings &gt; Microphone
3. เลือก **Microphone \(NVIDIA Broadcast\)**
4. กลับไปที่ Site Settings แล้วไปที่ Site Settings &gt; Site Settings &gt; Camera
5. เลือก **Camera \(NVIDIA Broadcast\)**

![](https://www.nvidia.com/content/dam/en-zz/Solutions/geforce/news/broadcast-app-setup-guide/Chrome-1.png)

### 

### OBS Studio

**1.** ไปที่ Settings ⚙ &gt; Audio

![](https://www.nvidia.com/content/dam/en-zz/Solutions/geforce/news/broadcast-app-setup-guide/OBS-1.jpg)

**2.** เลือก NVIDIA Broadcast เป็นอุปกรณ์ของท่าน

1. ใน Devices &gt; Mic/Auxiliary Audio ให้เลือก **Microphone \(NVIDIA Broadcast\)**
2. ใน Advanced &gt; Monitoring Device ให้เลือก **Speakers \(NVIDIA Broadcast\)**

![](https://www.nvidia.com/content/dam/en-zz/Solutions/geforce/news/broadcast-app-setup-guide/OBS-2.png)

**3.** หากต้องการเลือก NVIDIA Broadcast Camera ให้เพิ่ม Video Capture Source ในฉากของท่าน แล้วเลือก **Camera \(NVIDIA Broadcast\)** และปล่อยให้การตั้งค่าทั้งหมดเป็นค่าเริ่มต้น หากท่านต้องการเปลี่ยนความละเอียดของกล้อง ท่านต้องทำด้วย **NVIDIA Broadcast**

## การติดตั้ง **NVIDIA Broadcast** 

**ดาวน์โหลดได้ที่นี่** : [https://www.nvidia.com/en-us/geforce/broadcasting/broadcast-app/](https://www.nvidia.com/en-us/geforce/broadcasting/broadcast-app/)

### คุณสมบัติของเครื่องคอมพิวเตอร์ที่ต้องการ

| **หัวข้อ** | รายละเอียด |
| :--- | :--- |
| **GPU** | NVIDIA GeForce RTX 2060, Quadro RTX 3000, TITAN RTX หรือสูงกว่า |
| **RAM** | RAM 8GB หรือสูงกว่า |
| **CPU** | แนะนำ Intel Core i5 8600, AMD Ryzen r5 2600 หรือสูงกว่า |
| **ไดร์เวอร์** | [ไดร์เวอร์แสดงผล NVIDIA](https://www.nvidia.com/Download/index.aspx?lang=en-us) เวอร์ชัน 456.xx หรือสูงกว่า |
| **ระบบปฏิบัติการ** | Windows 10 64 บิต |
| **การเชื่อมต่อ** | การเชื่อมต่ออินเทอร์เน็ตระหว่างการติดตั้ง |

{% hint style="info" %}
เมื่อทำการติดตั้งแล้วโปรด Restart เครื่องคอมพิวเตอร์ของท่าน เพื่อเริ่มต้นการใช้งาน
{% endhint %}

