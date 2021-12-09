# Zoom

สำหรับการใช้การ OBS กับ Zoom นั้นจะช่วยให้การบรรยาย การนำเสนอผลงาน หรือการประชุมนั้นง่ายขึ้น จากการใช้ความสามารถที่มีอยู่ของ OBS ในการ Live Stream โดยการทำงานร่วมกันกับ Zoom นั้น OBS จะใช้สิ่งที่เรียกว่า "กล้องจำลอง" หรือ Virtual Camera แทนกล้องเว็บแคมปกติ ซึ่งการตั้งค่าสำหรับการใช้ OBS บน Zoom มีวิธีการดังนี้

1.เปิดโปรแกรม OBS กดที่ Start Virtual Camera ที่บริเวณแถบเมนูด้านขวาล่าง เพื่อเปิดใช้งาน

![](<../.gitbook/assets/image (208).png>)

2.ไปที่ Tool -> VirtualCam หน้าต่าง VirtualCam จะปรากฏขึ้น เลือก Target Camera เป็น OBS-Camera จากนั้นกด Start

![](<../.gitbook/assets/image (199).png>)

3.Login เข้าใช้งาน Zoom (สามารถใช้ cmu account ได้) และทำการเข้าสู่ Meeting

4.ทำการ Start Video จากนั้นกดที่ ^ ข้างปุ่ม Start Video -> Video Setting หน้าต่างการตั้งค่าจะปรากฏขึ้น

![](<../.gitbook/assets/image (209).png>)

4.ตั้งค่าส่วนของ Video ที่ Camera ให้เลือกกล้องเป็น OBS Virtual Camera เมื่อระบบเชื่อมต่อการใช้งานสำเร็จ ภาพวิดีโอตัวอย่างจะปรากฏขึ้น กดปิดหน้าต่าง Setting และเข้าไปใช้งานที่ OBS ได้ทันที

![](<../.gitbook/assets/image (197).png>)

9.เมื่อต้องการปิดการใช้งาน OBS ให้กด Stop Virtual Camera ทั้งสองตำแหน่งใน OBS และ Stop Video หรือเปลี่ยนเป็นกล้องเว็บแคมตามปกติใน Zoom เป็นอันเสร็จเรียบร้อย

![กด Stop VirtualCam ที่หน้าต่าง VirtualCam ของ OBS](<../.gitbook/assets/image (206) (1).png>)

![กด Stop Virtual Camera ที่แถบเมนูมุมขวาล่างของ OBS](<../.gitbook/assets/image (198).png>)

![ใน Zoom กด Stop Video หรือ ^ เพื่อเปลี่ยนเป็นกล้องเว็บแคมปกติ](<../.gitbook/assets/image (196) (1).png>)

{% hint style="info" %}
**ควรปิดการใช้งาน Virtual Camera ใน OBS และ Zoom ให้เรียบร้อย ไม่แนะนำให้ปิดเฉพาะแค่อย่างใดอย่างหนึ่ง**
{% endhint %}
