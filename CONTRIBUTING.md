1 - CONCOCTION FOR REPO
-
- git remote -v
- git remote remove origin
- git remote add origin https://github.com/obadaalh/ENGPI.git
- git pull

2 - push code 
-
- git checkout master
- git pull origin master

2.1 editing code before 
-
- git status
- git add .
- git commit -m "feat: update 2 section ..."

2.2 editing code after
-
- git push -u origin master

3 - create pull Request 
-
- New pull Request 
- base: engpi-live
- compare: master
