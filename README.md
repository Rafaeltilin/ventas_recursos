# ventas_recursos
de examen
LAB-PC30@DESKTOP-N7HVI32 MINGW64 ~
$ cd c:

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c
$ cd ventas_recursos

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git init
Reinitialized existing Git repository in C:/ventas_recursos/.git/

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git branch
* main
  produccion
  recurso_humano
  ventas

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git checkout produccion
Switched to branch 'produccion'

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ touch produccion\ prima.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ touch productofinal.tx

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ git checkout recurso_humano
Switched to branch 'recurso_humano'

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (recurso_humano)
$ touch recurso_humano\ despido.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (recurso_humano)
$ touch ventas\ ganancias.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (recurso_humano)
$ touch ventas\ tiendas.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (recurso_humano)
$ git checkout recurso_humano
Already on 'recurso_humano'

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (recurso_humano)
$ git checkout producción
error: pathspec 'producción' did not match any file(s) known to git

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (recurso_humano)
$ git checkout produccion
Switched to branch 'produccion'

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ touch produccion\ materia prima.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ touch produccion\ productofinal.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ touch produccion\ imagenproducto.png

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ git checkout recurso_humano
Switched to branch 'recurso_humano'

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (recurso_humano)
$ touch recurso_humano\ empleados.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (recurso_humano)
$ git checkout ventas
Switched to branch 'ventas'

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ touch ventas\ tiendas.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git add .

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git commit -m "agregue archivos y contenido a los 3 branch"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'LAB-PC30@DESKTOP-N7HVI32.(none)')

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git commit -m "agregue archivos y contenido a branch produccion"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'LAB-PC30@DESKTOP-N7HVI32.(none)')

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git config --global user.email "tic-280074@utnay.edu.mx"

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git config --global user.name Rafaeltilin

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git commit -m "agregue archivos y contenido a branch produccion"
[ventas 4af5a02] agregue archivos y contenido a branch produccion
 6 files changed, 8 insertions(+)
 create mode 100644 prima.txt
 create mode 100644 produccion imagenproducto.png
 create mode 100644 produccion materia
 create mode 100644 produccion productofinal.txt
 create mode 100644 recurso_humano empleados.txt
 create mode 100644 ventas tiendas.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git commit -m "agregue archivos y contenido a branch recurso_humano"
On branch ventas
nothing to commit, working tree clean

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git commit -m "agregue archivos y contenido a branch ventas"
On branch ventas
nothing to commit, working tree clean

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git commit -m "agregue archivos y contenido a branch produccion"
On branch ventas
nothing to commit, working tree clean

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git push origin ventas
info: please complete authentication in your browser...
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (5/5), 510 bytes | 510.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'ventas' on GitHub by visiting:
remote:      https://github.com/Rafaeltilin/ventas_recursos/pull/new/ventas
remote:
To https://github.com/Rafaeltilin/ventas_recursos.git
 * [new branch]      ventas -> ventas

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git push origin produccion
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'produccion' on GitHub by visiting:
remote:      https://github.com/Rafaeltilin/ventas_recursos/pull/new/produccion
remote:
To https://github.com/Rafaeltilin/ventas_recursos.git
 * [new branch]      produccion -> produccion

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git push origin recurso_humano
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'recurso_humano' on GitHub by visiting:
remote:      https://github.com/Rafaeltilin/ventas_recursos/pull/new/recurso_humano
remote:
To https://github.com/Rafaeltilin/ventas_recursos.git
 * [new branch]      recurso_humano -> recurso_humano

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git checkout produccion
Switched to branch 'produccion'

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ touch produccion\ materia prima.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ touch produccion\ imagenproducto.png

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ touch produccion\ productofinal.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ git commit -m "agregue archivos y contenido a branch produccion"
On branch produccion
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        prima.txt
        produccion imagenproducto.png
        produccion materia
        produccion productofinal.txt

nothing added to commit but untracked files present (use "git add" to track)

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ git add .

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ git commit -m "agregue archivos y contenido a branch produccion"
[produccion 9ea90d3] agregue archivos y contenido a branch produccion
 4 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 prima.txt
 create mode 100644 produccion imagenproducto.png
 create mode 100644 produccion materia
 create mode 100644 produccion productofinal.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ git push origin produccion
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 350 bytes | 350.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Rafaeltilin/ventas_recursos.git
   6ac7c13..9ea90d3  produccion -> produccion

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ git checkout recurso_humano
Switched to branch 'recurso_humano'

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (recurso_humano)
$ touch recurso_humano\ empleados.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (recurso_humano)
$ git commit -m "agregue archivos y contenido a branch recurso_humano"
On branch recurso_humano
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        recurso_humano empleados.txt

