# adjust-condition

สื่อการสอนและคู่มือหน้าเครื่องสำหรับงานฉีดพลาสติก (Injection Molding) เปิดได้ด้วยเบราว์เซอร์โดยตรง หรือผ่าน GitHub Pages

| หน้า | เนื้อหา |
|---|---|
| [`injection-cycle.html`](injection-cycle.html) | รอบการฉีด 1 cycle จากใบ condition master (LCP UENO, Fanuc 100 ton, สกรู Ø26): ปรับค่า condition ได้ (ฉีดและ pack 2 step) แล้วดูผลต่อ fill, cushion, shot weight, ขนาด และ cycle time, simulator การขยับของสกรูและแม่พิมพ์, กราฟตำแหน่ง/ความเร็ว/แรงดันเทียบกับค่า master |
| [`injection-troubleshooting-th.html`](injection-troubleshooting-th.html) | คู่มือแก้ปัญหาตามอาการ เรียงจากปรับง่ายไปยาก และค่าตั้งเครื่องตามเกรดวัสดุ |

สองหน้าลิงก์ถึงกัน: การ์ดอาการแต่ละใบลิงก์ไปจังหวะและค่า monitor ที่เกี่ยวข้อง และคำเตือนกับจังหวะในหน้ารอบการฉีดลิงก์กลับไปการ์ดวิธีแก้

ลิงก์ตรง (deep link)
- `injection-cycle.html#pack` เปิด simulator ที่จังหวะนั้น (`close`, `inj`, `pack`, `bef`, `rec`, `dcmp`, `cool`, `open`, `ej`)
- `injection-cycle.html#m-mincush` เลื่อนไปที่กราฟ ณ จังหวะที่วัดค่า monitor นั้น (`m-vppos`, `m-vpprs`, `m-peak`, `m-mincush`, `m-extr`, `m-injt`, `m-recov`, `m-cycle`, `m-maxinj`, `m-maxpack`)
- `injection-troubleshooting-th.html#d-sink` เปิดการ์ดอาการ และ `#mats` เปิดหน้าค่าวัสดุ
