
假设已经在centOS中安装好docker

- 拉取镜像
  在docker官方仓库搜索已经存在的镜像文件(https://hub.docker.com)，选择星级最高的镜像，如redis。找到拉取当前镜像需要执行的命令，如docker pull redis，在centOS中启动docker环境后执行docker pull redis 拉取最新镜像到本地。
- 启动redis
  docker run --name some-redis -d redis
  --name:为容器指定一个名称
  -d:后台运行容器，并返回容器ID