
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
