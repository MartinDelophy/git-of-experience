# git-of-experience
my self git experience

git revert 可以创建一个新的节点 通过 add commit 出发新的节点
git reset 可以让当前指针指向一个一个节点  
如果用--hard命令就完全改变工作区了，但是可以通过 git reflog来还原回来。


git merge 可以进行分支合并，会完全改变某一个分支的文件
git rebase 可以改变分支的基 指令较为复杂，需要时间去理解

git stash 可以储藏自己的工作区改变的部分，通过git stash pop 来进行还原  ==> 仅限用于尚未commit操作的情况  commit 部分需要重新提交
git checkout .  可以指定某一个文件 文件夹 一样的效果  commit 部分还能应用之前的
git checkout -b 创建新的分支

git add. 加入文件
git commit 用于提交

git fsck --lost-found  可以观察悬空指针中状态。

############################################################ 

![git 指针详解]https://www.cnblogs.com/idorax/p/6475941.html
###########################################################



