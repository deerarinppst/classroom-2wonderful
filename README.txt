วิธีเผยแพร่ด้วย GitHub Pages

1. อัปโหลดไฟล์ index.html, 404.html และ .nojekyll ไว้ที่หน้าหลักของ Repository
   ห้ามอัปโหลดเฉพาะโฟลเดอร์ github-pages-site โดยปล่อยให้ index.html อยู่ข้างใน

2. เปิด Repository บน GitHub แล้วไปที่:
   Settings > Pages

3. ในหัวข้อ Build and deployment เลือก:
   Source: Deploy from a branch
   Branch: main
   Folder: / (root)

4. กด Save และรอประมาณ 1–3 นาที

5. ลิงก์เว็บไซต์ปกติจะเป็น:
   https://ชื่อผู้ใช้.github.io/ชื่อ-repository/

หมายเหตุ:
- ถ้า Repository ชื่อ username.github.io ให้เปิด:
  https://username.github.io/
- ตรวจสอบว่าชื่อไฟล์เป็น index.html ตัวพิมพ์เล็กทั้งหมด
