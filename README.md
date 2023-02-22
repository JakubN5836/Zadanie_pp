
jakub@komputer MINGW64 ~
$ pwd
/c/Users/jakub

jakub@komputer MINGW64 ~
$ cd ~/CLionProjects/untitled7

jakub@komputer MINGW64 ~/CLionProjects/untitled7 (main)
$ ls
CMakeLists.txt  README.md  cmake-build-debug/  main.cpp

jakub@komputer MINGW64 ~/CLionProjects/untitled7 (main)
$ echo "# Zadanie_pp" >> README.md

jakub@komputer MINGW64 ~/CLionProjects/untitled7 (main)
$ git init
Reinitialized existing Git repository in C:/Users/jakub/CLionProjects/untitled7/.git/

jakub@komputer MINGW64 ~/CLionProjects/untitled7 (main)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

jakub@komputer MINGW64 ~/CLionProjects/untitled7 (main)
$ git commit -m "first commit"
[main 7d6ee76] first commit
 1 file changed, 1 insertion(+)

jakub@komputer MINGW64 ~/CLionProjects/untitled7 (main)
$ git branch -M main

jakub@komputer MINGW64 ~/CLionProjects/untitled7 (main)
$ git remote set-url origin https://github.com/JakubN5836/Zadanie_pp.git

jakub@komputer MINGW64 ~/CLionProjects/untitled7 (main)
$ git push -u origin main
Enumerating objects: 19, done.
Counting objects: 100% (19/19), done.
Delta compression using up to 12 threads
Compressing objects: 100% (15/15), done.
Writing objects: 100% (19/19), 2.01 KiB | 2.01 MiB/s, done.
Total 19 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), done.
To https://github.com/JakubN5836/Zadanie_pp.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

jakub@komputer MINGW64 ~/CLionProjects/untitled7 (main)
$
