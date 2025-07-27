### 📝 แบบฝึกหัดที่ 1: เปลี่ยนจำนวนคุกกี้
```c
// หาบรรทัดนี้ในโค้ด:
int total_cookies = 20;    // คุกกี้ทั้งหมด
int friends = 4;           // จำนวนเพื่อน

// ลองเปลี่ยนเป็น:
int total_cookies = 24;    // เพิ่มเป็น 24 ชิ้น
int friends = 6;           // เพิ่มเป็น 6 คน
```
```c
I (19990) COOKIES_MATH: 🧮 ขั้นตอนการคิด:
I (19990) COOKIES_MATH:    คุกกี้ทั้งหมด ÷ จำนวนเพื่อน
I (19990) COOKIES_MATH:    = 26 ÷ 6
I (19990) COOKIES_MATH:    = 4 ชิ้นต่อคน
I (19990) COOKIES_MATH:    เศษที่เหลือ = 2 ชิ้น
I (19990) COOKIES_MATH: 
I (19990) COOKIES_MATH: ✅ คำตอบ:
I (19990) COOKIES_MATH:    แต่ละคนได้คุกกี้ 4 ชิ้น
I (19990) COOKIES_MATH:    มีคุกกี้เหลือ 2 ชิ้น (ไม่สามารถแบ่งได้เท่าๆ กัน)
I (19990) COOKIES_MATH: 
I (19990) COOKIES_MATH: 🎨 ภาพประกอบการแบ่ง:
I (20000) COOKIES_MATH:    คุกกี้ทั้งหมด: 🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪 (26 ชิ้น)
I (20000) COOKIES_MATH:
I (20000) COOKIES_MATH:    เพื่อนคนที่ 1: 
I (20000) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (20000) COOKIES_MATH:    เพื่อนคนที่ 2: 
I (20000) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (20000) COOKIES_MATH:    เพื่อนคนที่ 3: 
I (20000) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (20000) COOKIES_MATH:    เพื่อนคนที่ 4: 
I (20000) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (20000) COOKIES_MATH:    เพื่อนคนที่ 5: 
I (20000) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (20000) COOKIES_MATH:    เพื่อนคนที่ 6: 
I (20000) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (20010) COOKIES_MATH:    เหลือ: 
I (20010) COOKIES_MATH: 🍪 (2 ชิ้น)
I (20010) COOKIES_MATH: 
I (20010) COOKIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (20010) COOKIES_MATH:    คุกกี้ 15 ชิ้น แบ่งให้ 3 คน
I (20010) COOKIES_MATH:    = 15 ÷ 3 = 5 ชิ้นต่อคน, เหลือ 0 ชิ้น
I (20010) COOKIES_MATH: 
I (20010) COOKIES_MATH:    คุกกี้ 13 ชิ้น แบ่งให้ 4 คน
I (20010) COOKIES_MATH:    = 13 ÷ 4 = 3 ชิ้นต่อคน, เหลือ 1 ชิ้น
I (20010) COOKIES_MATH:    (หารไม่ลงตัว)
I (20010) COOKIES_MATH: 
I (20010) COOKIES_MATH: ⚠️  กรณีพิเศษ - หารด้วยศูนย์:
I (20010) COOKIES_MATH:    ถ้าไม่มีเพื่อนมาแบ่ง (หารด้วย 0)
I (20010) COOKIES_MATH:    ไม่สามารถคำนวณได้ในทางคณิตศาสตร์
I (20020) COOKIES_MATH:    ในชีวิตจริง: คุกกี้จะเหลือทั้งหมด
I (20020) COOKIES_MATH:
I (20020) COOKIES_MATH: 🔄 ความสัมพันธ์กับการคูณ:
I (20020) COOKIES_MATH:    การหาร: 26 ÷ 6 = 4
I (20020) COOKIES_MATH:    การคูณ: 4 × 6 = 24
I (20020) COOKIES_MATH:    บวกเศษ: 24 + 2 = 26
I (20020) COOKIES_MATH:    การหารและการคูณเป็นการดำเนินการตรงข้ามกัน
I (20020) COOKIES_MATH: 
I (20020) COOKIES_MATH: 📊 สรุปการดำเนินการทั้งหมด:
I (20020) COOKIES_MATH:    การบวก (+): เพิ่มจำนวน
I (20020) COOKIES_MATH:    การลบ (-): ลดจำนวน
I (20020) COOKIES_MATH:    การคูณ (×): บวกซ้ำๆ หลายชุด
I (20030) COOKIES_MATH:    การหาร (÷): แบ่งออกเป็นกลุ่มเท่าๆ กัน
I (20030) COOKIES_MATH:
I (20030) COOKIES_MATH: 🎓 แนวคิดขั้นสูง:
I (20030) COOKIES_MATH:    1. การหารจะได้ผลหาร (quotient) และเศษ (remainder)
I (20030) COOKIES_MATH:    2. ในภาษา C:
I (20030) COOKIES_MATH:       ผลหาร = a / b
I (20030) COOKIES_MATH:       เศษ = a % b
I (20030) COOKIES_MATH:    3. การตรวจสอบการหารด้วยศูนย์เป็นสิ่งสำคัญ
I (20030) COOKIES_MATH:    4. การหารด้วย 1 จะได้ตัวเลขเดิม
I (20030) COOKIES_MATH:    5. การหารตัวเลขด้วยตัวมันเองจะได้ 1
I (20030) COOKIES_MATH: 
I (20030) COOKIES_MATH: 📚 สิ่งที่เรียนรู้:
I (20030) COOKIES_MATH:    1. การหารเลข (Division): a ÷ b = c
I (20030) COOKIES_MATH:    2. การใช้ Modulo operator (%) หาเศษ
I (20030) COOKIES_MATH:    3. การตรวจสอบการหารด้วยศูนย์
I (20040) COOKIES_MATH:    4. ความแตกต่างระหว่างหารลงตัวและไม่ลงตัว
I (20040) COOKIES_MATH:    5. ความสัมพันธ์ระหว่างการหารและการคูณ
I (20040) COOKIES_MATH:    6. การจัดการกรณีพิเศษ (Error Handling)
I (20040) COOKIES_MATH: 
I (20040) COOKIES_MATH: 🎉 จบโปรแกรมแบ่งคุกกี้!
I (20040) COOKIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 05_mixed_shopping
I (22040) main_task: Returned from app_main()
```
