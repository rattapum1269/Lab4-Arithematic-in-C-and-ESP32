### 📝 แบบฝึกหัดที่ 1: เปลี่ยนจำนวนถุงลูกอม
```c
// หาบรรทัดนี้ในโค้ด:
int candy_bags = 5;         // จำนวนถุง
int candies_per_bag = 6;    // ลูกอมต่อถุง

// ลองเปลี่ยนเป็น:
int candy_bags = 7;         // เพิ่มเป็น 7 ถุง
int candies_per_bag = 8;    // ลูกอมถุงละ 8 เม็ด
```


```c
I (15649) CANDIES_MATH: 🧮 ขั้นตอนการคิด:
I (15649) CANDIES_MATH:    จำนวนถุง × ลูกอมต่อถุง
I (15649) CANDIES_MATH:    = 7 × 8
I (15649) CANDIES_MATH:    = 56 เม็ด
I (15649) CANDIES_MATH: 
I (15649) CANDIES_MATH: ✅ คำตอบ:
I (15649) CANDIES_MATH:    มีลูกอมทั้งหมด 56 เม็ด
I (15649) CANDIES_MATH: 
I (15649) CANDIES_MATH: 🎨 ภาพประกอบ:
I (15649) CANDIES_MATH:    ถุงที่ 1: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15649) CANDIES_MATH:    ถุงที่ 2: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15649) CANDIES_MATH:    ถุงที่ 3: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15649) CANDIES_MATH:    ถุงที่ 4: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15649) CANDIES_MATH:    ถุงที่ 5: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15649) CANDIES_MATH:    รวม:     56 เม็ด
I (15649) CANDIES_MATH: 
I (15659) CANDIES_MATH: 🔄 เปรียบเทียบกับการบวกซ้ำๆ:
I (15659) CANDIES_MATH:    การคูณ: 7 × 8 = 56
I (15659) CANDIES_MATH:    การบวกซ้ำๆ:
I (15659) CANDIES_MATH:                   8
I (15659) CANDIES_MATH:                 + 8
I (15659) CANDIES_MATH:                 + 8
I (15659) CANDIES_MATH:                 + 8
I (15659) CANDIES_MATH:                 + 8
I (15659) CANDIES_MATH:                 + 8
I (15659) CANDIES_MATH:                 + 8 = 56
I (15659) CANDIES_MATH:    ผลลัพธ์เหมือนกัน! การคูณคือการบวกซ้ำๆ
I (15659) CANDIES_MATH:
I (15659) CANDIES_MATH: 📊 ตารางสูตรคูณ 8:
I (15659) CANDIES_MATH:    1 × 8 = 8
I (15959) CANDIES_MATH:    2 × 8 = 16
I (16259) CANDIES_MATH:    3 × 8 = 24
I (16559) CANDIES_MATH:    4 × 8 = 32
I (16859) CANDIES_MATH:    5 × 8 = 40
I (17159) CANDIES_MATH:    6 × 8 = 48
I (17459) CANDIES_MATH:    7 × 8 = 56
I (17759) CANDIES_MATH:    8 × 8 = 64
I (18059) CANDIES_MATH:    9 × 8 = 72
I (18359) CANDIES_MATH:    10 × 8 = 80
I (18659) CANDIES_MATH: 📊 ตารางสูตรคูณของ 8:
I (18659) CANDIES_MATH:    1 x 8 = 8
I (18659) CANDIES_MATH:    2 x 8 = 16
I (18659) CANDIES_MATH:    3 x 8 = 24
I (18659) CANDIES_MATH:    4 x 8 = 32
I (18659) CANDIES_MATH:    5 x 8 = 40
I (18659) CANDIES_MATH:    6 x 8 = 48
I (18659) CANDIES_MATH:    7 x 8 = 56
I (18659) CANDIES_MATH:    8 x 8 = 64
I (18659) CANDIES_MATH:    9 x 8 = 72
I (18659) CANDIES_MATH:    10 x 8 = 80
I (18659) CANDIES_MATH: 
I (18659) CANDIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (18659) CANDIES_MATH:    ถ้ามีถุงลูกอม 3 ถุง ถุงละ 8 เม็ด
I (18659) CANDIES_MATH:    จะได้ลูกอม 3 × 8 = 24 เม็ด
I (18659) CANDIES_MATH:
I (18659) CANDIES_MATH:    ถ้ามีถุงลูกอม 7 ถุง ถุงละ 4 เม็ด
I (18659) CANDIES_MATH:    จะได้ลูกอม 7 × 4 = 28 เม็ด
I (18669) CANDIES_MATH:
I (18669) CANDIES_MATH: 🔄 เปรียบเทียบการดำเนินการ:
I (18669) CANDIES_MATH:    การบวก (+): เพิ่มจำนวน (เช่น ไข่ 4 + 2 = 6)
I (18669) CANDIES_MATH:    การลบ (-): ลดจำนวน (เช่น ของเล่น 8 - 3 = 5)
I (18669) CANDIES_MATH:    การคูณ (×): บวกซ้ำๆ (เช่น ลูกอม 5 × 6 = 30)
I (18669) CANDIES_MATH:
I (18669) CANDIES_MATH: 🎓 แนวคิดขั้นสูง:
I (18669) CANDIES_MATH:    1. การคูณมีคุณสมบัติการสับเปลี่ยน:
I (18679) CANDIES_MATH:       7 × 8 = 8 × 7 = 56
I (18679) CANDIES_MATH:    2. การคูณด้วย 0 จะได้ 0 เสมอ:
I (18679) CANDIES_MATH:       7 × 0 = 0 (ไม่มีถุงลูกอม)
I (18679) CANDIES_MATH:    3. การคูณด้วย 1 จะได้ตัวเลขเดิม:
I (18679) CANDIES_MATH:       8 × 1 = 8 (มีถุงเดียว)
I (18679) CANDIES_MATH: 
I (18679) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (18679) CANDIES_MATH:    1. การคูณเลข (Multiplication): a × b = c
I (18679) CANDIES_MATH:    2. การใช้ for loop สำหรับการทำซ้ำ
I (18679) CANDIES_MATH:    3. ความสัมพันธ์ระหว่างการคูณและการบวกซ้ำๆ
I (18679) CANDIES_MATH:    4. คุณสมบัติพิเศษของการคูณ
I (18679) CANDIES_MATH:    5. การแสดงผลแบบตาราง
I (18689) CANDIES_MATH:
I (18689) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (18689) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (20689) main_task: Returned from app_main()
```
## 📝 แบบฝึกหัดที่ 2: เพิ่มลูกอมหลายรส
เพิ่มลูกอมหลายรส:
```c
int strawberry_bags = 3;    // ถุงรสสตรอเบอร์รี่
int orange_bags = 2;        // ถุงรสส้ม
int grape_bags = 4;         // ถุงรสองุ่น

int total_bags = strawberry_bags + orange_bags + grape_bags;
int total_candies = total_bags * candies_per_bag;

ESP_LOGI(TAG, "🍓 สตรอเบอร์รี่: %d ถุง = %d เม็ด", 
         strawberry_bags, strawberry_bags * candies_per_bag);
ESP_LOGI(TAG, "🍊 รสส้ม: %d ถุง = %d เม็ด", 
         orange_bags, orange_bags * candies_per_bag);
ESP_LOGI(TAG, "🍇 รสองุ่น: %d ถุง = %d เม็ด", 
         grape_bags, grape_bags * candies_per_bag);
```

