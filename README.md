# Suprnova Line Notify Ver 1.1
- สำคัญมาก : ยังไม่ได้ทดสอบกับการ์ดจอ AMD
- สำคัญมาก : การ์ดจอ AMD ให้ปรับ SHOW_GPU_TEMPERATURE เป็น 0 เท่านั้น

วิธีใช้
1. เปิดไฟล์ LineNotify.exe.config โดยใช้ โปรแกรม notepad
2. แก้ไข config ดังนี้
   - 2.1 LINE_TOKEN คือ Line Token
   - 2.2 SUPRNOVA_APIKEY คือ Api key ที่ได้จากเว็ป Suprnova หน้า Edit Account
   - 2.3 SUPRNOVA_COIN คือ สกุลเหรียญที่ต้องการให้แจ้งเตือน (ตัวอย่าง sigt)
   - 2.4 SUPRNOVA_TIME คือ ต้องการให้แจ้งเตือนทุกๆกี่นาที //หน่วยเป็นนาที (ตัวอย่าง 5)
   - 2.5 SHOW_GPU_TEMPERATURE คือ ต้องการให้ เปิด/ปิด ตัวโชว์องศา (0 คือปิด / 1 คือเปิด)
3. กด Save
4. ดับเบิ้ลคลิก ที่ไฟล์ LineNotify.exe (รูประฆัง) เพื่อเริ่มการทำงาน
Enjoy!!!!
