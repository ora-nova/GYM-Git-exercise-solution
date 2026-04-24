BUNDLE 1
Exercise 1
````
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git --version
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git config --global core.editor "code --wait"
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git config --global user.name "ora-nova"
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git config --global user.email "shyakauwaseroanova@gmail.com"
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git config --global init.defaultBranch master
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ mkdir myproject
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ cd myproject
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git init
create index.html in vs code and saved it in folder(myproject)
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git config --global init.defaultBranch main
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git branch -m master main
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git add index.html
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git commit -m "add index file"
created repo in github named"GYM Git exercise solution"
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git remote add origin https://github.com/ora-nova/GYM-Git-exercise-solution
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git push -u origin main
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git  branch dev
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git checkout dev
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git branch test
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git checkout test
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git checkout dev
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git branch -d test
````
exercise 2
````
create a  home.html in vs code and added html changes and saved it in myproject
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git stash -u
create a  home.html in vs code and added html changes and saved it in myproject
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git stash -u
create a  home.html in vs code and added html changes and saved it in myproject
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git stash -u
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git stash pop stash@{1}
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git stash pop stash@{2}
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git add --all
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git commit -m "add  about and home page"
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git push origin main
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git stash pop
tech heaven@DESKTOP-PVBNUBJ MINGW64 $ git reset --hard 11cf22e
````
BUNDLE 2
Exercise 1
````
tech heaven@DESKTOP-PVBNUBJ MINGW64 ~ (main)
$ cd myproject

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/myproject (main)
$ git branch ft/bundle-2

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/myproject (main)
$ git checkout ft/bundle-2
Switched to branch 'ft/bundle-2'

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/myproject (ft/bundle-2)
$ touch service.html

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/myproject (ft/bundle-2)
$ git add service.html

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/myproject (ft/bundle-2)
$ git commit -m "add service page"
[ft/bundle-2 aff83b0] add service page
 1 file changed, 13 insertions(+)
 create mode 100644 service.html

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/myproject (ft/bundle-2)
$ git push origin ft/bundle-2
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 2 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 936 bytes | 234.00 KiB/s, done.
Total 7 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), done.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/ora-nova/GYM-Git-exercise-solution/pull/new/ft/bundle-2
remote:
To https://github.com/ora-nova/GYM-Git-exercise-solution
 * [new branch]      ft/bundle-2 -> ft/bundle-2

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/myproject (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

tech heaven@DESKTOP-PVBNUBJ MINGW64 ~/myproject (main)
$ git pull origin main
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (5/5), 2.31 KiB | 71.00 KiB/s, done.
From https://github.com/ora-nova/GYM-Git-exercise-solution
 * branch            main       -> FETCH_HEAD
   11cf22e..289a32f  main       -> origin/main
Updating 11cf22e..289a32f
Fast-forward
 README.md    | 43 +++++++++++++++++++++++++++++++++++++++++++
 service.html | 13 +++++++++++++
 2 files changed, 56 insertions(+)
 create mode 100644 README.md
 create mode 100644 service.html
````
