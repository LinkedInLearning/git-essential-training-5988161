This is content for a file I just added to the local repo 
Para llevarlo a stage uso git add Example.md

Eso le dice a Git que i want to stage this file in the next commit

Si uso git add . eso would staged all changes in the current directory

git status te enseña como how the repository is doing

Microsoft Windows [Version 10.0.26100.4946]
(c) Microsoft Corporation. All rights reserved.

C:\repos\git-essential\git-essential-training-5988161>Git add Example.md

C:\repos\git-essential\git-essential-training-5988161>git add .

C:\repos\git-essential\git-essential-training-5988161>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Example.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Example.md


C:\repos\git-essential\git-essential-training-5988161>

para hacer commit con un mensaje que explique el porqué del commit:
git commit -m "adds Example.md to demostrate the git process"

(Tuve que agregar mis credenciales globalmente y luego volvi a intentar el commit

C:\repos\git-essential\git-essential-training-5988161>git config --global user.name "Jo-Nath"          
 
C:\repos\git-essential\git-essential-training-5988161>git config --global user.email "jonguzca@gmail.com"            

C:\repos\git-essential\git-essential-training-5988161>git config --show-origin --get user.name
file:C:/Users/jonat/.gitconfig  Jo-Nath

C:\repos\git-essential\git-essential-training-5988161>git config --show-origin --get user.email
file:C:/Users/jonat/.gitconfig  jonguzca@gmail.com)

*Ahora lo vamos a agregar del repositorio local al remoto:

*Cuando usé git push me mando al browser a hacer log in y luego hizo el push al remote

*Con el comando Pull podemos traer cosas desde el remoto (creare una rchivo en el repositorio remoto a traves de la UI web de git Example02 y Example02.md)

Ahora voy a probar creando un reposiorio (inicializando) localmente y sincronizandolo con uno en git


This is an extra line to test editing a file a viw changes. To check what has being change you use git diff

git diff --cached is for staging area changes


Here is an extra line to work with undo changes


Con git log vemos el historial de commits

usa el id del commit in git log para usando git show + id veas todo los cambios en eso

con git log --oneline da una linea de id y titulos de commits mas corta y legible

hay otras formas de usar git log tambien


con git checkout puedo ir/ver a un commit anterior 

git checkout + the name of the branch me permite volver al commit actual


