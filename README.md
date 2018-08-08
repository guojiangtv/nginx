# nginx配置
nginx，本地服务，所有本地项目的服务器配置都可以在这里配置,服务的项目有：

* 国内项目
* 海外项目
* naus项目
* 娃娃机项目

**由于nginx中配置文件采取相对目录，所以要求nginx和其他项目在同一目录下**  
请按照以下目录配置你本地项目文件夹:
```
guojiang/
---- /nginx/
---- /naus/
---- /overseas/
---- /source/
---- /xingguang/
```

各个项目的配置独立出配置文件

https证书文件夹 CA/  

https配置文件  

* 国内 conf/ssl/xingguang.conf
* 海外 conf/ssl/overseas.conf

本地http服务配置文件

* 国内 conf/project/xigguang.conf
* 海外 conf/project/overseas.conf
* naus conf/project/naus.conf
* grab conf/project/grab.conf

快速启动文件 start_nginx.bat   **双击即可启动nginx**  
快速退出文件 stop_nginx.bat    **双击即可退出nginx**


如有nginx服务不起作用，请首先查看logs文件夹中的error.log日志进行分析
