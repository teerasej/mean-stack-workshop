# Mongoose module labs
1. สร้าง โปรเจค express ใหม่ด้วย Express Generator
  - ติดตั้ง mongoose module `npm install mongoose --save`
  - ติดตั้ง mongodb module `npm install mongodb --save`
  - ติดตั้ง module อื่นๆ ที่เหลือ (hint: `npm install)

2. สร้างระบบเพิ่มข้อมูลเข้า MongoDB ดังนี้
  1. สร้าง Schema สำหรับ Collection 'hospital' ตามรายละเอียดด้านล่าง
  2. สร้าง `views/index.jade` สำหรับ แสดง hospital ทั้งหมดใน collection
    - ตั้งชื่อ database เอง
    - ลองใช้คำสั่ง `mongo` เพื่อใส่ข้อมูลจำลองเพื่อใช้ทดสอบในเว็บแอพ
  2. สร้าง link จาก index.jade ไปยังไฟล์ `views/create.jade` (hint: `app.get` )
  3. สร้าง Web form ใน `views/create.jade` เพื่อรับข้อมูลไปสร้างเป็น document ใหม่ใน collection
  4. สร้างระบบ routing รับค่าที่ส่งจาก web form (hint: `app.post`)
  5. เมื่อ Document ถูกเพิ่มเข้า collection แล้ว ให้แสดงรายการทั้งหมดในหน้า index.jade อีกครั้ง (hint: `res.redirect()` )
  
# 'Hospital' document structure

- Collection: hospital
- Property:
  - name: String
  - province: String
