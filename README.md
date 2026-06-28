# 🚀 麦卖云 V2bX 后端全能王牌脚本
<p align="center">
  <img src="https://img.shields.io/badge/Platform-Ubuntu%20%7C%20Debian%20%7C%20CentOS%20%7C%20Alpine-orange.svg" alt="Platform">
  <img src="https://img.shields.io/badge/Language-Shell-blue.svg" alt="Language">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/Status-Stable-brightgreen.svg" alt="Status">
  <a href="https://maimaiyun.shop"><img src="https://img.shields.io/badge/%F0%9F%8C%8D%20%E5%AE%98%E6%96%B9%E6%9C%BA%E5%9C%BA-%E9%A5%A6%E5%8D%96%E4%BA%91-blue.svg" alt="Website"></a>
</p>
---
一款专为 **V2bX 后端运维** 设计的“全能型”管理脚本。它不仅是一个简单的安装器，更是集成了**资源防爆控制、网络优化、深度日志净化、高并发调优**的一站式生产力工具，完美解决生产环境中的各种痛点。
🌐 **官方机场门户：** [麦卖云 (maimaiyun.shop)](https://maimaiyun.shop)
---
## ✨ 为什么选择这款脚本？

| 特性分类 | 功能描述 |
| :--- | :--- |
| 🌍 **全系统自适应** | 原生支持 `Systemd` (Ubuntu/Debian/CentOS) 与 `OpenRC` (Alpine) 双模式。 |
| 🛡️ **内核级防爆 (Anti-Explode)** | 独创资源护卫策略，通过 `GOMEMLIMIT` 限制内存，`CPUQuota` 压制性能，坚决防止节点爆内存导致服务器宕机。 |
| 🧹 **深度日志净化** | 集成模块化日志处理引擎，配合 `logrotate` 每小时强控，告别硬盘被日志塞爆的痛苦。 |
| ⚡ **极致网络优化** | 一键集成豪华版 **BBR 加速**，永久解锁 **TCP 高并发连接数**限制（大幅提升并发突破瓶颈）。 |
| 🔍 **全透明运维** | 拒绝“盲人运维”，日志全链路透明化，错误排查一目了然。 |
| 📦 **模块化架构** | 核心脚本轻量化，动态调用外部高级配置模块，升级无需重装。 |

---
## 📥 极速安装
在 **Root 权限** 下，选择以下任意一行命令执行即可：
### 选项 A：使用 wget 安装（推荐）
```bash
wget -N [https://raw.githubusercontent.com/yunfeibuzai/xmm/main/maimai](https://raw.githubusercontent.com/yunfeibuzai/xmm/main/maimai) && bash maimai

选项 B：使用 curl 安装

bash <(curl -fsSL [https://raw.githubusercontent.com/yunfeibuzai/xmm/main/maimai](https://raw.githubusercontent.com/yunfeibuzai/xmm/main/maimai))

