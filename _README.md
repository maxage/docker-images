# docker images
本仓库用于管理常用的Docker镜像，并将它们上传到GitHub Container Registry (GHCR)。

## 使用说明
### 1. 提高拉取速度
把 `151.101.184.133 pkg-containers.githubusercontent.com` 加入 `hosts` 文件，可能拉取速度会变快。

### 2. 添加新镜像
如果你想添加其他镜像，可以通过以下方式：
- 提交Issue说明你需要的镜像
- 或者Fork本仓库，启用Actions后：
  1. 在`hub`目录下新建文件
  2. 文件内容为镜像名称及tag（参考格式见下方）
[hub/nginx](https://github.com/maxage/docker-images/blob/main/hub/nginx)。
### 3. 镜像列表
当前管理的镜像列表：

