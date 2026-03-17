
EXACT@DESKTOP-H3MMDKJ MINGW64 ~
$ cd desktop

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop
$ cd git

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git config --global user.name "Jericho Gamboa"

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git config --global user.email "jerichogamboa111@gmail.com"

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git init
Reinitialized existing Git repository in C:/Users/EXACT/Desktop/Git/.git/

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ gid add .
bash: gid: command not found

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    .gitignore
        modified:   main.html
        modified:   text.txt

no changes added to commit (use "git add" and/or "git commit -a")

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git add .

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    .gitignore
        modified:   main.html
        modified:   text.txt


EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git commit -m "Upload Folder"
[main 75f75b0] Upload Folder
 3 files changed, 7 insertions(+), 3 deletions(-)
 delete mode 100644 .gitignore

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git remote add origin https://github.com/jerichogamboa111-create/March_17_2026-.git
error: remote origin already exists.

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git branch -M main

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git remote add origin https://github.com/jerichogamboa111-create/March_17_2026-.git
error: remote origin already exists.

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git push -u origin main
remote: Repository not found.
fatal: repository 'https://github.com/jerichogamboa111-create/Git.git/' not foun
d

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git remote add origin https://github.com/jerichogamboa111-create/March_17_2026-.git
error: remote origin already exists.

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ ^C

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git remote set-url origin https://github.com/jerichogamboa111-create/March_17_2026-.git

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git remote -v
origin  https://github.com/jerichogamboa111-create/March_17_2026-.git (fetch)
origin  https://github.com/jerichogamboa111-create/March_17_2026-.git (push)

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git push -u origin main
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (9/9), 645 bytes | 645.00 KiB/s, done.
Total 9 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/jerichogamboa111-create/March_17_2026-.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$
