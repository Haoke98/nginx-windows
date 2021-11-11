<div align="center">
<img width="200" height="160" src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2F5b0988e595225.cdn.sohucs.com%2Fimages%2F20171106%2F6ee4bf83716845c1bf72455b42f5b88b.jpeg&refer=http%3A%2F%2F5b0988e595225.cdn.sohucs.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1639213528&t=2f0f5b0bf8ec843a03633aea29cdf5f6"/>
<img width="200" height="160" src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fpic.51yuansu.com%2Fpic3%2Fcover%2F03%2F65%2F24%2F5bdff5304ed51_610.jpg&refer=http%3A%2F%2Fpic.51yuansu.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1639213705&t=b4fce45be9cd7a1fc9a58079fadc1a4b"/>

# Nginx-Windows
简体中文 |  [English](./README.en.md)
<p>Nginx高性能的HTTP和反向代理web服务器的Windows平台版本和相关配置</p>
<p>版本：1.18.0</p>
</div>

[comment]: <> ([![Website]&#40;<https://img.shields.io/badge/ good luck - vue admin beautiful -blue?style=flat-square>&#41;]&#40;https://gitee.com/sadam98/nginx-windows&#41;)
[![stars](https://img.shields.io/github/stars/chuzhixin/vue-admin-beautiful?style=flat-square&logo=GitHub)](https://gitee.com/sadam98/nginx-windows)
[![star](https://gitee.com/chu1204505056/vue-admin-beautiful/badge/star.svg?theme=gray)](https://gitee.com/sadam98/nginx-windows)
[![license](https://img.shields.io/github/license/chuzhixin/vue-admin-beautiful?style=flat-square)](https://gitee.com/sadam98/nginx-windows/blob/master/LICENSE)


#### 软件架构

    软件架构说明


#### 安装教程

    1. 直接下载下来压缩包解压缩 或者 git clone
    2. 修改conf目录里的nginx.conf

#### 命令大全
###### 1.启动（nginx-windows)
```bash
start nginx
```
###### 2.验证配置文件的准确性：
```bash
nginx -t
```
###### 3.启动：
```bash
nginx -s start
```
###### 2.验证配置文件的准确性：
```bash
nginx -t
```
###### 3.配置文件修改重载：
```bash
nginx -s reload
```
###### 4.快速停止或关闭：
```bash
nginx -s stop
```
###### 5.正常停止或关闭
```bash
nginx -s quit
```
###### 6.查看nginx版本号
```bash
nignx -V
```
###### 7.查看帮助信息
```bash
nginx -h
```
###### 8.打开日志文件
```bash
nginx -s reopen
```
###### 9.彻底杀掉Windows上的所有nginx进程
```bash
taskkill /IM nginx.exe /F
```
###### 10.快速生效host文件的修改
```bash
ipconfig /flushdns
```



#### 参与贡献



#### 报错解答
报错1：

        nginx: [emerg] CreateDirectory() "E:\myProjects\nginx-windows/temp/client_body_temp" failed (3: The system cannot find the path specified)
原因1：

        因为nginx被安装在了中文目录，或者路径中有中文汉字，所以nginx没法自己自动地在根目录创建temp文件夹

解决1：

        自己在nginx根目录手动创建一个temp目录
## 框架杰出贡献者
<div align="center">
    <a href="https://gitee.com/sadam98" target="_blank">
    <img width="50px" style="border-radius:999px" src="https://portrait.gitee.com/uploads/avatars/user/1882/5648408_sadam98_1580052770.png!avatar200"/>
    </a>
    <div>萨达木·沙地克</div>
    <div>Sadam·Sadik</div>
    <div>1903249375@qq.com</div>
</div>

## 联系我们

- 请我们喝杯咖啡，支付后联系 QQ 1903249375 邀请您进入讨论群（由于用户数较多，如果您打赏后未通过好友请求，请在支付宝支付页面选择联系商家），不管您请还是不请，您都可以享受到开源的代码，感谢您的支持和信任，群内提供
基础版本、开发工具自动配置教程及项目开发文档。

<table>
<tr>
<td>
<img width="200px" src="http://59.110.225.84/static/sdm/qr_qq.png">
</td>
<td>
<img width="200px" src="http://59.110.225.84/static/sdm/qr_alipay.png">
</td>
<td>
<img width="200px" src="http://59.110.225.84/static/sdm/qr_wechat.png">
</td>
</tr>
</table>

#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
