docker-shadowsocksr
===================


## 如何使用
- 安装 [Docker][1] 和 [Docker Compose][2]
- 下载 [docker-compose.yml][3]，修改相关参数
- 运行

        # 服务器端
        $ docker-compose up -d server

        # 客户端
        $ docker-compose up -d client

- 设置浏览器代理

[1]: https://docs.docker.com/install/
[2]: https://docs.docker.com/compose/install/
[3]: https://github.com/fpfeng/docker-shadowsocksr/raw/master/docker-compose.yml