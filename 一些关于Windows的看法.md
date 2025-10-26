# 一些关于Windows和Office的看法

## 一、Windows

### 1、下载Windows

- 下载Windows可以去微软官网下载，不推荐去其他地方下载，因为可能携带一些其他的东西。如果微软官网很难打开，可以去`Next I tell you`下载，这个里面的系统还行，没目前听说有什么病毒什么的，因为也是微软官网收录的。

- Windows7于2020年1月14 日正式停止更新维护服务；Windows10于2025年10月14日正式停止更新维护服务；停止更新服务意味着即使出现BUG也不会去修复，可能会遭到网络攻击，也可能会更容易中病毒。所以我的电脑全部更新到了Windows11。

- 关于下载Windows：

  | 版本      | 下载连接                                                     | 说明                                                         |
  | --------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | Windows10 | [下载 Windows 10 光盘映像（ISO 文件）](https://www.microsoft.com/zh-cn/software-download/windows10ISO) | 需要按下F12，将浏览器标识改为手机或平板后再次刷新网页即可回到以前的下载页面，可能微软后面会修复这个BUG。 |
  | Windows11 | [下载 Windows 11](https://www.microsoft.com/zh-cn/software-download/windows11) | 往下滑，找到**下载适用于 x64 设备的 Windows 11 磁盘映像 (ISO)**然后下载**适用于多版本ISO**下载64位即可。 |

  

- | 配置 | 电脑1（笔记本）                                              | 电脑2（台式机）                                              |
  | ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | CPU  | i7 10750H                                                    | i3 12100F                                                    |
  | 主板 | 联想Y7000 2020                                               | 华南H610m Plus                                               |
  | 内存 | 8GB DDR4 3200MHz 记忆科技 + 8GB DDR4 3200MHz 联想            | 16GB DDR4 3200MHz 金百达 + 16GB DDR4 3200MHz 金百达          |
  | 硬盘 | 512GB PCIe3.0 PC711 海力士固态硬盘 + 1TB PCIe 3.0 SN570西数蓝盘 | 1TB PCIe 4.0 KP260 金百达固态硬盘 + 闲置480GB SATA TC10 铠侠固态硬盘 + 限制1TB SATA 笔记本拆机机械硬盘 |
  | 显卡 | 4GB GTX1650                                                  | 8GB RTX4060                                                  |

  两台电脑性能差不多，都安装了Win11，但是台式机要比笔记本用起来更流畅一些，笔记本之前用的Win10，也升级过Win11，卡卡的；台式机相对流畅很多，所以台式机一直用的Win11。



### 2、激活Windows

激活Windows的方法有多种，这里仅供研究方法。

#### ①最简单的方法（使用在线Windows自带的PowerShell命令）

Ⅰ、在搜索框搜索PowerShell，右键以管理员身份运行：

![](https://active.freedash.top/Resource/Pic/20251026_001.png)

Ⅱ、输入`irm https://active.freedash.top/Resource/Active.txt | iex`或者`irm https://get.activated.win | iex`，然后回车，会得到下面这个页面。

![](https://active.freedash.top/Resource/Pic/20251026_002.png)

什么意思呢？

| 激活类型   | 支持的产品                         | 激活期限        | 是否需要联网 |
| ---------- | ---------------------------------- | --------------- | ------------ |
| HWID       | Windows 10、Windows11              | 永久            | 需要         |
| OHook      | Office                             | 永久            | 不需要       |
| TSforge    | Windows、ESU、Office               | 永久            | 需要         |
| KMS38      | Windows10 Server、WIndows11 Server | 直到2038年      | 不需要       |
| Online KMS | Windows、Office                    | 180天，可以续订 | 需要         |

![](https://active.freedash.top/Resource/Pic/20251026_003.png)

绿色图表的代表推荐，也就是1和2，都可以永久激活Windows和Office。

那么只需要接着输入1或者2回车即可。

我输入数字1，默认会一直操作，直到激活为止。

![](https://active.freedash.top/Resource/Pic/20251026_004.png)

#### ②使用HEU KMS软件激活

可以去Github下载：[Releases · zbezj/HEU_KMS_Activator](https://github.com/zbezj/HEU_KMS_Activator/releases)

为什么不推荐这个，因为会被Windows自带的`Windows Defender`作为病毒杀掉，需要关闭`Windows Defender`，这里就劝退很多人了。

#### ③使用正版Windows激活码激活

| 版本   | 售价                                                    | 链接                                                         |
| ------ | ------------------------------------------------------- | ------------------------------------------------------------ |
| 家庭版 | 1088元人民币                                            | [微软 Windows11 家庭版购买-Win11激活密钥官网下载-微软官方商城](https://www.microsoftstore.com.cn/windows/windows-11-home) |
| 专业版 | 在中国内，只能从家庭版升级专业版，在Microsoft Srote购买 | [将 Windows 家庭版升级到 Windows 专业版 - Microsoft 支持](https://support.microsoft.com/zh-cn/windows/将-windows-家庭版升级到-windows-专业版-ef34d520-e73f-3198-c525-d1a218cc2818) |

## 二、Office

个人有两个绑定账号的Office，一个是买笔记本送的，一个是在淘宝上买的；







