git 提交代码命令
1.git add <filename>
  git add *
2.这是 git 基本工作流程的第一步；使用如下命令以实际提交改动：
  git commit -m "代码提交信息"
3.你的改动现在已经在本地仓库的 HEAD 中了。执行如下命令以将这些改动提交到远端仓库：
  git push origin master
  可以把 master 换成你想要推送的任何分支。

如果你还没有克隆现有仓库，并欲将你的仓库连接到某个远程服务器，你可以使用如下命令添加：
git remote add origin git@github.com:qianjunjian/Angular2_test.git
如此你就能够将你的改动推送到所添加的服务器上去了。

分支
1.创建一个叫做"feature_x"的分支，并切换过去：
  git checkout -b feature_x
2.切换回主分支：
  git checkout master
3.再把新建的分支删掉：
  git branch -d feature_x
4.除非你将分支推送到远端仓库，不然该分支就是 不为他人所见的：
  git push origin <branch>

更新与合并
1.要更新你的本地仓库至最新改动，执行：
  git pull
2.要合并其他分支到你的当前分支（例如 master），执行：
  git merge <branch>