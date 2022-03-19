## base 镜像重新制作，解决的问题
- 原有镜像没有yum 仓库createrepo，在升级操作的时候我们要添加新的rpm包 
- 私有镜像containerd 缺少用户密码的配置，通过修改ansible 源码配置来搞定
- 更新升级的时候新的rpm 包再客户端需要重新做 yum makecache


## 新增k8s 基础 image list 的下载和导入脚本

