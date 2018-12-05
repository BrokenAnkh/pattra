# redis
1. 介绍
    > - 开源非关系型数据库，
    > - 数据存储在内存中

1. 安装
    ``` shell
    cd redis/unzip/root/path
    make clean
    make install DESTDIR=your/install/path
    ```
1. 配置
    ``` properties
    daemonize no
    pidfile /var/run/redis.pid
    port 6379
    bind 127.0.0.1 # 绑定的主机地址
    # effect client
    timeout 300 # 客户端闲置超时关闭
    loglevel verbose
    logfile stdout
    database 16
    save <seconds> <changes>

    ```
1. 数据结构
    # Hash
    # List
    # 

3. 命令
    * config
    * 
