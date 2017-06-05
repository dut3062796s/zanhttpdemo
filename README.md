# ZanTcpDemo
zan php tcp server demo

# 如何使用

1. 安装 [*zan扩展*](https://github.com/youzan/zan)，编译参数：(`sockets` 与 `openssl` 可选)
`./configure --enable-sockets --enable-openssl` 
2. 安装[composer](https://getcomposer.org/)
3. 在根目录下执行composer update
4. 配置php.ini
```ini
zan.RUN_MODE = test
zan.DEBUG = true
```
5. 启动http server
`php bin/httpd`
6. 访问`127.0.0.1:8030`