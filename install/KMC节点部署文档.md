#### 说明文档

##### 1.端口占用情况说明

服务默认占用8888和8889两个端口号，释放8888和8889两个端口号以提供服务所需

##### 2.包解压安装

```shell
root$ wget http://img.xinyuanlive.com/koumei-linux-1.0.0-testnet.tar.gz
root$ tar xzvf koumei-linux-1.0.0-testnet.tar.gz
root$ cd koumei-linux-1.0.0-testnet
```

在koumei-linux-1.0.0-testnet目录下，修改config.json中参数publicIp。改成自己本机的公网IP,其他不做改动

```json
"publicIp": "xxx.xxx.xxx.xxx"  //添上公网IP地址
```

##### 3.启动服务

在koumei-linux-1.0.0-testnet目录下

```shell
root$ ./aschd start
```

说明：刚启动服务可能需要几分钟同步区块。



