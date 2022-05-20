# Demo

Some description!
Create SSH Key (https://juejin.cn/post/6844903904035995655)
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
$ ls | grep keyname
$ cat keyname.pub

git clone "SSH/HTTPS Link"
//edit files and then do: 
git add .  ## update what will be committed
git status  ## changes to be committed
// COMMIT NEW FILE: 
git commit -m "Added index.html" -m "Description"
git push origin main

Problrm: git Please tell me who you are
Solve: git config --global user.email "youremail"

# when create a new fold locally, create new reposiory online and do following: 
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:Yifan-SD/demo-repo2.git
git push -u origin main  // use 'git push' from now on
git remote -v //see all the connection

//TL;DR – How to Exit Vim
Press ESC once (sometimes twice)
Make sure you are using the English input method
The next step depends on the current status and your expectations:
If you didn't make any changes, type :q and press Enter/return
If you made some changes and would like to keep them, type :wq and press Enter/return
If you made some changes and would rather discard them, type :q! and press Enter/return

## Local Development

1. Open index.html in your browser