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

�鿴Զ�̿���Ϣ��ʹ��git remote -v��

�����½��ķ�֧��������͵�Զ�̣��������˾��ǲ��ɼ��ģ�

�ӱ������ͷ�֧��ʹ��git push origin branch-name���������ʧ�ܣ�����git pullץȡԶ�̵����ύ��

�ڱ��ش�����Զ�̷�֧��Ӧ�ķ�֧��ʹ��git checkout -b branch-name origin/branch-name�����غ�Զ�̷�֧���������һ�£�

�������ط�֧��Զ�̷�֧�Ĺ�����ʹ��git branch --set-upstream branch-name origin/branch-name��

��Զ��ץȡ��֧��ʹ��git pull������г�ͻ��Ҫ�ȴ����ͻ��
