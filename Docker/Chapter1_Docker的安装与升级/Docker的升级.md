# Docker的升级

```shell
# 更新包列表
apt-get update
# 卸载当前的docker，在之前的版本中，Docker引擎的包名有可能有多个
apt-get remove docker docker-engine docker-ce docker.io -y
# 安装新版本Docker
```

