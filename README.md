##  centos一键安装shadowsocks脚本

执行以下命令一键安装：

```
chmod +x install-shadowsocks.sh
./install-shadowsocks.sh
```

也可以直接执行以下命令从 `GitHub` 下载安装脚本并执行：

```
bash <(curl -s http://morning.work/examples/2015-12/install-shadowsocks.sh)
```
安装完成后会自动打印出 `Shadowsocks` 的连接配置信息。比如：

```
Congratulations! Shadowsocks has been installed on your system.
You shadowsocks connection info:
--------------------------------
server:      10.0.2.15
server_port: 8388
password:    RaskAAcW0IQrVcA7n0QLCEphhng7K4Yc
method:      aes-256-cfb
--------------------------------
```


## 参考文档

在 CentOS 7 下安装配置 shadowsocks
https://morning.work/page/2015-12/install-shadowsocks-on-centos-7.html