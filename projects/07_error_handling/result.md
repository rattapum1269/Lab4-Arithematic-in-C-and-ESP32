## 🎯 โจทย์สถานการณ์
ร้านขายของมีปัญหาต่างๆ เหล่านี้:

### 🍕 ร้านพิซซ่า
- **พิซซ่าทั้งหมด**: 12 ชิ้น
- **ลูกค้า**: 0 คน (วันที่ฝนตก)
- **ปัญหา**: แบ่งพิซซ่าให้ลูกค้า 0 คน ได้ไหม?

### 💰 ร้านขายของ
- **เงินทอน**: -50 บาท (ลูกค้าให้เงินไม่พอ)
- **ราคาสินค้า**: "ABC" บาท (พิมพ์ผิด)
- **ปัญหา**: จัดการข้อมูลผิดพลาดอย่างไร?

### 🏦 ธนาคาร
- **ยอดเงินฝาก**: 999,999,999,999 บาท (เกินขีดจำกัด)
- **อัตราดอกเบี้ย**: -5% (ติดลบ)
- **ปัญหา**: ตรวจสอบข้อมูลก่อนคำนวณ
```c
I (18031) ERROR_HANDLING: 
🍕 === ร้านพิซซ่า ===
I (18031) ERROR_HANDLING: 
🔍 ตรวจสอบการหาร: แบ่งพิซซ่าให้ลูกค้า 4 คน
I (18031) ERROR_HANDLING: 📊 12.00 ÷ 4.00 = ?
I (18041) ERROR_HANDLING: ✅ สำเร็จ: 12.00 ÷ 4.00 = 3.00
I (18041) ERROR_HANDLING:    ✅ SUCCESS
I (18041) ERROR_HANDLING:      🎉🎉🎉
I (18041) ERROR_HANDLING:     สำเร็จแล้ว!
I (20041) ERROR_HANDLING: 
🔍 ตรวจสอบการหาร: แบ่งพิซซ่าให้ลูกค้า 0 คน
I (20041) ERROR_HANDLING: 📊 12.00 ÷ 0.00 = ?
E (20041) ERROR_HANDLING: ❌ หารด้วยศูนย์ไม่ได้!
I (20041) ERROR_HANDLING:    🍕 ÷ 0 = ❌
I (20041) ERROR_HANDLING:    😱 โอ้ะโอ!
I (20041) ERROR_HANDLING:   ไม่มีลูกค้า!
I (20041) ERROR_HANDLING: 💡 ตรวจสอบจำนวนลูกค้าก่อนแบ่งพิซซ่า
I (22041) ERROR_HANDLING: 
🌞 ฝนหยุดแล้ว! ลูกค้ามา 3 คน
I (22041) ERROR_HANDLING: 
🔍 ตรวจสอบการหาร: แบ่งพิซซ่าให้ลูกค้า 3 คน
I (22041) ERROR_HANDLING: 📊 12.00 ÷ 4.00 = ?
I (22041) ERROR_HANDLING: ✅ สำเร็จ: 12.00 ÷ 4.00 = 3.00
I (22041) ERROR_HANDLING:    ✅ SUCCESS
I (22041) ERROR_HANDLING:      🎉🎉🎉
I (22041) ERROR_HANDLING:     สำเร็จแล้ว!
I (25041) ERROR_HANDLING: 
🛒 === ร้านขายของ ===
I (25041) ERROR_HANDLING: 
🔢 ตรวจสอบตัวเลข: ราคาสินค้า
I (25041) ERROR_HANDLING: 📝 ข้อมูลที่ป้อน: 'ABC'
E (25041) ERROR_HANDLING: ❌ 'ABC' ไม่ใช่ตัวเลข!
I (25041) ERROR_HANDLING:    📝 ABC บาท?
I (25041) ERROR_HANDLING:    🤔 งง...
I (25041) ERROR_HANDLING:   ตัวเลขหายไป
I (25041) ERROR_HANDLING: 💡 ใช้เฉพาะตัวเลข 0-9 และจุดทศนิยม
I (27051) ERROR_HANDLING: 
🔢 ตรวจสอบตัวเลข: ราคาสินค้า
I (27051) ERROR_HANDLING: 📝 ข้อมูลที่ป้อน: '12.50'
I (27051) ERROR_HANDLING: ✅ ตัวเลขถูกต้อง: 12.50
I (28051) ERROR_HANDLING: 
💰 ตรวจสอบเงิน: เงินทอน
I (28051) ERROR_HANDLING: 💵 จำนวน: -50.00 บาท
E (28051) ERROR_HANDLING: ❌ จำนวนเงินต้องไม่ติดลบ!
I (28051) ERROR_HANDLING: 💡 ตรวจสอบการคิดเงินใหม่
I (30051) ERROR_HANDLING: 
💰 ตรวจสอบเงิน: เงินทอน
I (30051) ERROR_HANDLING: 💵 จำนวน: 25.75 บาท
I (30051) ERROR_HANDLING: ✅ เงินถูกต้อง: 25.75 บาท
I (33051) ERROR_HANDLING: 
🏦 === ธนาคาร ===
I (33051) ERROR_HANDLING: 
🏦 คำนวณดอกเบี้ย
I (33051) ERROR_HANDLING: 💰 เงินต้น: 100000.00 บาท
I (33051) ERROR_HANDLING: 📈 อัตราดอกเบี้ย: 2.50% ต่อปี
I (33051) ERROR_HANDLING: ⏰ ระยะเวลา: 5 ปี
I (33051) ERROR_HANDLING: ✅ ดอกเบี้ย: 12500.00, รวม: 112500.00
I (35051) ERROR_HANDLING: 
🏦 คำนวณดอกเบี้ย
I (35051) ERROR_HANDLING: 💰 เงินต้น: 100000.00 บาท
I (35051) ERROR_HANDLING: 📈 อัตราดอกเบี้ย: -5.00% ต่อปี
I (35051) ERROR_HANDLING: ⏰ ระยะเวลา: 5 ปี
I (35051) ERROR_HANDLING: ✅ ดอกเบี้ย: -25000.00, รวม: 75000.00
I (37051) ERROR_HANDLING: 
💰 ตรวจสอบเงิน: เงินฝาก
I (37051) ERROR_HANDLING: 💵 จำนวน: 999999999999.00 บาท
I (37051) ERROR_HANDLING: ✅ เงินถูกต้อง: 999999999999.00 บาท
I (39051) ERROR_HANDLING: 
🏦 คำนวณดอกเบี้ย
I (39051) ERROR_HANDLING: 💰 เงินต้น: 100000.00 บาท
I (39051) ERROR_HANDLING: 📈 อัตราดอกเบี้ย: 3.00% ต่อปี
I (39051) ERROR_HANDLING: ⏰ ระยะเวลา: 10 ปี
I (39051) ERROR_HANDLING: ✅ ดอกเบี้ย: 30000.00, รวม: 130000.00
I (42051) ERROR_HANDLING: 
📚 === สรุปข้อผิดพลาด ===
I (42051) ERROR_HANDLING: ╔══════════════════════════════════════╗
I (42051) ERROR_HANDLING: ║ 🚫 Division by Zero  - หารด้วยศูนย์ ║
I (42051) ERROR_HANDLING: ║ 📝 Invalid Input      - ป้อนผิด     ║
I (42051) ERROR_HANDLING: ║ 📊 Out of Range       - เกินขอบเขต  ║
I (42051) ERROR_HANDLING: ║ ➖ Negative Value      - ค่าติดลบ     ║
I (42051) ERROR_HANDLING: ║ ⬆️ Overflow            - ล้นค่าระบบ ║
I (42051) ERROR_HANDLING: ╚══════════════════════════════════════╝
I (42051) ERROR_HANDLING:
🛡️ หลักการจัดการข้อผิดพลาด:
I (42051) ERROR_HANDLING: ✅ ตรวจสอบข้อมูลก่อนคำนวณ
I (42051) ERROR_HANDLING: ✅ แจ้งเตือนแบบเข้าใจง่าย
I (42051) ERROR_HANDLING: ✅ ให้คำแนะนำแก้ปัญหา
I (42061) ERROR_HANDLING: ✅ ป้องกัน crash หรือ hang
I (42061) ERROR_HANDLING: ✅ ใช้ enum + struct คุมสถานะ
I (42061) ERROR_HANDLING:
✅ เสร็จสิ้น! พร้อมเขียนโปรแกรมปลอดภัยแล้ว!
I (42061) main_task: Returned from app_main()
```
