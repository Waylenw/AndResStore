## 存储
```
//查看分区
adb shell df -h
```

## 视图
```
 adb shell   dumpsys window
```

## 网络
```
adb shell  cat proc/net/arp
```
```
//表示已经打开的连接端口/网卡名称
adb shell ifconfig
```


## adb重启或关机手机命令
```
adb reboot
adb -s device1 reboot
//关机
adb shell reboot -p
```
## 查看某个端口进程
```
adb shell netstat -tulnp | grep :<PORT_NUMBER>
```
