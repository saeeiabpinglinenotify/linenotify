# Suprnova Line Notify Version 2.0
- สำคัญมาก : การ์ดจอ AMD ให้ปรับ SHOW_GPU_TEMPERATURE เป็น 0 เท่านั้น

รายละเอียดการอัพเดท Suprnova Line Notify Ver 2.0 (Last update 12-08-2560)
1. เพิ่มฟังชั่น Switch pool 
   - 0 = suprnova
   - 1 = pool.mn
2. เพิ่มฟังชั่นตรวจสอบการเชื่อมต่อกับ API
3. แก้ไขบัคอื่นๆ

วิธีใช้
1. เปิดไฟล์ LineNotify.exe.config โดยใช้ โปรแกรม notepad
2. แก้ไข config ดังนี้
   - 2.1 SWITCH_POOL คือ ต้องการให้แจ้งเตือนสำหรับ Pool อะไร (0 = suprnova / 1 = pool.mn)
   - 2.1 LINE_TOKEN คือ Line Token
   - 2.2 APIKEY คือ Api key ที่ได้จากเว็ป Suprnova หน้า Edit Account
   - 2.3 COIN คือ สกุลเหรียญที่ต้องการให้แจ้งเตือน (ตัวอย่าง sigt)
   - 2.4 TIME คือ ต้องการให้แจ้งเตือนทุกๆกี่นาที //หน่วยเป็นนาที (ตัวอย่าง 5)
   - 2.5 SHOW_GPU_TEMPERATURE คือ ต้องการให้ เปิด/ปิด ตัวโชว์องศา (0 คือปิด / 1 คือเปิด)
3. กด Save
4. ดับเบิ้ลคลิก ที่ไฟล์ LineNotify.exe (รูประฆัง) เพื่อเริ่มการทำงาน
5. Enjoy!!!!
