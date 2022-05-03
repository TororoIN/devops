# devops

2

MAKING A NEW FILE IN A NEW FOLDER
```
$git --version
$mkdir devops
$cd devops
$touch test.txt
$dir test.txt
#(Add text in file, “This is test file”)
$cat test.txt
```
INITIALIZE A LOCAL GIT REPOSITORY
```
git init
```

ADD NEWLY CREATED FILE ON GIT REPOSITORY
```
git status
git add test.txt
Git status
```

COMMIT CHANGES
```
git commit -m “Write something”
git add . 
git status
git push https: ……. master
```

  3
CREATE A NEW BRANCH
```
git branch suer-branch
```

DISPLAY ALL BRANCHES
```
git branch -a
```

SWITCHING TO NEW BRANCH FROM MASTER
```
git checkout user-branch
```

SWITCHING TO A SUB BRANCH WITHIN A BRANCH
```
Git checkout -b sub-branch user-branch
git status 
```

CREATING A NEW FILE AND ADDING IT TO BRANCH
```
git checkout user-branch
touch branchingtest.txt
```
CHECKING ALL FILES IN FOLDER
```
ls
```

CHECKING ALL BRANCHES 
```
git branch -a
```

PUSHING BRANCH TO REMOTE REPO
```
git add .
git commit -m “New file in branch”
git push https…… user-branch
```
