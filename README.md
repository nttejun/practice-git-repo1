
Hello world!!

Updated

ch.1
git checkout -b feature/readme
git add README.md
git commit -m "Fixed readme file"
git checkout develop
git merge feature/readme
git push origin develop

ch.2
git checkout feature/readme
git add README.md
git commit -m "Fixed readme file"
git checkout develop
git checkout -b feature/welcome
git add welcome.py
git commit -m "welcome.py"
git checkout develop
git merge feature/welcome
git push origin develop

confirm file
readme.md not changed
welcome.py changed 
