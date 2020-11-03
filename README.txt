# lab3
Bootcamp nivelPRO - Laboratory 3

$ git remote add origin https://github.com/dicodiaz/lab3.git
$ git push -u origin master
$ git flow feature start add-file-1
$ vim README-1.txt
$ git add README-1.txt
$ git commit . -m "Add README-1.txt"
$ git push -u origin feature/add-file-1
$ git flow feature finish add-file-1
$ git push -u origin develop
$ git flow feature start add-file-2
$ vim README-2.txt
$ git add README-2.txt
$ git commit . -m "README-2.txt"
$ git flow release start v.0.1.0
$ git flow release finish v.0.1.0
$ git push -u origin
$ git flow feature finish add-file-2
$ git flow release start v.0.2.0
$ git flow release finish v.0.2.0
