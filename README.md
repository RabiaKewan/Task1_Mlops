![Screenshot 2024-02-12 115530](https://github.com/RabiaKewan/Task1_Mlops/assets/119858275/a552c92d-2d48-4edf-84d3-2f62ea0e960b)
![Screenshot 2024-02-12 112959](https://github.com/RabiaKewan/Task1_Mlops/assets/119858275/5ba2e5b1-ba5e-4d9d-8253-ad3ef9418068)
![Screenshot 2024-02-12 112329](https://github.com/RabiaKewan/Task1_Mlops/assets/119858275/684cc5a2-d483-4323-b0ee-0125f8fca7a1)
![Screenshot 2024-02-12 113720](https://github.com/RabiaKewan/Task1_Mlops/assets/119858275/6306b0a5-df57-4774-a4e3-9878e74c4220)
![Screenshot 2024-02-12 111920](https://github.com/RabiaKewan/Task1_Mlops/assets/119858275/e8e515e1-3ec0-45a1-9718-af7d40b56380)

# Task1_Mlops

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~
$ git clone https://github.com/RabiaKewan/Task1_Mlops.git
Cloning into 'Task1_Mlops'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~
$ cd task1_Mlops

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (main)
$ git branch dev

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (main)
$ git branch test

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (main)
$ git branch master

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (main)
$ git branch rabia

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (main)
$ git branch kewan

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (main)
$ git checkout dev
Switched to branch 'dev'

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (dev)
$ git merge rabia
Already up to date.

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (dev)
$ git merge kewan
Already up to date.

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (dev)
$ git add .

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (dev)
$ git commit -m "initial commit"
On branch dev
nothing to commit, working tree clean

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (dev)
$ git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/RabiaKewan/Task1_Mlops/pull/new/dev
remote:
To https://github.com/RabiaKewan/Task1_Mlops.git
 * [new branch]      dev -> dev

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (dev)
$ git config --global user.email "rabiakewan402@gmail.com"

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (dev)
$  git config --global user.name "RabiaKewan"

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (dev)
$ git commit -m "initial commit"
On branch dev
nothing to commit, working tree clean

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (dev)
$ git push origin dev
Everything up-to-date

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (dev)
$ notepad readme.md
Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (dev)
$ mkdir my_project

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops (dev)
$ cd my_project

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops/my_project (dev)
$ ^[[200~python3 -m venv venv
bash: $'\E[200~python3': command not found

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops/my_project (dev)
$ python3 -m venv venv
Python was not found; run without arguments to install from the Microsoft Store, or disable this shortcut from Settings > Manage App Execution Aliases.

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops/my_project (dev)
$ touch main.py

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops/my_project (dev)
$ touch test.py

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops/my_project (dev)
$ touch requirments.txt

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops/my_project (dev)
$ git commit -m "initial commit"
On branch dev
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ../README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ./

no changes added to commit (use "git add" and/or "git commit -a")

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops/my_project (dev)
$ git add .

Rabia Kewan@LAPTOP-7F6HE65M MINGW64 ~/task1_Mlops/my_project (dev)
$ git commit -m "initial commit"
[dev c16f587] initial commit
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 my_project/main.py
 create mode 100644 my_project/requirments.txt
 create mode 100644 my_project/test.py


