# learnCode
git学习笔记
工作原理


工作流程
首先在github新建自己的仓库 创建远程库 
https://github.com/bayern11james/learnCode.git

git branch -m | -M oldbranch newbranch #重命名分支

git remote add origin
基本步骤
    初始化git  gitinit
    添加更改  git add learn.js  提交到暂存区
    提交文件到本地仓库  git commit -m 'Bayern'
    发送到远程仓库  git push origin main

基本认知操作
    获取当前状态 git status
    比较更新前后的改变查看修改后的内容  git diff
    查询更改日志  git log
    版本回退 git reset --hard commit_id     
    查询每次git的操作记录 git reflog
    撤销修改 git checkout -- file
            git reset HEAD file
    删除文件 git rm file 

多人合作开发 
    从远程库克隆  git clone
    分支 
        合并分支    git merge  首先commit分支  切换分支到要合并的主干或分支 运行 git merge file
         删除分支    git branch -diff