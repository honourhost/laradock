# Laradock精简优化版

 
> 基于[Laradock](https://laradock-docs.linganmin.cn/) 精简，只保留了PHP+MYSQL+MONGODB+REDIS+NGINX+APACHE ，针对PHP添加了redis、mongodb 、xhprof和xdebug扩展。更换了支持新版mongodb的mongo网页管理端。添加图形处理的GRAPHVIZ软件

<a name="Intro"></a>
## 介绍

Laradock预装PHP开发者常用软件集合，不需要单独安装和维护任何软件在你本地机器上。

**使用概览：**

1. 安装 docker，[下载](https://www.docker.com/products/docker-desktop)   ； 安装docker-compose ,[下载](https://github.com/docker/compose/releases)

2. 下载 Laradock ：

    ```bash
    git clone https://github.com/laradock/laradock.git  &&  cd  laradock   &&  docker-compose up -d
    ```
    
3. 设置NGINX站点配置

4. 在docker内运行的项目配置数据库地址：， mysql地址为"mysql" ，redis地址为"redis"  ，mongodb地址为"mongo"。

5. 打开浏览器，访问 localhost


## 许可证

[MIT License](https://github.com/laradock/laradock/blob/master/LICENSE) (MIT)
