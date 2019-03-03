# docker-java-node
docker镜像文件，在操作系统 alpine 基础上使用 openJDK 的 jre8 和 node 的镜像。

[docker-hub](https://hub.docker.com/r/kissaoe/java-node-alpine)

# 使用方式

## 下载镜像
`docker pull kissaoe/java-node-alpine`

## 启动镜像
外部6000端口映射为80端口
`docker run -it -d -p 6000:80 kissaoe/java-node-alpine`

# 版本更新
## 1.0.0
暴露的端口有: 3000 6000 8080

具体修改如下:
1. 操作系统 alpine
2. 安装基础组件 jre8 和 nodeJS

## 1.1.0
暴露的端口有: 80

具体修改如下:
1. 新增 nginx
