# My learn git
## 基础命令

git init

touch index.html

git status

git add index.html

git add *.html

git add .

git commit

修改文件

git status

git add .

git commit -m 'Changes in file'

git  branch login

git checkout login

添加login.html
git add .

git commit -m 'changes in login'

git checkout master

git merge login

---

### ignore

touch .gitignore

touch log.txt

git add .

git commit -m 'added ignore'

去ignore文件里修改

## remote

```
git remote add origin https
```

git remote

git push -u origin master

touch README.md

修改README

git add .

git commit -m ''

修改GitHub上文件

git pull

也可以用fetch 再merge

git fetch origin master

git merge origin/master