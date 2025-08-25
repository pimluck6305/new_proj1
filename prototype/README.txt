# Air Pro Online — Prototype & Wireframes

ไฟล์ที่ให้ไป:
- `airpro-wireframes.pdf` : ไฟล์ Wireframe (A4) นำเข้า Figma ได้ (File > Import)
- `prototype/index.html` : เว็บต้นแบบแบบ Single-file (รันได้จริง)
- `logo-airpro.svg` : ไฟล์โลโก้สำหรับใช้ในโปรเจกต์

วิธีเปิด Prototype:
1) ดับเบิลคลิก `prototype/index.html` (ถ้าเครื่องต่ออินเทอร์เน็ต จะโหลด Tailwind จาก CDN ให้ทันที)
2) หรือเปิดด้วย Live Server ของ VS Code

วิธีนำเข้า Wireframe สู่ Figma:
1) เปิด Figma > New design file
2) ไปที่ `File > Place image / video ...` หรือ `File > Import`
3) เลือกไฟล์ `airpro-wireframes.pdf` หรือ `logo-airpro.svg` เพื่อใช้งาน/ต่อยอด

แนวทางโครงสร้างหน้า:
- Home: แบนเนอร์, สินค้าแนะนำ, จุดขาย
- Category: กรอง/เรียง, กริดสินค้า
- Product Detail: รูป, ราคา, สเปก, ปุ่มใส่ตะกร้า
- Cart & Checkout: สรุปยอด, ปรับจำนวน, ชำระเงิน (เดโม)