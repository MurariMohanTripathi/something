#this is just learning git and github and nothing else so don't intervain

git remote add origin https://github.com/MurariMohanTripathi/something.git

PS D:\GIT\localRepo> git add .
PS D:\GIT\localRepo> git commit -m "add something"


PS D:\GIT\localRepo> git remote -v
origin  https://github.com/MurariMohanTripathi/something.git (fetch)
origin  https://github.com/MurariMohanTripathi/something.git (push)

PS D:\GIT\localRepo> git branch

PS D:\GIT\localRepo> git push -u origin main


PS D:\GIT\localRepo> git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
PS D:\GIT\localRepo> git add .
PS D:\GIT\localRepo> git commit -m "readme"
[main ad64c53] readme
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
PS D:\GIT\localRepo> git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 377 bytes | 377.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MurariMohanTripathi/something.git
   6c55da6..ad64c53  main -> main

   # => to create New branch we  can simply use the steps below
   PS D:\GIT\localRepo> git branch
* main
PS D:\GIT\localRepo> git checkout -b feature1
Switched to a new branch 'feature1'
PS D:\GIT\localRepo> git branch
* feature1
  main
PS D:\GIT\localRepo> git checkout -b feature2

to exit any branch or to switch between branch
use the code below
:
=> git checkout main
here main depicts the branch to which user wants to switch