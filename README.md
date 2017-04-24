# shadowsocks with net-speeder
这是一个Shadowsocks Docker

## 启动方式

```
docker run -d --name ss-with-net-speeder -p 8989:8989 -p 22:22 jialezi/ss-with-net-speeder -s 0.0.0.0 -p 8989 -k jaz -m rc4-md5
```

## Arukas.io 启动

```
镜像 ：ss-with-net-speeder
启动命令(CMD) ：-s 0.0.0.0 -p 8989 -k jaz -m rc4-md5
```

## 支持SSH
用户名：root
密  码：password

## SSR镜像
https://github.com/jialezi/ssr-with-net-speeder

## 感谢
lowid/ss-with-net-speeder

https://github.com/malaohu/ss-with-net-speeder
