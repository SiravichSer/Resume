# CE.AI Resume Website

เว็บไซต์ Resume สำหรับงาน IP1 สร้างด้วย HTML, CSS และ Bootstrap CSS เท่านั้น ไม่มี JavaScript

## วิธีเปิดใน VS Code
1. แตกไฟล์ ZIP
2. เปิดโฟลเดอร์ `ce_ai_resume` ด้วย VS Code
3. เปิด `index.html` ในเบราว์เซอร์ หรือใช้ส่วนขยาย Live Server ใน VS Code
4. อินเทอร์เน็ตจำเป็นสำหรับโหลด Bootstrap CSS และ Google Fonts จาก CDN

## สิ่งที่ต้องแก้ก่อนส่งงาน
- แก้ `Your Name` และ `Your Surname` เป็นชื่อจริง
- แก้สาขา คณะ สถาบัน และประวัติการศึกษาให้ตรงกับข้อมูลจริง
- แก้ประสบการณ์ ทักษะ และโปรเจกต์ให้ตรงกับผลงานจริง
- แทนที่ไฟล์ `images/profile.svg` ด้วยรูปของตัวเองและแก้ path ใน `index.html` ให้ตรงกับชื่อไฟล์รูป (แนะนำรูปสี่เหลี่ยมจัตุรัส)
- แก้ข้อมูลติดต่อโดยใช้ข้อมูลสมมุติตามข้อกำหนดในเอกสารงาน
- ตรวจสอบลิงก์ทุกจุดก่อนเผยแพร่

## หมายเหตุ
- Hamburger menu ใช้ checkbox และ CSS จึงไม่ต้องใช้ JavaScript
- รูปโปรไฟล์จะใช้ placeholder หากยังไม่มีไฟล์ `images/profile.svg`
- Navbar แบบ CSS-only ไม่ได้ใช้ Bootstrap JavaScript bundle
