# OBS x Microsoft Teams

การใช้งาน OBS กับ Microsoft Teams นั้นจะเป็นการใช้งานระหว่างการ Meeting ซึ่งจะช่วยให้การบรรยาย การนำเสนอผลงาน หรือการประชุมนั้นง่ายขึ้น จากการใช้ความสามารถที่มีอยู่ของ OBS ในการ Live Stream โดยการทำงานร่วมกันกับ Microsoft Teams นั้น OBS จะใช้สิ่งที่เรียกว่า "กล้องจำลอง" หรือ Virtual Camera แทนกล้องเว็บแคมปกติเช่นเดียวกันกับการใช้งาน OBS กับ Zoom  ซึ่งการตั้งค่าสำหรับการใช้ OBS บน Microsoft Teams มีวิธีการดังนี้

1.เปิดโปรแกรม OBS กดที่ Start Virtual Camera ที่บริเวณแถบเมนูด้านขวาล่าง เพื่อเปิดใช้งาน

![](<../../.gitbook/assets/image (208) (1) (1).png>)

2.ไปที่ Tool -> VirtualCam หน้าต่าง VirtualCam จะปรากฏขึ้น เลือก Target Camera เป็น OBS-Camera จากนั้นกด Start

![](<../../.gitbook/assets/image (199) (1).png>)

3.Login เข้าใช้งาน Microsoft Teams (สามารถใช้ cmu account ได้) และทำการเข้าสู่ Meeting

4.เปิดใช้งานกล้องและเลือกที่เครื่องหมายฟันเฟือง แถบ Device Setting จะปรากฏขึ้น เลือกส่วนของ Camera ให้เป็น OBS Virtual Camera

![เปิดใช้งานกล้อง(ด้านซ้าย)และเลือกที่เครื่องหมายฟันเฟือง(ด้านขวา)](<../../.gitbook/assets/image (212) (1) (1).png>)

![เลือกส่วนของ Camera ให้เป็น OBS Virtual Camera](<../../.gitbook/assets/image (215) (1).png>)

5.เมื่อระบบเชื่อมต่อการใช้งานสำเร็จ ภาพวิดีโอตัวอย่างจะปรากฏขึ้นที่ด้านซ้าย กด Join Now เพื่อทำการเข้าสู่ Meeting

![](<../../.gitbook/assets/image (209) (1).png>)

6.จะสังเกตเห็นได้ว่าภาพจาก OBS Virtual Camera ที่ถูกเปิดใน Meeting จะถูกกลับด้าน ให้เข้าไปที่โปรแกรม OBS ไปที่ Scene และ Source ที่ต้องการ -> คลิกขวาที่ Source -> Transform -> Flip Horizontal ภาพใน OBS จะถูกกลับด้าน ส่วนภาพที่ถูกแชร์ขึ้นไปใน Microsoft Teams จะแสดงผลเป็นด้านที่ถูกต้อง

![https://answers.microsoft.com/ko-kr/msteams/forum/all/ms-teams-%ED%99%94%EC%83%81%ED%9A%8C%EC%9D%98/525217e6-6de4-43dc-a975-2698d60f5dec](<../../.gitbook/assets/image (214) (1).png>)

![ภาพใน OBS จะถูกกลับด้าน กรณีที่เปิดใช้งานแบบ Studio Mode อย่าลืมกด Transition เพื่อนำการตั้งค่าปัจจุบันเข้าสู่การถ่ายทอดสด](<../../.gitbook/assets/image (211) (1).png>)

![ภาพบน Microsoft Teams Meeting จะถูกปรับให้แสดงผลด้านที่ถูกต้อง](<../../.gitbook/assets/image (208) (1).png>)



7.เมื่อต้องการปิดการใช้งาน OBS ให้กด Stop Virtual Camera ทั้งสองตำแหน่งใน OBS และ ปิดกล้องด้วปุ่มบริเวณมุมขวาบนหรือเปลี่ยนเป็นกล้องเว็บแคมตามปกติใน Microsoft Teams ด้วยปุ่ม More Options(ปุ่มจุดสามจุด) -> Device settings -> Camera -> เลือกกล้องที่ต้องการ เป็นอันเสร็จเรียบร้อย

![กด Stop VirtualCam ที่หน้าต่าง VirtualCam ของ OBS](<../../.gitbook/assets/image (206) (1) (1).png>)

![กด Stop Virtual Camera ที่แถบเมนูมุมขวาล่างของ OBS](<../../.gitbook/assets/image (198).png>)

![ใน Meeting กดปิดกล้อง](<../../.gitbook/assets/image (210) (1).png>)

![เปลี่ยน Camera เป็นเว็บแคมปกติ](<../../.gitbook/assets/image (202) (1).png>)
