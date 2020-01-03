
ch.1<br>
git checkout -b feature/readme<br>
git add README.md<br>
git commit -m "Fixed readme file"<br>
git checkout develop<br>
git merge feature/readme<br>
git push origin develop<br>


ch.2<br>
git checkout feature/readme<br>
git add README.md<br>
git commit -m "Fixed readme file"<br>
git checkout develop<br>
git checkout -b feature/welcome<br>
git add welcome.py<br>
git commit -m "welcome.py"<br>
git checkout develop<br>
git merge feature/welcome<br>
git push origin develop<br>

confirm file<br>
readme.md not changed<br>
welcome.py changed<br>

ch.3<br>
github pull request base : master <-- compare : develop<br>
confirm merge<br>

confirm remote repository master branch<br>
pull request contents (master == develop)<br>

ch4<br>
local 1 git add, commit 2 time<br>
local 2 git clone repository<br>
local 2 git add commit<br>
local 2 git push origin develop<br>


