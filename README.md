# NginxWindows

#### 介绍
    Nginx高性能的HTTP和反向代理web服务器的Windows平台版本和相关配置
    版本：1.18.0

#### 软件架构
软件架构说明


#### 安装教程

1.  直接下载下来压缩包解压缩 或者 git clone
2.  修改conf目录里的nginx.conf

#### 使用说明

    1.  在终端进入到解压后的根目录
    2.  启动（nginx-windows)                start nginx
    3.  验证配置文件的准确性：                 nginx -t
    4.  启动：                              nginx -s start
    5.  配置文件修改重载：                    nginx -s reload
    6.  快速停止或关闭                       nginx -s stop
    7.  正常停止或关闭                         nginx -s quit
    8.  查看nginx版本号                      nignx -V
    9.  查看帮助信息                          nginx -h
    10.  打开日志文件                         nginx -s reopen
    11. 彻底杀掉Windows上的所有nginx进程   taskkill /IM nginx.exe /F


#### 参与贡献

1.  萨达木·沙地克（Sadam·Sadik）1903249375@qq.com

#### 报错解答
报错1：

        nginx: [emerg] CreateDirectory() "E:\myProjects\nginx-windows/temp/client_body_temp" failed (3: The system cannot find the path specified)
原因1：

        因为nginx被安装在了中文目录，或者路径中有中文汉字，所以nginx没法自己自动地在根目录创建temp文件夹

解决1：

        自己在nginx根目录手动创建一个temp目录

#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
