# Git
## 配置
1. 安装
1. 配置用户
    ``` shell

    ```
1. 配置ssh
    ``` shell
    cd ~
    mkdir .ssh
    cd .ssh
    vim config
    ssh-keygen -t rsa -C 'your content'
    ```
    config示例：
    ``` config
    # gitlab
    Host github.com
    Port 22
    HostName github.com
    PreferredAuthentications publickey
    IdentityFile C:/Users/xiaohaozi/.ssh/id_github_rsa
    User posuo
    ```
* file/dir
    ```
    git add [filename/dirname]
    git rm [filename/dirname]
    git commit [filename/dirname] -m ["comment"]
    git status
    ```

* checkout
    ```
    git checkout [filename/dirname]
    ```

* branch
    ```
    git checkout -b [branchname]
    git branch -v 
    git branch [branchname]
    git branch -d [branchname]
    git diff [branchname]
    git merge [branchname]
    git fetch origin master:[branchname]
    git pull origin master:[branchname]
    ```

* remote
    ```
    git remote -v
    ```

* log
    ```
    git log
    git reflog
    ```

* version switch
    ```
    git reset --hard [versionid]
    ```

* gui
    ```
    gitk
    ```

## 参考链接
> [Git 官网](https://git-scm.com/)  
> [Git 教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
