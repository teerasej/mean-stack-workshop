# Angular JS labs
1. ปรับ/สร้าง routing ของ `routes/hospitals.js` ให้รองรับ
  - การขอข้อมูลทั้งหมดของ Hospital collection เป็น json
  - การรับ post request เพื่อนำข้อมูลจาก angularjs มาสร้างเป็น document ใหม่ใน collection

2. ปรับส่วนของ web form ดังนี้
  1. ปรับ `views/index.jade` สำหรับ แสดงข้อมูลของ Hospital  ทั้งหมดใน collection
    - ใช้ angular เรียกข้อมูลจาก routing และนำมาแสดงในหน้าเว็บ (hint: `$http.get()`)
  2. เพิ่ม web form ใน `views/index.jade` รับข้อมูลเพื่อเอาไปสร้าง document ใน collection
    - พอกดปุ่ม Add ใน web form แล้วให้ส่งข้อมูลเข้าไปที่ routing ที่สร้างไว้ (hint: `$http.post()`)
    - หลังจากข้อมูลเข้า database ไปแล้ว ให้แสดงข้อมูลล่าสุดในหน้าเดิม
    
# 'Product' document structure

- Collection: products
- Property:
  - name: String
  - price: Number
  - capacity: String
