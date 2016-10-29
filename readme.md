José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)

### git clone git@github.com:josecarb/campusciff.git

Cloning into 'campusciff'...
Enter passphrase for key '/c/Users/José Ángel Carballo/.ssh/id_rsa':
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)
### cd campusciff


José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
### git add readme.md

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
### git commit -m "Ejercicio básico"
[master e9c9101] Ejercicio básico
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.md

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
### git add readme.md

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
### git commit -m "Commit inicial"
[master bd3d44c] Commit inicial
 1 file changed, 5 insertions(+)


José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
### git push origin master
Enter passphrase for key '/c/Users/José Ángel Carballo/.ssh/id_rsa':
Counting objects: 8, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 1.11 KiB | 0 bytes/s, done.
Total 8 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), done.
To github.com:josecarb/campusciff.git
   20dee1e..bd3d44c  master -> master

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)
### cd privada

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)
### git add "privado.txt"

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)
### git commit -m "Commit inicial"
[master bd3d44c] Commit inicial
 1 file changed, 5 insertions(+)

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/privada (master)
### touch .gitignore

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/privada (master)
### git config --global core.excludesfile ~/.gitignore_global


José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)
### echo "privado.txt" >> .gitignore


José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)
### echo "privada" >> .gitignore


José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~ (master)
### cd campusciff

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
### git add 1.txt

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
### git commit -m "Fichero 1.txt"
[master b44ad10] Fichero 1.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 1.txt


José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
### git tag -a v0.1 -m " Versión 0.1"


|    Nombre    |     Github     |
| ------------ | -------------- |
| Adolfo Sanz  |  asanzdiego    | 
| Miguel David |  migueldmonzon | 



José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
### git branch v0.2

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
### git checkout v0.2
Switched to branch 'v0.2'

### git add "2.txt"

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (v0.2)
###  git commit -m "Rama2, fichero 2.txt"
[v0.2 79c2710] Rama2, fichero 2.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 2.txt


José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (v0.2)
###  git push origin master


José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (v0.2)
###  git checkout master
M       readme.md
Switched to branch 'master'
Your branch is up-to-date with 'origin/master'.

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
###  git merge v0.2
Updating efed6da..79c2710
Fast-forward
 2.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 2.txt


José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
###  git add 1.txt

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
###  git commit -m "Cambios 1.txt"
[master c6d69c4] Cambios 1.txt
 1 file changed, 1 insertion(+)

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
###  git checkout v0.2
M       readme.md
Switched to branch 'v0.2'

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (v0.2)
###  git add 2.txt

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (v0.2)
###  git commit -m "Cambios 2.txt"
[v0.2 a6cfc59] Cambios 2.txt
 1 file changed, 1 insertion(+)

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (v0.2)
###  git checkout master
M       readme.md
Switched to branch 'master'
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
###  git merge v0.2
Merge made by the 'recursive' strategy.
 2.txt | 1 +
 1 file changed, 1 insertion(+)

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
###  git branch
* master
  v0.2


José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
###  git add 1.txt

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
###  git commit -m "Cambios 1.txt"
[master 8437ce5] Cambios 1.txt
 1 file changed, 4 insertions(+)

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
###  git merge v0.2
Already up-to-date.

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
###  git tag -a v0.2 -m " Versión v0.2"

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
###  git branch -d v0.2
Deleted branch v0.2 (was a6cfc59).

José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
###  git log
commit 8437ce5ab4b1a48c938dd45458d1314b76770533
Author: josecarb <j.a.carballosanchez@gmail.com>
Date:   Sat Oct 29 19:25:03 2016 +0200

    Cambios 1.txt

commit adc4ee183b8155bc57805bdb9f1a35ace4dec112
Merge: c6d69c4 a6cfc59
Author: josecarb <j.a.carballosanchez@gmail.com>
Date:   Sat Oct 29 19:22:54 2016 +0200

    Merge branch 'v0.2'

commit a6cfc593544a66abc7907ed485140bb7645b37ae
Author: josecarb <j.a.carballosanchez@gmail.com>
Date:   Sat Oct 29 19:22:35 2016 +0200

    Cambios 2.txt

commit c6d69c4c810974ad3b831c1ec4408c19762f862e
Author: josecarb <j.a.carballosanchez@gmail.com>
Date:   Sat Oct 29 19:21:53 2016 +0200

   José Ángel Carballo@LAPTOP-KR38OL89 MINGW64 ~/campusciff (master)
###  git clone https://github.com/asanzdiego/campusciff2016
Cloning into 'campusciff2016'...
remote: Counting objects: 74, done.
remote: Total 74 (delta 0), reused 0 (delta 0), pack-reused 74
Unpacking objects: 100% (74/74), done.


