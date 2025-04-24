# 🐳 Docker镜像管理仓库

本仓库用于管理常用的Docker镜像，并将它们上传到GitHub Container Registry (GHCR)。✨

## 📖 使用说明

### 🚀 1. 提高拉取速度
在`hosts`文件中添加以下内容可能提高拉取速度：
151.101.184.133 pkg-containers.githubusercontent.com
国内拉取示例：docker pull ghcr.nju.edu.cn/

### ➕ 2. 添加新镜像
如果你想添加其他镜像，可以通过以下方式：
- 📝 提交Issue说明你需要的镜像
- 🍴 或者Fork本仓库，启用Actions后：
  1. 在`hub`目录下新建文件
  2. 文件内容为镜像名称及tag（参考格式见下方）

👉 示例文件格式参考：[hub/nginx](https://github.com/maxage/docker-images/blob/main/hub/nginx)


### 🤝3. 贡献指南
欢迎提交Pull Request来添加更多常用镜像！🎉

### ⚖️4. 许可证
[MIT](LICENSE)

### 📋 5. 可用镜像列表
当前管理的镜像列表：
🔄 👇👇👇👇👇👇
