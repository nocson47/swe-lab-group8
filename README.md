# SWE Lab Group 8[คนภูธร]
Repository สำหรับการทำงานกลุ่มวิชา Software Engineering Lab (เวอร์ชันคอนโทรล)

คำอธิบายย่อ
--
ที่เก็บนี้ใช้เป็นที่รวมผลงานและบันทึกการมีส่วนร่วมของสมาชิกกลุ่มที่ทำงานในวิชา Software Engineering Lab (กลุ่ม 8)

วิธีใช้งานสำหรับสมาชิกกลุ่ม
--
เมื่อจะทำการแก้ไขไฟล์หรือเพิ่มชื่อของตนเองลงใน `contributions.txt` ให้ทำตามขั้นตอนดังนี้ (ตัวอย่างใช้ `main` เป็นชื่อสาขาหลัก):

1) Clone repository (ครั้งแรกเท่านั้น)

```bash
git clone https://github.com/nocson47/swe-lab-group8.git
cd swe-lab-group8
```

2) ตั้งค่า Git user (ถ้ายังไม่เคยตั้งค่าบนเครื่องนี้)

```bash
git config --global user.name "Your Name"
git config --global user.email "you@email.example"
```

3) ตรวจสอบสถานะและอัปเดตข้อมูลจาก remote ก่อนเริ่มแก้ไข

```bash
git status
git pull origin main
```

4) แก้ไข `contributions.txt`

ให้เพิ่มบรรทัดใหม่ในรูปแบบ:

```
ชื่อ-สกุล รหัส ห้อง
```

ตัวอย่าง:

```
สมชาย ใจดี 63000123 01
```

5) บันทึกการเปลี่ยนแปลงและส่งขึ้น remote

```bash
git add contributions.txt
git commit -m "Add contribution: Your Name - ID - Section"
git push origin main
```

ถ้าครั้งแรกที่คุณ push จากเครื่องนี้ ให้รัน:

```bash
git push -u origin main
```
หรือ
```bash
git push
```

หมายเหตุและข้อแนะนำ
--
- ให้ดึง (`git pull`) เสมอก่อนแก้ไขเพื่อลดปัญหา merge conflicts
- ถ้ามี conflict เกิดขึ้น ให้แก้ไขไฟล์ที่ขัดกัน แล้ว `git add` และ `git commit` อีกครั้ง
- ใช้ข้อความ commit ที่สื่อความหมาย เช่น "Add contribution: <ชื่อ>" หรือ "Fix typo in contributions.txt"

ติดต่อผู้ดูแล
--
หากมีปัญหาหรือข้อสงสัย ติดต่อเจ้าของ repository: @nocson47 (GitHub)  สิรวิชญ์  ชื่นตา  

ลิขสิทธิ์
--
โปรเจกต์นี้อยู่ภายใต้ใบอนุญาตในไฟล์ `LICENSE` (ดูรายละเอียดในไฟล์)


