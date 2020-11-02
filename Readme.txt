touch filename.txt
git init
ls
ls -a
git status
git add . || git add filename.txt
git commit -m "my first commit"
git status
git log

To check any type of difference in any file that you commit

git diff filename.txt

To save change to previous file data 

git checkout filename.txt