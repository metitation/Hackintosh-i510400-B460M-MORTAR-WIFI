## 基本信息

macOS version: 12.1 Monterey

引导方式：OC引导（0.7.6）

## EFI下载地址

## 升级过程记录

### 操作
- 更换 `AirportItlwm` 为 `Monterey` 版本
- 添加 `BlueToolFixup.kext`
- 禁用 `IntelBluetoothFirmware.kext`

### 遇到的坑
做完了上面的操作后，蓝牙死活没有用，几乎所有方案都试过了，最后在远景论坛找到了解决方案。
[查看](http://bbs.pcbeta.com/forum.php?mod=redirect&goto=findpost&ptid=1915971&pid=51985501)
> 关机后断电，断电后长按开机键5秒，接电源，开机。
