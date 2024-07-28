TG[@GoEdge233](https://t.me/goedge233)

# 独家赞助 Goedge
GoEdge CDN
制作自己专属的CDN
利用开源的GoEdge可以零成本制作自己专属的CDN系统，支持集群式管理和API。

https://goedge.cloud

# 感谢Lecdn官方的引流，观察到自开心版PATCH无人使用，故直接开源license服务端源码

## 功能

本仓库可帮助你开心的试用Lecdn

## 使用方法一（直接使用）

安装完Lecdn后从仓库中下载修改过的lecdn-master.patch放到Lecdn目录下

进入Lecdn目录执行指令

```bash
chmod +x lecdn-master.patch
```

完成后执行下面命令修改Hosts

```bash
echo "13.125.122.206 key.lecdn.local">>/etc/hosts
```

## 使用方法二（自行编译）

下载lecdn.zip压缩包，解压放到/license_server目录下。解压后编译运行（需要GOLANG环境）

```bash
go build
./LeCDN
```

完成后执行下面命令修改Hosts（$IP改为自己的授权站IP）

```bash
echo "$IP key.lecdn.local">>/etc/hosts
```

## 鸣谢

Lecdn

## 广告位招租 接定制破解 TG[@mihoooyoo](https://t.me/mihoooyoo)

## 许可证

本仓库的代码和文档使用 [Apache 2.0 协议](LICENSE) 授权。