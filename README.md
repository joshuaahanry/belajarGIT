# belajarGIT
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT

user@DESKTOP-UJN34KV MINGW64 /d/GIT
$ git clone https://github.com/joshuaahanry/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

user@DESKTOP-UJN34KV MINGW64 /d/GIT
$ git init
Initialized empty Git repository in D:/GIT/.git/
Initialized empty Git repository in D:/GIT/.git/
bash: Initialized: command not found

user@DESKTOP-UJN34KV MINGW64 /d/GIT (master)
$ cd belajarGIT

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-git

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Git.txt


user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.email "hanryjosh@gmail.com"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.name "joshuaahanry"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git commit -m "tugasgit"
[Tugas-git 5270ba6] tugasgit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Git.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-Git.txt

no changes added to commit (use "git add" and/or "git commit -a")

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Tugas-Git.txt


user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git commit -m "tugasgit"
[Tugas-git cae8e14] tugasgit
 1 file changed, 1 insertion(+)

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-git
Updating cfde61b..cae8e14
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 536 bytes | 134.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/joshuaahanry/belajarGIT.git
   cfde61b..cae8e14  main -> main

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-html

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git config --global user.email "hanryjosh@gmail.com"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git config --global user.name "joshuaahanry"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git commit -m "tugashtml"
[Tugas-html 658ccd2] tugashtml
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Html.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-Html.txt

no changes added to commit (use "git add" and/or "git commit -a")

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git add ^C

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git commit -m "tugashtml"
[Tugas-html 0d9d17e] tugashtml
 1 file changed, 1 insertion(+)
user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-html
Updating cae8e14..0d9d17e
Fast-forward
 Tugas-Html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 519 bytes | 173.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/joshuaahanry/belajarGIT.git
   cae8e14..0d9d17e  main -> main

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-css

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git checkout Tugas-css
Already on 'Tugas-css'

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git config --global user.email "hanryjosh@gmail.com"
user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git config --global user.name "joshuaahanry"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git commit -m "tugascss"
[Tugas-css d44a040] tugascss
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Css.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-Css.txt

no changes added to commit (use "git add" and/or "git commit -a")

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git commit -m "tugascss"
[Tugas-css 7723a4b] tugascss
 1 file changed, 1 insertion(+)

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
nothing to commit, working tree clean

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-css
Updating 0d9d17e..7723a4b
Fast-forward
 Tugas-Css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 550 bytes | 55.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/joshuaahanry/belajarGIT.git
   0d9d17e..7723a4b  main -> main

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-js

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git config --global user.email "hanryjosh@gmail.com"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git config --global user.name "joshuaahanry"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git commit -m "tugasjs"
On branch Tugas-js
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-js.txt

nothing added to commit but untracked files present (use "git add" to track)

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git config --global user.email "hanryjosh@gmail.com"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git config --global user.name "joshuaahanry"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git commit -m "tugasjs"
[Tugas-js c445af8] tugasjs
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
nothing to commit, working tree clean

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-js
Updating 7723a4b..c445af8
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 278 bytes | 139.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/joshuaahanry/belajarGIT.git
   7723a4b..c445af8  main -> main

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-midProject

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.email "hanryjosh@gmail.com"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.name "joshuaahanry"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "tugasmidproject"
On branch Tugas-midProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-midProject.txt

nothing added to commit but untracked files present (use "git add" to track)

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "tugasmidproject"
On branch Tugas-midProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-MidProject.txt

nothing added to commit but untracked files present (use "git add" to track)

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git statusgit add Tugas-MidProject.txt
git: 'statusgit' is not a git command. See 'git --help'.

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.email "hanryjosh@gmail.com"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.name "joshuaahanry"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "tugasmidproject"
[Tugas-midProject f7cce4e] tugasmidproject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
nothing to commit, working tree clean

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-midProject
Updating c445af8..f7cce4e
Fast-forward
 Tugas-MidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 277 bytes | 138.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/joshuaahanry/belajarGIT.git
   c445af8..f7cce4e  main -> main

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-php

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git config --global user.email "hanryjosh@gmail.com"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git config --global user.name "joshuaahanry"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git commit -m "tugasphp"
[Tugas-php 112cdc1] tugasphp
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Php.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-Php.txt

no changes added to commit (use "git add" and/or "git commit -a")

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git commit -m "tugasphp"
[Tugas-php a8aa7ae] tugasphp
 1 file changed, 1 insertion(+)

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
nothing to commit, working tree clean

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-php
Updating f7cce4e..a8aa7ae
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 496 bytes | 165.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/joshuaahanry/belajarGIT.git
   f7cce4e..a8aa7ae  main -> main

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-finalProject

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git config --global user.email "hanryjosh@gmail.com"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git config --global user.name "joshuaahanry"

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m "tugasfinalproject"
[Tugas-finalProject f061185] tugasfinalproject
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-FinalProject.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-FinalProject.txt

no changes added to commit (use "git add" and/or "git commit -a")

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m "tugasfinalproject"
[Tugas-finalProject e101a89] tugasfinalproject
 1 file changed, 1 insertion(+)

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
nothing to commit, working tree clean

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-finalProject
Updating a8aa7ae..e101a89
Fast-forward
 Tugas-FinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 492 bytes | 164.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/joshuaahanry/belajarGIT.git
   a8aa7ae..e101a89  main -> main

user@DESKTOP-UJN34KV MINGW64 /d/GIT/belajarGIT (main)
$

