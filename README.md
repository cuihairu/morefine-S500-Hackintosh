# minisforum S500 hackintosh

[![U820](screenshots/U820.jpg)](https://hackintosher.taobao.com)

## 电脑配置

|   规格    |                           详细信息                           |
| :-------: | :----------------------------------------------------------: |
| 电脑型号  |                       minisforum S500                        |
| 操作系统  |                 macOS `Monterey` / `Big Sur`                 |
|  处理器   |               英特尔 酷睿 i9-10880H 8核16线程                |
|   内存    |                      32 GB DDR4 2933MHz                      |
|  硬盘1/2  | WD SN750 **WDS100T3X0C** 1TB/<br />支持双NVMe或NVMe+SATA SSD或双SATA SSD |
|  硬盘/3   |                    可接SATA 2.5寸硬盘/SSD                    |
|   显卡    |                    Intel UHD Graphics 630                    |
|  显示器   |                              无                              |
|   声卡    |                   Realtek ALC662 `alcid=5`                   |
| 无线网卡  | m.2 NGFF插槽，默认出厂为 `Intel AX200` 已更换为[BCM94360Z3](https://blog.daliansky.net/uploads/WeChatandShop.png) |
| 有线网卡1 |   **Realtek RTL8168H/8111H PCI Express Gigabit Ethernet**    |
| 有线网卡2 |   **Realtek RTL8168H/8111H PCI Express Gigabit Ethernet**    |

## 更新日志

- 10-19-2021
  
  - Release `v1.0.0`
  - 默认支持 `Type-C` + `DP` 双显输出，未来会提供`DP` + `HDMI` 双显输出
  - 更新 `OpenCore` 为 `v0.7.5`
  - 请使用工具  [OCAT_Mac.dmg](https://github.com/ic005k/QtOpenCoreConfig/releases) 编辑 `config.plist` 
  
  
  

### 设置`BIOS`

- 安全菜单：

  - 安全启动 -> `关闭`  (*Disable Secure Boot*)

- 高级菜单：

  - CPU菜单：`CFG Lock` -> `关闭` (*Disabling CFG Lock*)【相关BIOS请进群获取】

- 设备：

  - 显示设备
    - 预指派内存大小：`64MB` (*DVMT* pre-allocated memory)

  - ATA设备菜单：
    - `配置SATA为` -> `AHCI`

- 其它参数默认即可



## 注意事项

登录 `Apple ID` 之前，请务必重新生成三码，否则有可能会导致无法登录 `App Store`，教程详见群公告里的链接



## 截屏

![DualDisplays](ScreenShots/DualDisplays.png)

![Graphics](ScreenShots/Graphics.png)

![Hackintool_Misc](ScreenShots/Hackintool_Misc.png)

![iTerm2](ScreenShots/iTerm2.png)

![Memory](ScreenShots/Memory.png)

![Memory2](ScreenShots/Memory2.png)

![Monterey_iMac](ScreenShots/Monterey_iMac.png)

![Monterey](ScreenShots/Monterey.png)

![NVMe](ScreenShots/NVMe.png)

![Sensei](ScreenShots/Sensei.png)

![WIFI](ScreenShots/WIFI.png)

![AirDrop](ScreenShots/Handoff.png)


## 其它信息

minisforum 黑苹果交流群：[869792897](https://qm.qq.com/cgi-bin/qm/qr?k=TdIS59sEdBCjbz8NbdrQ2IyPG6bMza3_&jump_from=webapi)

minisforum S500购买链接：[黑果小兵的部落阁](https://hackintosher.taobao.com/) 

## 感谢名单：

- [Apple](https://apple.com/) for macOS;
- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the lovely hackintosh work.
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/icelake.html) For great and detailed guides.

- [jozews321](https://github.com/jozews321) For the injection information in the U820 device properties
