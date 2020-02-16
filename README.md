# 五子棋对战小游戏

# 介绍 
运行在linux上五子棋对战小游戏

# 运行环境
项目运行在linux系统上 

# 安装
在linux系统下可以直接将下载的项目解压，然后执行以下两个命令
如果是局域网联机对战的话，需要修改client.c，里的IP地址（第十行代码），改为server端的IP地址
```bash
make -f makefile_server
make -f makefile_client

```
# 使用方法
安装完毕后，执行一下命令就可以启动该项目
注意如果自己和自己对战的话，就用两个终端窗口分别启动server和client
```bash
./bin/server
./bin/client
```
启动该项目后将会展现如下的界面，然后就可以五子棋对战

# TODO 
* 将 server 抽离出来，让多个client连上来  
* 支持多人对战
