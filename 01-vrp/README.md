### console 端口

路由器端口号：2000
```
# telent 路由器
telnet 127.0.0.1 2000
```


### 串行连接
pc 的 RS232 端口和路由器的 Console 端口连接
```
# 基本参数如下

波特率：9600

数据位：8

奇偶位：无

停止位：1

流控：无

```

### vrp 操作

```
# 进入 system-view 模式
system-view

# 修改设备名称
sysname R1

# 保存设置
quit
save

# 保存到文件
save test.cfg

# 从文件启动
startup saved-configuration test.cfg

# 查看启动文件
display startup

# 清空配置文件
reset saved-configuration

# 重启系统
reboot

```
