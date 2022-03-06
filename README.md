```
conda create --prefix ./env python=3.7 y
```

To know where the remote branch location is,
```
$ git remote -v
origin  https://github.com/kiran1384/aiops_test.git (fetch)
origin  https://github.com/kiran1384/aiops_test.git (push) 
```
To remove file from staging
```
$ git rm --cached main.py
rm 'main.py'
```
To know the branch name
```
git branch
* main
```

To rename a branch
```
git brnch -M main
```