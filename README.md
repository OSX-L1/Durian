# Durian
# สร้างโฟลเดอร์สำหรับโปรเจกต์ของคุณ (ถ้ายังไม่มี)
mkdir durian-app
cd durian-app

# สร้างไฟล์ index.html และวางโค้ดลงไป
# (คุณสามารถสร้างด้วย VS Code หรือโปรแกรมแก้ไขข้อความอื่นๆ)

# เริ่มต้น Git ในโฟลเดอร์โปรเจกต์ของคุณ
git init

# เพิ่มไฟล์ทั้งหมด
git add .

# คอมมิตการเปลี่ยนแปลง
git commit -m "Initial commit of durian sales app"

# เชื่อมต่อกับ GitHub repository ของคุณ (แทนที่ <YOUR_USERNAME> และ <YOUR_REPO_NAME>)
git remote add origin https://github.com/<YOUR_USERNAME>/<YOUR_REPO_NAME>.git

# พุชโค้ดไปยัง GitHub
git push -u origin master
