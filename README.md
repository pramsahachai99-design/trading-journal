# Trading Journal (ฟรี, ใช้ได้เลยในเบราว์เซอร์)

สมุดบันทึกการเทรดสไตล์สอบกองทุน (prop firm) — กรอกเองวันต่อวัน แล้วดูว่าผ่านกฎไหม

👉 **เปิดใช้งาน: https://pramsahachai99-design.github.io/trading-journal/**

## มีอะไรให้
- บันทึกไม้เทรดรายวัน (symbol / side / lots / entry / SL / TP / exit / P&L / setup / mistake / emotion / note)
- คิด R ต่อไม้ให้อัตโนมัติจาก entry–SL
- ด่านกฎแบบสอบกองทุน: daily loss limit, max loss, profit target, จำนวนวันเทรดขั้นต่ำ
- สรุป: win rate, expectancy, profit factor, max drawdown, streak, แยกตามวัน/setup/emotion/ช่วงเวลา
- เตือนเมื่อ R กับเงินไปคนละทาง (= ลอตไม่สม่ำเสมอ)
- export CSV / JSON และ import JSON กลับได้

## ความเป็นส่วนตัว
ข้อมูลเก็บใน **localStorage ของเบราว์เซอร์ตัวเอง** (key `tradingJournal.v1`) ไม่ส่งออกไปเซิร์ฟเวอร์ ไม่มี backend ไม่มี analytics
ใครเปิดลิงก์นี้ก็เห็นแค่สมุดของตัวเอง ไม่เห็นของคนอื่น

หมายเหตุ: ล้าง browser data / ใช้โหมดไม่ระบุตัวตน = ข้อมูลหาย → export JSON เก็บไว้เป็นระยะ

## ใช้แบบออฟไลน์
กด Save ไฟล์ `index.html` ลงเครื่อง แล้วดับเบิลคลิกเปิดได้เลย ไม่ต้องติดตั้งอะไร
