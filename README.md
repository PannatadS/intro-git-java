# intro-git-java 
Java backend developer bootcamp

## โจทย์ ❓
ลองแตก branch ออกมาจาก main branch จากนั้นให้แก้ไขใน branch ที่แตกออกมา แล้วสุดท้าย merge กลับไปที่ main branch 

## Start!
- เริ่ม initialize ด้วยคำสั่งว่า git init
- เชื่อม Local Repository และ Remote Repository ด้วยคำสั่ง git remote add origin ...
- ตรวจสอบว่าเชื่อม Local Repository เข้ากับ Remote Repository หรือไม่ด้วยคำสั่ง git remote -v
- เริ่ม pull file จาก Remote Repository ด้วยคำสั่ง git pull origin main

## หากไม่ต้องการนำไฟล์จาก Local file บางอย่างขึ้น
- ไป config ที่ .gitignore
  - .idea/
 
## หากต้องการแตก branch จะทำอย่างไร ?
- git checkout -b แล้วตามด้วยชื่อ branch
- git checkout +ชื่อ branch จะเป็นการ switch branch