```c
I (15708) CANDIES_MATH: 🧮 ขั้นตอนการคิด:
I (15708) CANDIES_MATH:    จำนวนถุง × ลูกอมต่อถุง
I (15708) CANDIES_MATH:    = 7 × 8
I (15708) CANDIES_MATH:    = 56 เม็ด
I (15708) CANDIES_MATH:
I (15708) CANDIES_MATH: ✅ คำตอบ:
I (15708) CANDIES_MATH:    มีลูกอมทั้งหมด 56 เม็ด
I (15708) CANDIES_MATH: 
I (15708) CANDIES_MATH: 🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (15708) CANDIES_MATH: 🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (15708) CANDIES_MATH: 🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (15708) CANDIES_MATH: 🎨 ภาพประกอบ:
I (15708) CANDIES_MATH:    ถุงที่ 1: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15708) CANDIES_MATH:    ถุงที่ 2: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15718) CANDIES_MATH:    ถุงที่ 3: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15718) CANDIES_MATH:    ถุงที่ 4: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15718) CANDIES_MATH:    ถุงที่ 5: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15718) CANDIES_MATH:    รวม:     56 เม็ด
I (15718) CANDIES_MATH:
I (15718) CANDIES_MATH: 🔄 เปรียบเทียบกับการบวกซ้ำๆ:
I (15718) CANDIES_MATH:    การคูณ: 7 × 8 = 56
I (15718) CANDIES_MATH:    การบวกซ้ำๆ:
I (15718) CANDIES_MATH:                   8
I (15718) CANDIES_MATH:                 + 8
I (15718) CANDIES_MATH:                 + 8
I (15718) CANDIES_MATH:                 + 8
I (15718) CANDIES_MATH:                 + 8
I (15728) CANDIES_MATH:                 + 8
I (15728) CANDIES_MATH:                 + 8 = 56
I (15728) CANDIES_MATH:    ผลลัพธ์เหมือนกัน! การคูณคือการบวกซ้ำๆ
I (15728) CANDIES_MATH:
I (18728) CANDIES_MATH: 
I (18728) CANDIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (18728) CANDIES_MATH:    ถ้ามีถุงลูกอม 3 ถุง ถุงละ 8 เม็ด
I (18728) CANDIES_MATH:    จะได้ลูกอม 3 × 8 = 24 เม็ด
I (18728) CANDIES_MATH: 
I (18728) CANDIES_MATH:    ถ้ามีถุงลูกอม 7 ถุง ถุงละ 4 เม็ด
I (18728) CANDIES_MATH:    จะได้ลูกอม 7 × 4 = 28 เม็ด
I (18728) CANDIES_MATH:
I (18738) CANDIES_MATH: 🔄 เปรียบเทียบการดำเนินการ:
I (18738) CANDIES_MATH:    การบวก (+): เพิ่มจำนวน (เช่น ไข่ 4 + 2 = 6)
I (18738) CANDIES_MATH:    การลบ (-): ลดจำนวน (เช่น ของเล่น 8 - 3 = 5)
I (18738) CANDIES_MATH:    การคูณ (×): บวกซ้ำๆ (เช่น ลูกอม 5 × 6 = 30)
I (18738) CANDIES_MATH: 
I (18738) CANDIES_MATH: 🎓 แนวคิดขั้นสูง:
I (18738) CANDIES_MATH:    1. การคูณมีคุณสมบัติการสับเปลี่ยน:
I (18738) CANDIES_MATH:       7 × 8 = 8 × 7 = 56
I (18738) CANDIES_MATH:    2. การคูณด้วย 0 จะได้ 0 เสมอ:
I (18738) CANDIES_MATH:       7 × 0 = 0 (ไม่มีถุงลูกอม)
I (18738) CANDIES_MATH:    3. การคูณด้วย 1 จะได้ตัวเลขเดิม:
I (18738) CANDIES_MATH:       8 × 1 = 8 (มีถุงเดียว)
I (18738) CANDIES_MATH: 
I (18738) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (18738) CANDIES_MATH:    1. การคูณเลข (Multiplication): a × b = c
I (18748) CANDIES_MATH:    2. การใช้ for loop สำหรับการทำซ้ำ
I (18748) CANDIES_MATH:    3. ความสัมพันธ์ระหว่างการคูณและการบวกซ้ำๆ
I (18748) CANDIES_MATH:    4. คุณสมบัติพิเศษของการคูณ
I (18748) CANDIES_MATH:    5. การแสดงผลแบบตาราง
I (18748) CANDIES_MATH: 
I (18748) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (18748) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (20748) main_task: Returned from app_main()
```
### 📝 แบบฝึกหัดที่ 3: สร้างตารางสูตรคูณ
เพิ่มการแสดงตารางสูตรคูณ:
```c
ESP_LOGI(TAG, "📊 ตารางสูตรคูณของ %d:", candies_per_bag);
for (int i = 1; i <= 10; i++) {
    ESP_LOGI(TAG, "   %d x %d = %d", i, candies_per_bag, i * candies_per_bag);
}
```
```c
I (15708) CANDIES_MATH: 🧮 ขั้นตอนการคิด:
I (15708) CANDIES_MATH:    จำนวนถุง × ลูกอมต่อถุง
I (15708) CANDIES_MATH:    = 7 × 8
I (15708) CANDIES_MATH:    = 56 เม็ด
I (15708) CANDIES_MATH:
I (15708) CANDIES_MATH: ✅ คำตอบ:
I (15708) CANDIES_MATH:    มีลูกอมทั้งหมด 56 เม็ด
I (15708) CANDIES_MATH: 
I (15708) CANDIES_MATH: 🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (15708) CANDIES_MATH: 🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (15708) CANDIES_MATH: 🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (15708) CANDIES_MATH: 🎨 ภาพประกอบ:
I (15708) CANDIES_MATH:    ถุงที่ 1: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15708) CANDIES_MATH:    ถุงที่ 2: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15718) CANDIES_MATH:    ถุงที่ 3: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15718) CANDIES_MATH:    ถุงที่ 4: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15718) CANDIES_MATH:    ถุงที่ 5: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15718) CANDIES_MATH:    รวม:     56 เม็ด
I (15718) CANDIES_MATH:
I (15718) CANDIES_MATH: 🔄 เปรียบเทียบกับการบวกซ้ำๆ:
I (15718) CANDIES_MATH:    การคูณ: 7 × 8 = 56
I (15718) CANDIES_MATH:    การบวกซ้ำๆ:
I (15718) CANDIES_MATH:                   8
I (15718) CANDIES_MATH:                 + 8
I (15718) CANDIES_MATH:                 + 8
I (15718) CANDIES_MATH:                 + 8
I (15718) CANDIES_MATH:                 + 8
I (15728) CANDIES_MATH:                 + 8
I (15728) CANDIES_MATH:                 + 8 = 56
I (15728) CANDIES_MATH:    ผลลัพธ์เหมือนกัน! การคูณคือการบวกซ้ำๆ
I (15728) CANDIES_MATH:
I (15728) CANDIES_MATH: 📊 ตารางสูตรคูณ 8:
I (15728) CANDIES_MATH:    1 × 8 = 8
I (16028) CANDIES_MATH:    2 × 8 = 16
I (16328) CANDIES_MATH:    3 × 8 = 24
I (16628) CANDIES_MATH:    4 × 8 = 32
I (16928) CANDIES_MATH:    5 × 8 = 40
I (17228) CANDIES_MATH:    6 × 8 = 48
I (17528) CANDIES_MATH:    7 × 8 = 56
I (17828) CANDIES_MATH:    8 × 8 = 64
I (18128) CANDIES_MATH:    9 × 8 = 72
I (18428) CANDIES_MATH:    10 × 8 = 80
I (18728) CANDIES_MATH: 
I (18728) CANDIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (18728) CANDIES_MATH:    ถ้ามีถุงลูกอม 3 ถุง ถุงละ 8 เม็ด
I (18728) CANDIES_MATH:    จะได้ลูกอม 3 × 8 = 24 เม็ด
I (18728) CANDIES_MATH: 
I (18728) CANDIES_MATH:    ถ้ามีถุงลูกอม 7 ถุง ถุงละ 4 เม็ด
I (18728) CANDIES_MATH:    จะได้ลูกอม 7 × 4 = 28 เม็ด
I (18728) CANDIES_MATH:
I (18738) CANDIES_MATH: 🔄 เปรียบเทียบการดำเนินการ:
I (18738) CANDIES_MATH:    การบวก (+): เพิ่มจำนวน (เช่น ไข่ 4 + 2 = 6)
I (18738) CANDIES_MATH:    การลบ (-): ลดจำนวน (เช่น ของเล่น 8 - 3 = 5)
I (18738) CANDIES_MATH:    การคูณ (×): บวกซ้ำๆ (เช่น ลูกอม 5 × 6 = 30)
I (18738) CANDIES_MATH: 
I (18738) CANDIES_MATH: 🎓 แนวคิดขั้นสูง:
I (18738) CANDIES_MATH:    1. การคูณมีคุณสมบัติการสับเปลี่ยน:
I (18738) CANDIES_MATH:       7 × 8 = 8 × 7 = 56
I (18738) CANDIES_MATH:    2. การคูณด้วย 0 จะได้ 0 เสมอ:
I (18738) CANDIES_MATH:       7 × 0 = 0 (ไม่มีถุงลูกอม)
I (18738) CANDIES_MATH:    3. การคูณด้วย 1 จะได้ตัวเลขเดิม:
I (18738) CANDIES_MATH:       8 × 1 = 8 (มีถุงเดียว)
I (18738) CANDIES_MATH: 
I (18738) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (18738) CANDIES_MATH:    1. การคูณเลข (Multiplication): a × b = c
I (18748) CANDIES_MATH:    2. การใช้ for loop สำหรับการทำซ้ำ
I (18748) CANDIES_MATH:    3. ความสัมพันธ์ระหว่างการคูณและการบวกซ้ำๆ
I (18748) CANDIES_MATH:    4. คุณสมบัติพิเศษของการคูณ
I (18748) CANDIES_MATH:    5. การแสดงผลแบบตาราง
I (18748) CANDIES_MATH: 
I (18748) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (18748) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (20748) main_task: Returned from app_main()
```
### 📝 แบบฝึกหัดที่ 4: แจกลูกอมให้เพื่อน
คำนวณการแจกลูกอม:
```c
int friends = 12;           // จำนวนเพื่อน
int candies_per_friend = total_candies / friends;  // ลูกอมต่อคน
int remaining_candies = total_candies % friends;   // ลูกอมที่เหลือ

ESP_LOGI(TAG, "👥 แจกให้เพื่อน %d คน:", friends);
ESP_LOGI(TAG, "   คนละ %d เม็ด", candies_per_friend);
ESP_LOGI(TAG, "   เหลือ %d เม็ด", remaining_candies);
```


