Git is a distributed version control system.
Git is a free software distributed under the GPL...

git checkout -b dev
Creating a new branch is quick.

$ git checkout master
$ git merge dev

Creating a new branch is quick & simple.
$ git checkout -b feature1
$ git checkout master
$ git merge feature1
$ git branch -d feature1
$ git checkout -b dev


$ git checkout -b issue-101
$ git checkout master
$ git merge issue-101
$ git branch -d issue-101
$ git stash
$ git remote -v
$ git push origin master

http://stackoverflow.com/questions/5827944/git-error-on-commit-after-merge-fatal-cannot-do-a-partial-commit-during-a-mer

modify @PC
modify @NoteBook

查看远程库信息，使用git remote -v；

本地新建的分支如果不推送到远程，对其他人就是不可见的；

从本地推送分支，使用git push origin branch-name，如果推送失败，先用git pull抓取远程的新提交；

在本地创建和远程分支对应的分支，使用git checkout -b branch-name origin/branch-name，本地和远程分支的名称最好一致；

建立本地分支和远程分支的关联，使用git branch --set-upstream branch-name origin/branch-name；

从远程抓取分支，使用git pull，如果有冲突，要先处理冲突。
