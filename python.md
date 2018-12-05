# python
## 配置
* 安装python
* 配置环境变量
    ``` path
    PYTHON_HOME=python_package
    PATH=%PATH%;%PYTHON_HOME%;%PYTHON_HOME%\Scripts
    ```
* 配置pip镜像源
    > 国内镜像源列表:
    [清华](https://pypi.tuna.tsinghua.edu.cn/simple)
    [阿里云](http://mirrors.aliyun.com/pypi/simple/)
    [中国科技大学](https://pypi.mirrors.ustc.edu.cn/simple/)
    [华中理工大学](http://pypi.hustunique.com/)
    [山东理工大学](http://pypi.sdutlinux.org/)
    [豆瓣](http://pypi.douban.com/simple/)
* 配置virtualenv
    ``` powershell
    pip install virtualenv # 安装env环境
    cd workdir
    virtualenv -p c:\Python36\python.exe HigEnv # 初始化env环境,higenv为env名称
    .\env\Scripts\activate # 启动env环境
    .\env\Scripts\deactivate # 关闭env环境
    ```
## 文档
> [python 指南](https://docs.python.org/3/tutorial/index.html)  
> [python 语法手册](https://docs.python.org/3/reference/index.html)  
> [python 模块手册](https://docs.python.org/3/library/index.html)  
> [python 3.52 中译](https://yiyibooks.cn/xx/python_352/index.html)
