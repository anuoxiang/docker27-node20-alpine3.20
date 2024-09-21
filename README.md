# 基于 node lts-alpine3.20 构建 docker 的镜像

- node [官方镜像地址](https://github.com/nodejs/docker-node/blob/410410f6955bf8d052ef3ec7988cd41a54eab879/20/alpine3.20/Dockerfile)
  - Node 镜像选择 20.17.0 lts 版本
- docker [官方镜像地址](https://github.com/docker-library/docker/blob/21b87062452c5525f054e46fb9dc998d0601bfb3/27/cli/Dockerfile)
  - Docker 镜像选择 27.3.0 cli 版本

完成构建后，会将其推送到阿里云的私有仓库中
