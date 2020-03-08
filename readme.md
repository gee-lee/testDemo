## 当前项目说明书

1、进入要管理的文件夹

2、执行初始化命令
git init

3、查看文件状态
git status

4、管理指定文件
git add 文件名
git add .

5、个人信息配置
git config --global user.email "邮箱"
git config --global user.name "名字"

6、生成版本
git commit -m "描述信息"

7、查看历史版本记录
git log 

8、回滚至之前版本、
git log
git reset --hard 版本号

9、回滚至之后版本
git reflog
git reset --hard 版本号

--------------------------------------------------

10、查看分支
git branch

11、创建分支
git branch 分支名称

12、切换分支
git checkout 分支名称

13、分支合并
git merge 要合并的分支名称
注意：切换分支后再合并

14、删除分支
git branch -d 分支名称

15、开发的工作流
开发流程至少两个分支，master分支只放置稳定上线的版本，dev分支专门开发



