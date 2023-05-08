Max
Orel 
Sebastian
Juan
Alex



PS C:\Users\ZUL19> mkdir nuevo


    Directorio: C:\Users\ZUL19


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          5/8/2023  10:17 AM                nuevo


PS C:\Users\ZUL19> cd .\nuevo\
PS C:\Users\ZUL19\nuevo> git init
Initialized empty Git repository in C:/Users/ZUL19/nuevo/.git/
PS C:\Users\ZUL19\nuevo> code .
PS C:\Users\ZUL19\nuevo> code .
PS C:\Users\ZUL19\nuevo> git add .\README.md
PS C:\Users\ZUL19\nuevo> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

PS C:\Users\ZUL19\nuevo> git commit -m "Agregué el archivo README.md"
[master (root-commit) d4b99ce] Agregué el archivo README.md
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
PS C:\Users\ZUL19\nuevo> git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\ZUL19\nuevo> git add .\README.md
PS C:\Users\ZUL19\nuevo> git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

PS C:\Users\ZUL19\nuevo> git commit -m "Archivo modificado nombre de estudiantes"
[master 9a92dc1] Archivo modificado nombre de estudiantes
 1 file changed, 5 insertions(+)
PS C:\Users\ZUL19\nuevo> git status
On branch master
nothing to commit, working tree clean
PS C:\Users\ZUL19\nuevo>
