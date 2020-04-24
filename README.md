# Ejercicio-git
esta es la prueba del ejercicio



C:\Users\Ainhoa>cd C:\Users\Ainhoa\Desktop\MU\git\version 2

C:\Users\Ainhoa\Desktop\MU\git\version 2>dir/A
 El volumen de la unidad C es Windows
 El número de serie del volumen es: 2CC6-3815

 Directorio de C:\Users\Ainhoa\Desktop\MU\git\version 2

24/04/2020  12:36    <DIR>          .
24/04/2020  12:36    <DIR>          ..
               0 archivos              0 bytes
               2 dirs  54.951.108.608 bytes libres

C:\Users\Ainhoa\Desktop\MU\git\version 2>git init
Initialized empty Git repository in C:/Users/Ainhoa/Desktop/MU/git/version 2/.git/

C:\Users\Ainhoa\Desktop\MU\git\version 2>git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

C:\Users\Ainhoa\Desktop\MU\git\version 2>git add .

C:\Users\Ainhoa\Desktop\MU\git\version 2>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   data.csv
        new file:   programa.R
        new file:   readme.md


C:\Users\Ainhoa\Desktop\MU\git\version 2>git commit - "Añadimos los ficheros originales"
error: pathspec '-' did not match any file(s) known to git
error: pathspec 'Añadimos los ficheros originales' did not match any file(s) known to git

C:\Users\Ainhoa\Desktop\MU\git\version 2>git commit -m "Añadimos los ficheros originales"
[master (root-commit) df12109] Añadimos los ficheros originales
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 data.csv
 create mode 100644 programa.R
 create mode 100644 readme.md

C:\Users\Ainhoa\Desktop\MU\git\version 2>git commit -m "modificamos readme.md"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\Ainhoa\Desktop\MU\git\version 2>git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\Ainhoa\Desktop\MU\git\version 2>dir/A
 El volumen de la unidad C es Windows
 El número de serie del volumen es: 2CC6-3815

 Directorio de C:\Users\Ainhoa\Desktop\MU\git\version 2

24/04/2020  12:38    <DIR>          .
24/04/2020  12:38    <DIR>          ..
24/04/2020  12:41    <DIR>          .git
24/04/2020  12:37                 0 data.csv
24/04/2020  12:38                 0 programa.R
24/04/2020  12:40               109 readme.md
               3 archivos            109 bytes
               3 dirs  54.948.552.704 bytes libres

C:\Users\Ainhoa\Desktop\MU\git\version 2>git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\Ainhoa\Desktop\MU\git\version 2>git commit -am "añado los ficheros"
[master 30ffd0f] añado los ficheros
 1 file changed, 6 insertions(+)

C:\Users\Ainhoa\Desktop\MU\git\version 2>git log
commit 30ffd0fc5fc10f88265fceb01b08a80d5bac096d (HEAD -> master)
Author: ainhoa <ainhoaparedes2001@gmail.com>
Date:   Fri Apr 24 12:41:54 2020 +0200

    a<C3><B1>ado los ficheros

commit df121097ffa4a8ed7f08f55c7fe1153bbcda70cc
Author: ainhoa <ainhoaparedes2001@gmail.com>
Date:   Fri Apr 24 12:39:09 2020 +0200

    A<C3><B1>adimos los ficheros originales

C:\Users\Ainhoa\Desktop\MU\git\version 2>git lg
* 30ffd0f (HEAD -> master) a<C3><B1>ado los ficheros
* df12109 A<C3><B1>adimos los ficheros originales

C:\Users\Ainhoa\Desktop\MU\git\version 2>git branch nueva-rama

C:\Users\Ainhoa\Desktop\MU\git\version 2>git branch
* master
  nueva-rama

C:\Users\Ainhoa\Desktop\MU\git\version 2>git status
On branch master
nothing to commit, working tree clean

C:\Users\Ainhoa\Desktop\MU\git\version 2>git commit -am "modifico lineaa 3 de readme.md"
[master 2428091] modifico lineaa 3 de readme.md
 1 file changed, 2 insertions(+), 1 deletion(-)

C:\Users\Ainhoa\Desktop\MU\git\version 2>git checkout master
Already on 'master'

C:\Users\Ainhoa\Desktop\MU\git\version 2>git branch
* master
  nueva-rama

C:\Users\Ainhoa\Desktop\MU\git\version 2>git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\Ainhoa\Desktop\MU\git\version 2>git commit -am "modifico readme.md"
[master a4213b2] modifico readme.md
 1 file changed, 3 insertions(+), 1 deletion(-)

C:\Users\Ainhoa\Desktop\MU\git\version 2>git lg
* a4213b2 (HEAD -> master) modifico readme.md
* 2428091 modifico lineaa 3 de readme.md
* 30ffd0f (nueva-rama) a<C3><B1>ado los ficheros
* df12109 A<C3><B1>adimos los ficheros originales

C:\Users\Ainhoa\Desktop\MU\git\version 2>git merge nueva-rama
Already up to date.

C:\Users\Ainhoa\Desktop\MU\git\version 2>git status
On branch master
nothing to commit, working tree clean

C:\Users\Ainhoa\Desktop\MU\git\version 2>git merge nueva-rama
Already up to date.

C:\Users\Ainhoa\Desktop\MU\git\version 2>git commit -am "resolvemos los cambios"
On branch master
nothing to commit, working tree clean

C:\Users\Ainhoa\Desktop\MU\git\version 2>git lg
* a4213b2 (HEAD -> master) modifico readme.md
* 2428091 modifico lineaa 3 de readme.md
* 30ffd0f (nueva-rama) a<C3><B1>ado los ficheros
* df12109 A<C3><B1>adimos los ficheros originales

C:\Users\Ainhoa\Desktop\MU\git\version 2>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\Users\Ainhoa\Desktop\MU\git\version 2>https://github.com/ainhoaparedes/Ejercicio-git/settings
"https:" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\Users\Ainhoa\Desktop\MU\git\version 2>ainhoaparedes/Ejercicio-git
"ainhoaparedes" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\Users\Ainhoa\Desktop\MU\git\version 2>cd https://github.com/ainhoaparedes/Ejercicio-git/settings
El nombre de archivo, el nombre de directorio o la sintaxis de la etiqueta del volumen no son correctos.
C:\Users\Ainhoa\Desktop\MU\git\version 2>git push https://github.com/ainhoaparedes/Ejercicio-git/settings
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream https://github.com/ainhoaparedes/Ejercicio-git/settings master


C:\Users\Ainhoa\Desktop\MU\git\version 2>git push --set-upstream https://github.com/ainhoaparedes/Ejercicio-git/settings
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream https://github.com/ainhoaparedes/Ejercicio-git/settings master


C:\Users\Ainhoa\Desktop\MU\git\version 2>

C:\Users\Ainhoa\Desktop\MU\git\version 2>git push --set-upstream https://github.com/ainhoaparedes/Ejercicio-git/settings master
remote: Not Found
fatal: repository 'https://github.com/ainhoaparedes/Ejercicio-git/settings/' not found

C:\Users\Ainhoa\Desktop\MU\git\version 2>
