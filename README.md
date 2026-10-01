# adjust-condition

สื่อการสอนและคู่มือหน้าเครื่องสำหรับงานฉีดพลาสติก (Injection Molding) เปิดได้ด้วยเบราว์เซอร์โดยตรง หรือผ่าน GitHub Pages

| หน้า | เนื้อหา |
|---|---|
| [`injection-cycle.html`](injection-cycle.html) | รอบการฉีด 1 cycle จากใบ condition เครื่อง Fanuc B-26 (PC F40-40): simulator การขยับของสกรูและแม่พิมพ์, กราฟตำแหน่ง/ความเร็ว/แรงดัน, จุดวัดค่า monitor, แบบทดสอบ |
| [`injection-troubleshooting-th.html`](injection-troubleshooting-th.html) | คู่มือแก้ปัญหาตามอาการ เรียงจากปรับง่ายไปยาก และค่าตั้งเครื่องตามเกรดวัสดุ |

สองหน้าลิงก์ถึงกัน: การ์ดอาการแต่ละใบลิงก์ไปจังหวะและค่า monitor ที่เกี่ยวข้อง และการ์ด monitor ลิงก์กลับไปอาการที่ต้องเฝ้าดู

ลิงก์ตรง (deep link)
- `injection-cycle.html#pack` เปิด simulator ที่จังหวะนั้น (`close`, `inj`, `pack`, `bef`, `rec`, `dcmp`, `open`, `ej`)
- `injection-cycle.html#m-mincush` เปิดการ์ด monitor (`m-vppos`, `m-vpprs`, `m-peak`, `m-mincush`, `m-extr`, `m-injt`, `m-recov`, `m-cycle`, `m-maxinj`, `m-maxpack`)
- `injection-troubleshooting-th.html#d-sink` เปิดการ์ดอาการ และ `#mats` เปิดหน้าค่าวัสดุ
