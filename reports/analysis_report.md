# ใบงานทดลอง: การศึกษาสถาปัตยกรรม ESP32

 ### การทดลองที่ 1
## คำถามทบทวน

** Docker Commands: คำสั่ง docker-compose up -d และ docker-compose exec esp32-dev bash ทำอะไร?
 1.docker-compose up -d → เริ่ม container
 2.docker-compose exec esp32-dev bash → เข้าไปทำงานใน container นั้น เช่น สร้างโปรแกรม ESP32
- ESP-IDF Tools: เครื่องมือไหนจาก Lab4 ที่จะใช้ในการ build โปรแกรม ESP32?
 1.idf.py build
 New Tools: เครื่องมือใหม่ที่ติดตั้ง (tree, htop) ใช้ทำอะไร?
 | เครื่องมือ | ใช้ทำอะไร                       | 
 | ---------- | ------------------------------- | 
 | `tree`     | ดูโครงสร้างโฟลเดอร์แบบต้นไม้    | 
 | `htop`     | ดูการใช้ CPU, RAM แบบ real-time | 
- Architecture Focus: การศึกษา ESP32 architecture แตกต่างจากการทำ arithmetic ใน Lab4 อย่างไร?
 การศึกษา ESP32 architecture เน้นความเข้าใจ โครงสร้างภายในของชิป เช่น หน่วยประมวลผล, หน่วยความจำ, และอุปกรณ์ต่อพ่วง
 ส่วน Lab4 (Arithmetic) เน้นการฝึกเขียนโปรแกรมพื้นฐาน (เช่น บวก ลบ คูณ หาร) เพื่อเข้าใจ ภาษา C และตรรกะโปรแกรม

