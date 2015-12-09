# MyProject

# first time
git init
git add README.md
git commit -m "first commit" 
git remote add origin https://github.com/assamal/MyProject.git
git push -u origin master

#subsequent time
git add README.dm
git commit -m "subsequent commit" 
git push

git commit -am "third commit"

git remote -v
git push

#how to fetch a repository from github
git clone https://github.com/bethrobson/Head-First-JavaScript-Programming.git

# how to delete files in github repository
git rm file1.txt
git commit -m "rempove file1.txt"
git push -u origin master

# how to add folders and files in github repository
git add * or git add file.txt or gtit add <folder>/*


git help
git help tutorial