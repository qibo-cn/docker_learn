# 列出本地 docker 镜像

```shell
docker images
```

# hello world

```shell
docker run  {image} /bin/echo "hello world"
```

# 交互式进入 docker

```shell
docker run -i -t {image} /bin/shell
```

# 显示宿主机中 docker 执行情况

```shell
docker ps
```

# 显示 docker 中输出

```shell
docker logs  {dockerID | docker name}
```

# 获取 docker image

```shell
 docker pull {imageName}
```

# 进入容器

```shell
1/ docker attach {dockerID}  -- 退出后，镜像停止运行
2/ docker exec -it {dockerID} /bin/bash --- 退出后，镜像不会停止。
```

# 导入、导出镜像

```shell
docker export {dockerID}> NAME.tar
```

# 删除 docker

```shell
docker rm -f {dockerID/dockerName}
```
