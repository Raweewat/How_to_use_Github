If address not correct:
    pwd  # To check add address that file
    cd         #[file that want to open]
    cd ..      #[Exit address] 
    #Ex - cd Test[github]
    #To change - /Users/s92238/Desktop/Training/Test/
    to /Users/s92238/Desktop/Training/Test/Test[github]
    
    git branch  # To check what is your branch rightnow
    git status  # To check status on working and staging


First Time
# git init
# git add [filename.xx] #Ex - git add README.md
# git commit -m "[Comment]"
## git config --global user.email "raweewat.c1997@gmail.com"
## git branch -M main
## git remote add origin https://github.com/Raweewat/xxx.git
## git push -u origin main

Second Time
# git init
# git add [filename.xx] #Ex - git add README.md  or git add .
# git commit -m "[Comment]"
# git push

#################
git init ไว้สร้าง git repository

git status ตรวจสอบสถานะไฟล์ของ working diractory และ staging area

git add เพิ่มไฟล์ working เข้าสู่ staging area

git diff แสดงความแตกต่างของไฟล working directory และ staging area

git commit เก็บประวัติการแก้ไขแบบถาวรจาก staging area ไว้ใน repository

git log แสดงรายการที่ commit มาทั้งหมด
