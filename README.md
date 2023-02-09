pabs@DESKTOP-SFKUONT MINGW64 ~

$ git --version
git version 2.39.1.windows.1

pabs@DESKTOP-SFKUONT MINGW64 ~

$ git config --global user .name
error: key does not contain a section: user

pabs@DESKTOP-SFKUONT MINGW64 ~


pabs@DESKTOP-SFKUONT MINGW64 ~
$ git config --global user.name
alex2002djnkl


pabs@DESKTOP-SFKUONT MINGW64 ~

$ git config --global user.mail
alexpavo2005@ginebro.cat

pabs@DESKTOP-SFKUONT MINGW64 ~

$ git config --global user.name <nomUsuariGithub>

bash: syntax error near unexpected token `newline'

pabs@DESKTOP-SFKUONT MINGW64 ~

$ git config --global user.name alex2002djnkl

pabs@DESKTOP-SFKUONT MINGW64 ~

$ git config --global user.mail alexpavo2005@ginebro.cat

pabs@DESKTOP-SFKUONT MINGW64 ~

$  mkdir SMX2-2022-2023

pabs@DESKTOP-SFKUONT MINGW64 ~

$ ^[[200~cd SMX2-2022-2023
bash: $'\E[200~cd': command not found

pabs@DESKTOP-SFKUONT MINGW64 ~

$ cd SMX2-2022-2023

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023

$ mkdir MP07

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023

$ cd MP07

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ git commit -m "first commit"
[main (root-commit) 5a69923] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ git remote add origin
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fet


pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ git remote add origin https://github.com/alex2002djnkl

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ git remote add origin https://github.com/alex2002djnkl-A015U.git
error: remote origin already exists.

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ git remote rm
usage: git remote remove <name>


pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ git remote add origin https://github.com/alex2002djnkl-A015U.git
error: remote origin already exists.

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ git remote -v
origin  https://github.com/alex2002djnkl (fetch)
origin  https://github.com/alex2002djnkl (push)

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ git remote set-url origin https://github.com/alex2002djnkl/Pavo-A01

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ git remote -v
origin  https://github.com/alex2002djnkl/Pavo-A015U-.git (fetch)
origin  https://github.com/alex2002djnkl/Pavo-A015U-.git (push)

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ git remote set-url origin https://github.com/alex2002djnkl/Pavo-A01

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ git remote set-url origin https://github.com/alex2002djnkl/Pavo-A01

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ git remote -v
origin  https://github.com/alex2002djnkl/Pavo-A015U-.git (fetch)
origin  https://github.com/alex2002djnkl/Pavo-A015U-.git (push)

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 232 bytes | 232.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/alex2002djnkl/Pavo-A015U-.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ pwd
/c/Users/pabs/SMX2-2022-2023/MP07

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ mkdir Pavo-A015U

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ CD Pavo-A015U/
bash: CD: command not found

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07 (main)
$ cd Pavo-A015U/

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ echo "# Pavo-A015U" >>
bash: syntax error near unexpected token `newline'

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ echo "# Pavo-A015U"
# Pavo-A015U

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ echo "# Pavo-A015U" >> README.md

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ ls -la
total 1
drwxr-xr-x 1 pabs 197121  0 Feb  3 12:42 ./
drwxr-xr-x 1 pabs 197121  0 Feb  3 12:40 ../
-rw-r--r-- 1 pabs 197121 13 Feb  3 12:42 README.md

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ git init
Initialized empty Git repository in C:/Users/pabs/SMX2-2022-2023/MP07/Pavo-A015U/.git/

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ ls -la
total 5
drwxr-xr-x 1 pabs 197121  0 Feb  3 12:43 ./
drwxr-xr-x 1 pabs 197121  0 Feb  3 12:40 ../
drwxr-xr-x 1 pabs 197121  0 Feb  3 12:43 .git/
-rw-r--r-- 1 pabs 197121 13 Feb  3 12:42 README.md

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ ls -la .git
total 11
drwxr-xr-x 1 pabs 197121   0 Feb  3 12:43 ./
drwxr-xr-x 1 pabs 197121   0 Feb  3 12:43 ../
-rw-r--r-- 1 pabs 197121  21 Feb  3 12:43 HEAD
-rw-r--r-- 1 pabs 197121 130 Feb  3 12:43 config
-rw-r--r-- 1 pabs 197121  73 Feb  3 12:43 description
drwxr-xr-x 1 pabs 197121   0 Feb  3 12:43 hooks/
drwxr-xr-x 1 pabs 197121   0 Feb  3 12:43 info/
drwxr-xr-x 1 pabs 197121   0 Feb  3 12:43 objects/
drwxr-xr-x 1 pabs 197121   0 Feb  3 12:43 refs/

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ code hora_01.html

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ ls -la
total 6
drwxr-xr-x 1 pabs 197121   0 Feb  3 12:45 ./
drwxr-xr-x 1 pabs 197121   0 Feb  3 12:40 ../
drwxr-xr-x 1 pabs 197121   0 Feb  3 12:43 .git/
-rw-r--r-- 1 pabs 197121  13 Feb  3 12:42 README.md
-rw-r--r-- 1 pabs 197121 300 Feb  3 12:45 hora_01.html

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ git add hora_01.html



pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)

 git commit -m "Creem i afegim el fitxer hora_01.html"

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ git log
commit 796637950c1ec33658a31cf5e84cc863f1d9864e (HEAD -> main)
Author: alex2002djnkl <alexpavo2005@ginebro.cat>
Date:   Thu Feb 9 10:19:45 2023 +0100

    Creem i afegim el fitxer hora_01.html

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ git log --oneline
7966379 (HEAD -> main) Creem i afegim el fitxer hora_01.html

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ git ls-tree --name-only -r 7966379
hora_01.html

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ ls -la
total 6
drwxr-xr-x 1 pabs 197121   0 Feb  3 12:45 ./
drwxr-xr-x 1 pabs 197121   0 Feb  3 12:40 ../
drwxr-xr-x 1 pabs 197121   0 Feb  9 10:20 .git/
-rw-r--r-- 1 pabs 197121  13 Feb  3 12:42 README.md
-rw-r--r-- 1 pabs 197121 300 Feb  3 12:45 hora_01.html

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   README.md

pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ git remote add origin https://github.com/alex2002djnkl/pabs.git


pabs@DESKTOP-SFKUONT MINGW64 ~/SMX2-2022-2023/MP07/Pavo-A015U (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 429 bytes | 429.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/alex2002djnkl/pabs.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

