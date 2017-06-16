##git nodes
+ 创建版本库
    * 初始化一个Git仓库
        - git init
            + ls -ah查看文件包括隐藏文件
    * 把文件添加到版本库
        - git add readme.txt    //把readme.txt的文件添加到版本库
        - git add .     //点为多个文件
    * 文件提交到仓库
        - git commit
            + git commit -m "xxx"   //-m后面输入的是本次提交的说明
    * 查看仓库当前的状态
        - git status
        - git diff //查看文件修改内容
+ 时光机穿梭
    * 查看提交历史
        - git log
            + append GPL  //最近一次
            + add distributed //上一次
            + wrote a readme file //最早的一次
            + git log --pretty=oneline  提交历史的时间线
        - git reflog
            + 查看命令历史
    * 回退到上一个版本
        - git reset
        - git reset --hard HEAD^   
            + 一个版本就是HEAD^，上上一个版本就是HEAD^^,100个版本写HEAD~100