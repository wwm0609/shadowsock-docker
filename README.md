一：安装Docker (Ubuntu)



```

apt-get update

apt-get install docker.io

```





二：安装shadowsocks



```

docker run -it -p 7878:431 -e "password=docker" -d jarvin/shadowsocks-img

```



你只需要修改端口(7878),密码(docker)。



下载shadowsock客户端，使用：

账号：你的服务器地址。

端口：你修改后的端口号。

密码：你修改后的密码。
