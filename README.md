# Pixiv-Nginx

## 使用方法：

原作者教程[点我]((https://2heng.xin/2017/09/19/pixiv/))。

1、下载

<img src="https://view.moezx.cc/images/2018/09/17/git.png" width="360" alt="下载方法" />

2、根据E:\Pixiv-Nginx-main\自签证书傻瓜式批处理包 文件夹内的教程创建自己的签名ca；并导入到受信任的根证书机构（[Google Chrome安装证书的方法]((https://jingyan.baidu.com/article/c843ea0bc4142a77921e4a79.html))）

3、将E:\Pixiv-Nginx-main\hosts 的内容复制到你的hosts文件内，推荐使用[SwitchHosts]((https://github.com/oldj/SwitchHosts))来管理你的hosts。

4、使用 可视化工具（这个操作简单）.exe 运行nginx.exe 或将nginx.exe 放进开机启动。

5、不要使用其他系统代理，直接连接你所需的网址即可，推荐使用SwitchyOmega插件。

## 对于失效网站的处理：

>（我将不定时更新以确保能稳定使用）

1、请阅读8.如果网站ip失效了处理 zgh.txt

# LICENSE

<a href="http://www.wtfpl.net/"><img src="https://ngx.moezx.cc/share/svg/brands/WTFPL_badge.svg" width="80" alt="WTFPL" /></a>

This is a fork of [nginx/nginx](https://github.com/nginx/nginx), so you should always follow its [2-clause BSD-like license](http://nginx.org/LICENSE).

The visualized management tool is part of [wnmp/wnmp](https://github.com/wnmp/wnmp), which is under [GPL-3.0](https://github.com/wnmp/wnmp/blob/master/LICENSE).
