Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)
$ git clone git@github.com:josecarb/campusciff.git
Cloning into 'campusciff'...
Enter passphrase for key '/c/Users/Jos� �ngel Carballo/.ssh/id_rsa':
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)
$ cd campusciff


Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
$ git add readme.md

Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
$ git commit -m "Ejercicio b�sico"
[master e9c9101] Ejercicio b�sico
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.md

Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
$ git add readme.md

Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
$ git commit -m "Commit inicial"
[master bd3d44c] Commit inicial
 1 file changed, 5 insertions(+)


Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
$ git push origin master
Enter passphrase for key '/c/Users/Jos� �ngel Carballo/.ssh/id_rsa':
Counting objects: 8, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 1.11 KiB | 0 bytes/s, done.
Total 8 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), done.
To github.com:josecarb/campusciff.git
   20dee1e..bd3d44c  master -> master

Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)
$ cd privada

Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)
$ git add "privado.txt"

Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)
$ git commit -m "Commit inicial"
[master bd3d44c] Commit inicial
 1 file changed, 5 insertions(+)

Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~/privada (master)
$ touch .gitignore

Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~/privada (master)
$ git config --global core.excludesfile ~/.gitignore_global


Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)
$ echo "privado.txt" >> .gitignore


Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)
$ echo "privada" >> .gitignore


Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)
$ cd campusciff

Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
$ git add 1.txt

Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
$ git commit -m "Fichero 1.txt"
[master b44ad10] Fichero 1.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 1.txt


Jos� �ngel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
$ git tag -a v0.1 -m " Versi�n 0.1"