nothing added to commit but untracked files present (use "git add" to track)

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (recurso_humano)
$ git add .

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (recurso_humano)
$ git commit -m "agregue archivos y contenido a branch recurso_humano"
[recurso_humano c309dce] agregue archivos y contenido a branch recurso_humano
 1 file changed, 5 insertions(+)
 create mode 100644 recurso_humano empleados.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (recurso_humano)
$ git push origin recurso_humano
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 358 bytes | 358.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Rafaeltilin/ventas_recursos.git
   6ac7c13..c309dce  recurso_humano -> recurso_humano

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (recurso_humano)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git merge produccion
Updating 6ac7c13..9ea90d3
Fast-forward
 prima.txt                     | 0
 produccion imagenproducto.png | 0
 produccion materia            | 0
 produccion productofinal.txt  | 0
 4 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 prima.txt
 create mode 100644 produccion imagenproducto.png
 create mode 100644 produccion materia
 create mode 100644 produccion productofinal.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git push origin main
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Rafaeltilin/ventas_recursos.git
   6ac7c13..9ea90d3  main -> main

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ touch recurso_humano\ empleados.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git diff recurso_humano^..recurso_humano empleados.txt
fatal: ambiguous argument 'empleados.txt': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git diff recurso_humano^..recurso_humano empleados.txt
fatal: ambiguous argument 'empleados.txt': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git ls-tree recurso_humano -- empleados.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git ls-tree recurso_humano -- recurso_humano empleados.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git push origin main
Everything up-to-date

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git commit -m "agregue archivos y contenido a branch recurso_humano"
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        recurso_humano empleados.txt

nothing added to commit but untracked files present (use "git add" to track)

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git add .

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git commit -m "agregue archivos y contenido a branch recurso_humano"
[main 1d34b9c] agregue archivos y contenido a branch recurso_humano
 1 file changed, 10 insertions(+)
 create mode 100644 recurso_humano empleados.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git push origin main
Everything up-to-date

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (main)
$ git push origin main
Merge branch 'recurso_humano'

# Conflicts:
#       recurso_humano empleados.txt
#
# It looks like you may be committing a merge.
# If this is not correct, please run
#       git update-ref -d MERGE_HEAD
# and try again.


# Please enter the commit message for your changes. Lines starting
# with '#' will be ignored, and an empty message aborts the commit.
#
# On branch main
# Your branch is up to date with 'origin/main'.
#
# All conflicts fixed but you are still merging.
#
# Changes to be committed:
#       modified:   recurso_humano empleados.txt
#
.git/COMMIT_EDITMSG [unix] (17:36 12/06/2023)                            1,1 All"/c/ventas_recursos/.git/COMMIT_EDITMSG" [unix] 22L, 538B
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (5/5), 510 bytes | 510.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'ventas' on GitHub by visiting:
remote:      https://github.com/Rafaeltilin/ventas_recursos/pull/new/ventas
remote:
To https://github.com/Rafaeltilin/ventas_recursos.git
 * [new branch]      ventas -> ventas

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git push origin produccion
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'produccion' on GitHub by visiting:
remote:      https://github.com/Rafaeltilin/ventas_recursos/pull/new/produccion
remote:
To https://github.com/Rafaeltilin/ventas_recursos.git
 * [new branch]      produccion -> produccion

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git push origin recurso_humano
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'recurso_humano' on GitHub by visiting:
remote:      https://github.com/Rafaeltilin/ventas_recursos/pull/new/recurso_humano
remote:
To https://github.com/Rafaeltilin/ventas_recursos.git
 * [new branch]      recurso_humano -> recurso_humano

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (ventas)
$ git checkout produccion
Switched to branch 'produccion'

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ touch produccion\ materia prima.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ touch produccion\ imagenproducto.png

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ touch produccion\ productofinal.txt

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ git commit -m "agregue archivos y contenido a branch produccion"
On branch produccion
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        prima.txt
        produccion imagenproducto.png
        produccion materia
        produccion productofinal.txt

nothing added to commit but untracked files present (use "git add" to track)

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ git add .

LAB-PC30@DESKTOP-N7HVI32 MINGW64 /c/ventas_recursos (produccion)
$ git commit -m "agregue archivos y contenido a branch produccion"
[produccion 9ea90d3] agregue archivos # git update-ref -d MERGE_HEAD
# and try again.


# Please enter the commit message for your changes. Lines starting
# with '#' will be ignored, and an empty message aborts the commit.
.git/COMMIT_EDITMSG[+] [unix] (17:36 12/06/2023)                                                                                                                                                                                                                     216,38 94%recording @q
