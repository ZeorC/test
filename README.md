
## 常用命令

- `git init`
- `git add`
- `git commit`
- `git rm`
- `git log`
- `git diff`

## 概念


- git init 默认创建master分支，一般主分支都叫master
- unstack命令 `git rm --cached test.txt`

## 用户名和邮件

- /etc/gitconfig
 - git config --system
- ~/.gitconfig
 - git config --global
- .git/config
 - git config --local

优先级从低到高

## 删除

git rm 等价于 rm + git add

## 分支
git branch 显示分支

git checkout xx 切换分支

git checkout - 

git branch -d xx 删除分支
git branch -D xx 删除分支(强制)
