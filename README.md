# git-command
git常用命令

- **删除远程分支**

git push origin --delete 分支名

- **将本地的仓库和远程的仓库进行关联**

git remote add origin git@github.com:YotrolZ/helloTest.git

- **删除远程tag**
git push origin :refs/tags/tag标本号

- **删除本地tag**
git tag -d tag版本号

- **删除远程分支**
git branch -r -d origin/branch-name

git push origin :branch-name