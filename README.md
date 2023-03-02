Andrea18
Alejandro96
Alexis28
Aldemar
Andres P
Anibal Alvarado
Arturo
Carlos Gonzalez
Carlos105
Diego Cuellar
Carolina Cabrera
Cesar9p
Cristian Garcia
DuarteDA


Proceso:
PS C:\Users\fabte\Documents\ejercicios> ls       


    Directorio: C:\Users\fabte\Documents\ejercicios


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----       1/03/2023  8:52 p. m.                ejercicio1


PS C:\Users\fabte\Documents\ejercicios> pwd

Path
----
C:\Users\fabte\Documents\ejercicios


PS C:\Users\fabte\Documents\ejercicios> ls


    Directorio: C:\Users\fabte\Documents\ejercicios


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----       1/03/2023  8:52 p. m.                ejercicio1


PS C:\Users\fabte\Documents\ejercicios> mkdir ejercicio2


    Directorio: C:\Users\fabte\Documents\ejercicios


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----       2/03/2023  5:32 p. m.                ejercicio2


PS C:\Users\fabte\Documents\ejercicios> cd ejercicio2   
PS C:\Users\fabte\Documents\ejercicios\ejercicio2> git init
Initialized empty Git repository in C:/Users/fabte/Documents/ejercicios/ejercicio2/.git/
PS C:\Users\fabte\Documents\ejercicios\ejercicio2> git ad README.md
git: 'ad' is not a git command. See 'git --help'.

The most similar commands are
        add
        am
PS C:\Users\fabte\Documents\ejercicios\ejercicio2> git add README.md
fatal: pathspec 'README.md' did not match any files
PS C:\Users\fabte\Documents\ejercicios\ejercicio2> in README.md
The In command may only be used inside a Describe block.
En C:\Program Files\WindowsPowerShell\Modules\Pester\3.4.0\Functions\Describe.ps1: 125 Carácter: 9
+         throw "The $CommandName command may only be used inside a Des ...
+         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : OperationStopped: (The In command ...Describe block.:String) [], RuntimeException
    + FullyQualifiedErrorId : The In command may only be used inside a Describe block.
 
PS C:\Users\fabte\Documents\ejercicios\ejercicio2> git status        
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
PS C:\Users\fabte\Documents\ejercicios\ejercicio2> git add README.md
fatal: pathspec 'README.md' did not match any files
PS C:\Users\fabte\Documents\ejercicios\ejercicio2> git add README.md
PS C:\Users\fabte\Documents\ejercicios\ejercicio2> git status       
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

PS C:\Users\fabte\Documents\ejercicios\ejercicio2> git remote add origin https://github.com/fabiankintero/aspirantes-mir-ejercicio-2.git
PS C:\Users\fabte\Documents\ejercicios\ejercicio2> git commit -m "agregué el archivo README.md"                                     [master (root-commit) cc7ee86] agregué el archivo README.md
 1 file changed, 14 insertions(+)
 create mode 100644 README.md
PS C:\Users\fabte\Documents\ejercicios\ejercicio2> git branch -M main                                                               PS C:\Users\fabte\Documents\ejercicios\ejercicio2> git push -u origin main                                                          Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 355 bytes | 177.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/fabiankintero/aspirantes-mir-ejercicio-2.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\fabte\Documents\ejercicios\ejercicio2>