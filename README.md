###Tutorial-using-git
---------

##Khởi tạo git. trên folder máy tính: 
git init
---------

##Chuyển file từ working space đến stage area 
git add.
---------

##Khai báo người thao tác (lần đầu)
git config --global user.name "FIRST_NAME LAST_NAME"
git config --global user.email "MY_NAME@example.com"
---------

##Chuyển toàn bộ file từ stage area đến git local
git commit -m "tên trạng thái"
---------

##Tạo liên kết lên github online
git remote add origin (link github)
----------

##Đẩy code lên github
git push -u origin master
Những lần tiếp theo chỉ cần: git push

----------
git reset 
git remote -v
git pull --rebase
git init
git add -A
-----------

###or create a new repository on the command line
echo "# Step-for-Git-beginner" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/Helloiamwin/Step-for-Git-beginner.git

git push -u origin main

…or push an existing repository from the command line

git remote add origin https://github.com/Helloiamwin/Step-for-Git-beginner.git

git branch -M main

git push -u origin main

git commit -m "Add your commit"

git branch -M main

git push origin main --force
