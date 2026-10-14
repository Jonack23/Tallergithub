# Tallergithub
Prueba de taller de como usar github.
prueba de que se ha hecho un cambio.

Historial de git bash


Jaime@Jonacks-Laptop MINGW64 ~
$ cd desktop/

Jaime@Jonacks-Laptop MINGW64 ~/desktop (feature/presentationn)
$ git clone https://github.com/Jonack23/Tallergithub.git\
>
Cloning into 'Tallergithub'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

Jaime@Jonacks-Laptop MINGW64 ~/desktop (feature/presentationn)
$ cd Tallergithub/

Jaime@Jonacks-Laptop MINGW64 ~/desktop/Tallergithub (main)
$ git statues
git: 'statues' is not a git command. See 'git --help'.

The most similar command is
        status

Jaime@Jonacks-Laptop MINGW64 ~/desktop/Tallergithub (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

Jaime@Jonacks-Laptop MINGW64 ~/desktop/Tallergithub (main)
$ git add Tallergithub
fatal: pathspec 'Tallergithub' did not match any files

Jaime@Jonacks-Laptop MINGW64 ~/desktop/Tallergithub (main)
$ git add .

Jaime@Jonacks-Laptop MINGW64 ~/desktop/Tallergithub (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


Jaime@Jonacks-Laptop MINGW64 ~/desktop/Tallergithub (main)
$ git commit -m "Agregue un comentario en el readme"
[main 355190b] Agregue un comentario en el readme
 1 file changed, 1 insertion(+)

Jaime@Jonacks-Laptop MINGW64 ~/desktop/Tallergithub (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 325 bytes | 162.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Jonack23/Tallergithub.git
   1271f51..355190b  main -> main
