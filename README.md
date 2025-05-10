<div align="center">

![GitHub Header](https://git.kejizero.online/zhao/files/raw/branch/main/images/370035003-6d37cd69-a232-4444-9f91-30e5942a8938.svg)

**基于 [OpenWrt](https://github.com/openwrt/openwrt) 打造的高效固件，覆盖 Rockchip、X86_64、Mediatek、Qualcommax 平台，专为进阶用户设计！**

</div>

---

## 📂 固件展示 / 预览截图

| 基本                                              | 状态 | 基本                         | 状态 |
|:-------------------------------------------------:|:----:|:----------------------------:|:----:|
| kmod 内核模块安装                                 | ✅   | 全锥型 NAT（NFT、BCM 双方案）| ✅   |
| SS AES 硬件加速                                   | ✅   | 构建优化（O3、LTO）          | ✅   |
| GPU 硬件加速                                      | ✅   | 内核/模块 优化（Clang/LLVM） | ✅   |
| HDMI 终端输出                                     | ✅   | 在线 OTA 升级（squashfs）    | ✅   |
| RTC 时钟 (HYM8563)                                | ✅   | 固件重置（squashfs）         | ✅   |
| BBRv3 拥塞控制                                    | ✅   | LLVM-BPF 支持                | ✅   |
| TCP Brutal 拥塞控制                               | ✅   | Shortcut-FE（支持 UDP 入站） | ✅   |
| KVM 虚拟化支持                                    | ✅   | LRNG 随机数（v57）           | ✅   |
| NGINX & CURL HTTP3/QUIC 支持                      | ✅   | PWM 风扇控制                 | ✅   |


| 内置插件                 | 状态 | 内置插件         | 状态 |
|:------------------------:|:----:|:----------------:|:----:|
| PassWall                 | ✅   | Docker           | ✅   |
| HomeProxy                | ✅   | TTY 终端         | ✅   |
| FileBrowser              | ✅   | NetData 监控     | ✅   |
| qBittorrent              | ✅   | DiskMan 磁盘管理 | ✅   |
| MosDNS                   | ✅   | CPU 性能调节     | ✅   |
| 动态 DNS                 | ✅   | SQM 列队管理     | ✅   |
| Watchcat                 | ✅   | nlbw 宽带监控    | ✅   |
| KMS 服务器               | ✅   | Socat            | ✅   |
| FRP 客户端               | ✅   | 应用过滤         | ✅   |
| 网络唤醒                 | ✅   | 访问控制         | ✅   |
| 网络共享（Samba）        | ✅   | UPnP             | ✅   |
| 锐捷认证                 | ✅   | IP 限速          | ✅   |
| Aria2                    | ✅   | WireGuard        | ✅   |
| Alist 文件列表           | ✅   | L2TP             | ✅   |
| USB 打印服务器           | ✅   | ZeroTier         | ✅   |
| 隔空播放（AirConnect）   | ✅   | WebDav           | ✅   |
| 自定义命令               | ✅   | AirPlay 2        | ✅   |
| 网速测试                 | ✅   | NATMap           | ✅   |

✅ 可用

❌ 不可用

⏳ 计划中

<div align="center">

![示例图 1](https://git.kejizero.online/zhao/files/raw/branch/main/images/0001.png)  
![示例图 2](https://git.kejizero.online/zhao/files/raw/branch/main/images/0002.png)  
![示例图 3](https://git.kejizero.online/zhao/files/raw/branch/main/images/0003.png)  
![示例图 4](https://git.kejizero.online/zhao/files/raw/branch/main/images/0004.png)

</div>

---

## 🔍 固件信息概览

- 🛠 **源码基础**：[OpenWrt 官方]
  - Rockchip / x86_64：基于 [OpenWrt 官方](https://github.com/openwrt/openwrt)
  - Mediatek：基于 [Padavanonly](https://github.com/padavanonly/immortalwrt-mt798x-24.10)
  - ARMv8、Qualcommax、Bcm27xx、Bcm53xx：基于 [Lede](https://github.com/coolsnowwolf/lede)

- 🔧 **默认设置**：
  - 管理地址：`10.0.0.1`，密码：`password` 或留空
  - 所有 LAN 口均可访问网页终端和 SSH
  - WAN 默认启用防火墙保护
  - Docker 已切换为国内源，支持镜像加速

- 🚀 **增强支持**（x86_64 / Rockchip）：
  - GPU 硬件加速支持
  - BBRv3 拥塞控制
  - Shortcut-FE 支持 UDP 入站
  - NAT6 和全锥型 NAT（NFT / BCM 方案）

- 🎛 **功能优化**：
  - 内置 ZeroWrt 设置菜单，轻松管理
  - 支持高级插件、自定义启动项

---

## 💬 交流群与支持

如有技术问题或想交流使用经验，可加入我们的讨论群：

- 🧧 QQ 交流群：579896728 👉 [点击加入](https://qm.qq.com/q/oe4EAtvPIO)
- 🌐 Telegram 群组 👉 [点击加入](https://t.me/kejizero)

---

## 💰 打赏支持

感谢你的支持，我们会将每一笔打赏用于改善服务与开发。**打赏 20 元以上可获取 VIP 区域访问权限！**

👉 [点击打赏](https://pay.kejizero.online)

---

## 🏆 鸣谢来源

- [OpenWrt 官方源码](https://github.com/openwrt/openwrt)
- [Lean's LEDE](https://github.com/coolsnowwolf/lede)
- [ImmortalWrt](https://github.com/immortalwrt/immortalwrt)
- [padavanonly的ImmortalWrt分支](https://github.com/padavanonly/immortalwrt-mt798x-24.10)

---

## ⚠️ 免责声明

> - 本固件仅供学习研究，请勿用于商业用途  
> - 使用本固件所带来的一切后果由使用者自行承担  
> - 不保证完全无 bug，开发者不提供定制支持  
> - 请遵守国家网络安全相关法律法规  
