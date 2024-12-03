# web-semantic-lab
โปรเจคนี้เป็นส่วนหนึ่งของวิชา Web Frontend Development


## รายละเอียด
- การใช้ Semantic HTML
- Form Validation
- ARIA Labels


 # คำสั่งที่ใช้ ส่วนที่ 1
 git clone  https://github.com/66160147/web-semantic-lab.git
 สร้าง README.md
 git add README.md
 git commit -m "comment"
 git push

# ส่วนที่ 2

git checkout -b development
สร้างไฟล์ index.html กับ contact.html
git add .
git commit -m "สร้างโครงสร้างโปรเจคเริ่มต้น"

# ส่วนที่ 3
git checkout -b feature/homepage
git add .
git commit -m "สร้างโครงสร้างเริ่มต้นของโปรเจค"

# ส่วนที่ 4
. แก้ไขไฟล์ index.html เพิ่ม header และ nav
git add .
git commit -m "เพิ่ม header และ nav ในหน้าหลัก"
. เพิ่มส่วน main และ article ต่อจาก <header>
git commit -m "เพิ่มส่วน main และ article ในหน้าหลัก"


git checkout development
git merge feature/homepage
git merge feature/contact

##push ขึ้น github
git push origin development

##ไปทํา pull request ต่อที่ github
