
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
$ git branch jericho

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git branch
  jericho
* main

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git checkout jericho
Switched to branch 'jericho'

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (jericho)
$ git branch
* jericho
  main

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (jericho)
$ git status
On branch jericho
nothing to commit, working tree clean

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (jericho)
$ git status
On branch jericho
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   text.txt

no changes added to commit (use "git add" and/or "git commit -a")

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (jericho)
$ git add .

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (jericho)
$ git commit -m "updated text file"
[jericho 36f0917] updated text file
 1 file changed, 2 insertions(+), 1 deletion(-)

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (jericho)
$ git status
On branch jericho
nothing to commit, working tree clean

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (jericho)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$ git checkout jericho
Switched to branch 'jericho'

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (jericho)
$ git checkout mai
error: pathspec 'mai' did not match any file(s) known to git

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (jericho)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

















----new one-------------





EXACT@DESKTOP-H3MMDKJ MINGW64 ~
$ cd desktop

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop
$ cd Git

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/Git (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        DBcreate.png
        de9056aa-f316-4ab2-8eff-92105dce136c (1).jpg
        de9056aa-f316-4ab2-8eff-92105dce136c.jpg
        download.jpg

nothing added to commit but untracked files present (use "git add" to track)

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/Git (main)
$ git add .

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/Git (main)
$ git commit -m "Picture Files"
[main 4bc90cf] Picture Files
 4 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 DBcreate.png
 create mode 100644 de9056aa-f316-4ab2-8eff-92105dce136c (1).jpg
 create mode 100644 de9056aa-f316-4ab2-8eff-92105dce136c.jpg
 create mode 100644 download.jpg

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/Git (main)
$ git push origin main
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 8 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (10/10), 292.64 KiB | 29.26 MiB/s, done.
Total 10 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/jerichogamboa111-create/March_17_2026-.git
   93b559e..4bc90cf  main -> main

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/Git (main)
$ cd /

EXACT@DESKTOP-H3MMDKJ MINGW64 /
$ cd desktop
bash: cd: desktop: No such file or directory

EXACT@DESKTOP-H3MMDKJ MINGW64 /
$ cd

EXACT@DESKTOP-H3MMDKJ MINGW64 ~
$ cd deskto
bash: cd: deskto: No such file or directory

EXACT@DESKTOP-H3MMDKJ MINGW64 ~
$ cd desktop

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop
$ git clone  https://github.com/renzlyako/Lesson.git
Cloning into 'Lesson'...
remote: Enumerating objects: 19, done.
remote: Counting objects: 100% (19/19), done.
remote: Compressing objects: 100% (16/16), done.
remote: Total 19 (delta 0), reused 19 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (19/19), done.

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop
$ git status
fatal: not a git repository (or any of the parent directories): .git

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop
$ cd lesson

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/lesson (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   main.txt

no changes added to commit (use "git add" and/or "git commit -a")

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/lesson (main)
$ git add .

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/lesson (main)
$ git commit -m "NIBOMBOCLAT"
[main bef61eb] NIBOMBOCLAT
 1 file changed, 1 insertion(+), 1 deletion(-)

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/lesson (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 296 bytes | 296.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/renzlyako/Lesson.git
   1993ac8..bef61eb  main -> main

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/lesson (main)
$

EXACT@DESKTOP-H3MMDKJ MINGW64 ~/desktop/git (main)
$
