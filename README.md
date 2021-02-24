# wired-brain-recipes
Holger Buckemeyer@BGWSDEV04 MINGW64 /c/users/holger buckemeyer/git_test (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        git up an running.txt

nothing added to commit but untracked files present (use "git add" to track)

Holger Buckemeyer@BGWSDEV04 MINGW64 /c/users/holger buckemeyer/git_test (master)
$ git add  "git up an running.txt"

Holger Buckemeyer@BGWSDEV04 MINGW64 /c/users/holger buckemeyer/git_test (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   git up an running.txt

Holger Buckemeyer@BGWSDEV04 MINGW64 /c/users/holger buckemeyer/git_test (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   git up an running.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md


Holger Buckemeyer@BGWSDEV04 MINGW64 /c/users/holger buckemeyer/git_test (master)
$ git add README.md
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

Holger Buckemeyer@BGWSDEV04 MINGW64 /c/users/holger buckemeyer/git_test (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   git up an running.txt

Holger Buckemeyer@BGWSDEV04 MINGW64 /c/users/holger buckemeyer/git_test (master)
$ git status -s
M  README.md
A  "git up an running.txt"

Holger Buckemeyer@BGWSDEV04 MINGW64 /c/users/holger buckemeyer/git_test (master)
$ git diff --staged
diff --git a/README.md b/README.md
index 62c4fee..c93fc8a 100644
--- a/README.md
+++ b/README.md
@@ -1 +1,53 @@
 # wired-brain-recipes
+Holger Buckemeyer@BGWSDEV04 MINGW64 /c/users/holger buckemeyer/git_test (master)
+$ git status
