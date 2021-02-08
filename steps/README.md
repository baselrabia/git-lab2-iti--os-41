# steps for - git-lab2-iti--os-41

Git practice repo : lab2 iti os 41
Created By : [Basel Rabia](https://github.com/baselrabia)
## 1
- echo "# git-lab2-iti--os-41" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M master
- git remote add origin https://- github.com/baselrabia/- git-lab2-iti--os-41.- git
- git push -u origin master


## 2


- git branch dev 
- git checkout dev
- git add .
- git commit -m "edit on steps from dev"
- git push origin dev


## 3
- git add .
- git commit -m "edit on steps from dev"
- git push origin dev
- git checkout master 
- git merge dev 

## 4

### DELETE Dev BRANCH 
===>  `git branch -d dev`
### DELETE Dev BRANCH remotely 
=> `git push origin --delete dev`
### UNDO THE LAST COMMIT 
===> `git reset --hard HEAD^`



## 5

### ADD TAG V1.4

- git tag -a v1.4 -m "version 1.4.0"
- git push --tag

### SHOW TAGS LOCALLY 

===> git tag -n