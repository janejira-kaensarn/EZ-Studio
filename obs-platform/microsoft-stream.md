# Microsoft Stream

Microsoft Stream เป็น Platform สำหรับการถ่ายทอดสดและลง content ประเภทวิดีโอค้ลายกับ YouTube แต่มีข้อแตกต่างที่สำคัญคือสามารถกำหนด Privacy ในการเข้าชมให้เป็นระดับองค์กรหรือรายบุคคลได้ ซึ่งแตกต่างจาก YouTube ที่จะเน้นการเผยแพร่และถ่ายทอดสดในรูปแบบสาธารณะมากกว่า การตั้งค่าสำหรับการ Live Stream บน Microsoft Stream ด้วย OBS มีวิธีการดังนี้

1.Login ใน [https://web.microsoftstream.com/](https://web.microsoftstream.com) (สามารถใช้ cmu Account ได้)

2.ไปที่แถบเมนูมุมซ้ายบน เลือก Create -> Live Event

![](<../.gitbook/assets/image (199) (1) (1) (1).png>)

3.จะเข้าสู่หน้าจอการตั้งค่า Live Stream ให้ทำการใส่รายละเอียดใน Detail , ตั้งค่า Permission และ Options ให้เรียบร้อย จากนั้นกด Save

![](<../.gitbook/assets/image (196) (1) (1) (1).png>)

4.เมื่อกด Save แล้ว ส่วนการตั้งค่าของ Encoder setup จะปรากฏขึ้น ไปที่ส่วนของ Server ingest URL แล้วกด Copy

![](<../.gitbook/assets/image (203) (1).png>)

5.เปิดโปรแกรม OBS ไปที่แถบเครื่องมือบริเวณมุมขวาล่าง เลือกที่ Setting

![](<../.gitbook/assets/image (200).png>)

6.หน้าต่าง Setting จะปรากฏขึ้น เลือกที่ Stream ตั้งค่า Service ตามภาพด้านล่าง ส่วนช่อง Server ให้กด Ctrl + V หรือคลิกขวา + Paste เพื่อวาง Server ingest URL ที่คัดลอกมาจากหน้าตั้งค่าของ Microsoft Stream ลงไป และช่อง Stream Key ให้พิมพ์ 123456 จากนั้นกด OK

![](<../.gitbook/assets/image (198) (1) (1).png>)

7.ไปที่ Microsoft Stream คลิกที่ปุ่ม Start setup(สีเหลือง) จากนั้นรอระบบเชื่อมต่อกับ OBS

![](<../.gitbook/assets/image (201) (1).png>)

8.เมื่อระบบเชื่อมต่อกับ OBS เสร็จเรียบร้อย จะขึ้นเป็นหน้าจอดังกล่าว ให้ไปที่ OBS กด Start Streaming&#x20;

![](<../.gitbook/assets/image (204) (1) (1).png>)

9.หน้า Microsoft Stream จะแสดงตัวอย่างหน้าจอระหว่างถ่ายทอดสดขึ้นมาให้ พร้อมข้อความแจ้งเตือนว่าระบบพร้อมสำหรับการถ่ายทอดสดแล้วที่ด้านบนปุ่ม Start event เมื่อพร้อมแล้วสามารถกดที่ Start event ได้ทันที

และเมื่อต้องการหยุดการถ่ายทอดสดให้กดที่ Stop Streaming ใน OBS และกดปุ่ม End event(ปุ่มสีชมพู ตำแหน่งเดียวกับ Start event)ที่หน้า Microsoft Stream

![เมื่อระบบพร้อมสำหรับการถ่ายทอดสดจะเห็นข้อความแจ้งเตือนขึ้นมาดังภาพ](<../.gitbook/assets/image (197) (1) (1).png>)

![เมื่อกด End event จะมีข้อความแจ้งเเตือนการหยุดการถ่ายทอดสดขึ้นมา](<../.gitbook/assets/image (202) (1).png>)

10.สามารถเข้าไปจัดการรายละเอียดหรือตัดวิดีโอส่วนที่ไม่ต้องการออกได้ในภายหลัง โดยเข้าไปที่ My content -> Videos
