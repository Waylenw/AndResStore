# Docker服务启动

```
/usr/bin/dockerd --data-root /new/path/docker
``` 
  
方法一：通过systemd编辑docker.service文件

步骤1： 创建一个新目录并授予docker用户访问权限

sudo mkdir /new/path/docker

sudo chown -R $USER:$USER /new/path/docker

步骤2：使用nano或vi编辑文件/etc/systemd/system/docker.service

sudo nano /etc/systemd/system/docker.service

步骤3：更改ExecStart选项，添加--data-root

ExecStart=/usr/bin/dockerd --data-root /new/path/docker -H fd://
