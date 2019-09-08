# Docker的安装

1. 通过官方shell脚本一键安装

```shell
wget -qO- https://get.docker.com/ | sh
# 官方建议使用非root用户来使用docker,如果是用非root用户来使用docker，需要把该用户加入到Docker Unix组当中
sudo usermod -aG docker [username]
# 检查是否添加成功
cat /etc/group | grep docker
```

