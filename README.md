## 安装Docker (Ubuntu)

```bash
$ sudo apt update
$ sudo apt install docker.io
```


## 安装和运行shadowsocks server
你只需要修改端口(7878),密码(docker)。
```
$ sudo docker run -it -p 7878:431 -e "password=docker" -d kelvv/shadowsocks-img
```

## 下载接使用shadowsock客户端：
1. MacOs  : https://github.com/shadowsocks/ShadowsocksX-NG   
2. Ubuntu : https://github.com/shadowsocks/shadowsocks-qt5    
3. Android: https://github.com/shadowsocks/shadowsocks-android   

账号：你的服务器地址   
端口：你修改后的端口号   
密码：你修改后的密码   
加密方式：aes-256-cfb