```c
I (15708) CANDIES_MATH: 🧮 ขั้นตอนการคิด:
I (15708) CANDIES_MATH:    จำนวนถุง × ลูกอมต่อถุง
I (15708) CANDIES_MATH:    = 7 × 8
I (15708) CANDIES_MATH:    = 56 เม็ด
I (15708) CANDIES_MATH:
I (15708) CANDIES_MATH: ✅ คำตอบ:
I (15708) CANDIES_MATH:    มีลูกอมทั้งหมด 56 เม็ด
I (15708) CANDIES_MATH: 
I (15708) CANDIES_MATH: 🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (15708) CANDIES_MATH: 🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (15708) CANDIES_MATH: 🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (15708) CANDIES_MATH: 🎨 ภาพประกอบ:
I (15708) CANDIES_MATH:    ถุงที่ 1: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15708) CANDIES_MATH:    ถุงที่ 2: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15718) CANDIES_MATH:    ถุงที่ 3: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15718) CANDIES_MATH:    ถุงที่ 4: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15718) CANDIES_MATH:    ถุงที่ 5: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (15718) CANDIES_MATH:    รวม:     56 เม็ด
I (15718) CANDIES_MATH: 👥 แจกให้เพื่อน 12 คน:
I (15718) CANDIES_MATH:    คนละ 6 เม็ด
I (15718) CANDIES_MATH:    เหลือ 0 เม็ด
I (15718) CANDIES_MATH:
I (15718) CANDIES_MATH: 🔄 เปรียบเทียบกับการบวกซ้ำๆ:
I (15718) CANDIES_MATH:    การคูณ: 7 × 8 = 56
I (15718) CANDIES_MATH:    การบวกซ้ำๆ:
I (15718) CANDIES_MATH:                   8
I (15718) CANDIES_MATH:                 + 8
I (15718) CANDIES_MATH:                 + 8
I (15718) CANDIES_MATH:                 + 8
I (15718) CANDIES_MATH:                 + 8
I (15728) CANDIES_MATH:                 + 8
I (15728) CANDIES_MATH:                 + 8 = 56
I (15728) CANDIES_MATH:    ผลลัพธ์เหมือนกัน! การคูณคือการบวกซ้ำๆ
I (15728) CANDIES_MATH:
I (15728) CANDIES_MATH: 📊 ตารางสูตรคูณ 8:
I (15728) CANDIES_MATH:    1 × 8 = 8
I (16028) CANDIES_MATH:    2 × 8 = 16
I (16328) CANDIES_MATH:    3 × 8 = 24
I (16628) CANDIES_MATH:    4 × 8 = 32
I (16928) CANDIES_MATH:    5 × 8 = 40
I (17228) CANDIES_MATH:    6 × 8 = 48
I (17528) CANDIES_MATH:    7 × 8 = 56
I (17828) CANDIES_MATH:    8 × 8 = 64
I (18128) CANDIES_MATH:    9 × 8 = 72
I (18428) CANDIES_MATH:    10 × 8 = 80
I (18728) CANDIES_MATH: 📊 ตารางสูตรคูณของ 8:
I (18728) CANDIES_MATH:    1 x 8 = 8
I (18728) CANDIES_MATH:    2 x 8 = 16
I (18728) CANDIES_MATH:    3 x 8 = 24
I (18728) CANDIES_MATH:    4 x 8 = 32
I (18728) CANDIES_MATH:    5 x 8 = 40
I (18728) CANDIES_MATH:    6 x 8 = 48
I (18728) CANDIES_MATH:    7 x 8 = 56
I (18728) CANDIES_MATH:    8 x 8 = 64
I (18728) CANDIES_MATH:    9 x 8 = 72
I (18728) CANDIES_MATH:    10 x 8 = 80
I (18728) CANDIES_MATH: 
I (18728) CANDIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (18728) CANDIES_MATH:    ถ้ามีถุงลูกอม 3 ถุง ถุงละ 8 เม็ด
I (18728) CANDIES_MATH:    จะได้ลูกอม 3 × 8 = 24 เม็ด
I (18728) CANDIES_MATH: 
I (18728) CANDIES_MATH:    ถ้ามีถุงลูกอม 7 ถุง ถุงละ 4 เม็ด
I (18728) CANDIES_MATH:    จะได้ลูกอม 7 × 4 = 28 เม็ด
I (18728) CANDIES_MATH:
I (18738) CANDIES_MATH: 🔄 เปรียบเทียบการดำเนินการ:
I (18738) CANDIES_MATH:    การบวก (+): เพิ่มจำนวน (เช่น ไข่ 4 + 2 = 6)
I (18738) CANDIES_MATH:    การลบ (-): ลดจำนวน (เช่น ของเล่น 8 - 3 = 5)
I (18738) CANDIES_MATH:    การคูณ (×): บวกซ้ำๆ (เช่น ลูกอม 5 × 6 = 30)
I (18738) CANDIES_MATH: 
I (18738) CANDIES_MATH: 🎓 แนวคิดขั้นสูง:
I (18738) CANDIES_MATH:    1. การคูณมีคุณสมบัติการสับเปลี่ยน:
I (18738) CANDIES_MATH:       7 × 8 = 8 × 7 = 56
I (18738) CANDIES_MATH:    2. การคูณด้วย 0 จะได้ 0 เสมอ:
I (18738) CANDIES_MATH:       7 × 0 = 0 (ไม่มีถุงลูกอม)
I (18738) CANDIES_MATH:    3. การคูณด้วย 1 จะได้ตัวเลขเดิม:
I (18738) CANDIES_MATH:       8 × 1 = 8 (มีถุงเดียว)
I (18738) CANDIES_MATH: 
I (18738) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (18738) CANDIES_MATH:    1. การคูณเลข (Multiplication): a × b = c
I (18748) CANDIES_MATH:    2. การใช้ for loop สำหรับการทำซ้ำ
I (18748) CANDIES_MATH:    3. ความสัมพันธ์ระหว่างการคูณและการบวกซ้ำๆ
I (18748) CANDIES_MATH:    4. คุณสมบัติพิเศษของการคูณ
I (18748) CANDIES_MATH:    5. การแสดงผลแบบตาราง
I (18748) CANDIES_MATH: 
I (18748) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (18748) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (20748) main_task: Returned from app_main()
```
