# focus-en-cordee

ชื่อที่แสดงบนเว็บ: Summit Buddy (เพื่อนขึ้นดอย)

เว็บเพื่อนนั่งทำงาน มีเกาะภูเขา 3 มิติ ตัวจับเวลา เพลง lo-fi และเสียงธรรมชาติ
ชุดนี้เป็นเว็บล้วน ไม่ต้องตั้ง Environment Variables และไม่ต้องใช้ฐานข้อมูล

## ขึ้น Vercel ผ่าน GitHub

1. อัปโหลดไฟล์ในโฟลเดอร์นี้ขึ้น GitHub repository ใหม่
2. ที่ https://vercel.com กด Add New > Project แล้วเลือก repository นี้
3. กด Deploy

## ขึ้น Vercel ด้วยคำสั่ง

```bash
npm i -g vercel
vercel --prod --name focus-en-cordee
```

## อัปเดตครั้งถัดไป

แทนที่ `public/index.html` ด้วยไฟล์ใหม่ แล้ว push ขึ้น GitHub หรือรัน `vercel --prod`

## หมายเหตุ

สถิติและการตั้งค่าเก็บในเบราว์เซอร์ของแต่ละคน
