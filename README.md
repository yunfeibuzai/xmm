# 🚀 麦卖云 V2bX 后端全能王牌脚本
![Platform](https://img.shields.io/badge/Platform-Ubuntu%20%7C%20Debian%20%7C%20CentOS%20%7C%20Alpine-orange)
![Language](https://img.shields.io/badge/Language-Shell-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Stable-brightgreen)
一款专为 **V2bX 后端运维** 设计的“全能型”管理脚本。它不仅是一个简单的安装器，更是集成了**资源防爆、网络优化、深度日志净化、高并发调优**的一站式生产力工具，专为生产环境稳定性而生。
---
## ✨ 核心特性

| 特性分类 | 功能描述 |
| :--- | :--- |
| 🌍 **全系统自适应** | 原生支持 `Systemd` (Ubuntu/Debian/CentOS) 与 `OpenRC` (Alpine) 双模式。 |
| 🛡️ **内核级防爆 (Anti-Explode)** | 独创资源护卫策略，通过 `GOMEMLIMIT` 限制内存，`CPUQuota` 压制性能，坚决防止节点爆内存导致服务器宕机。 |
| 🧹 **深度日志净化** | 集成模块化日志处理引擎，配合 `logrotate` 每小时强控，告别硬盘被日志塞爆的痛苦。 |
| ⚡ **极致网络优化** | 一键集成豪华版 **BBR 加速**，永久解锁 **TCP 高并发连接数**限制。 |
| 🔍 **全透明运维** | 拒绝“盲人运维”，日志全链路透明化，错误排查一目了然。 |
| 📦 **模块化架构** | 核心脚本轻量化，动态调用外部高级配置模块，升级无需重装。 |

---
## 📥 极速安装
在 **Root 权限** 下，选择以下任意一行命令执行即可：
### 选项 A：使用 wget 安装（推荐）
```bash
wget -N [https://raw.githubusercontent.com/yunfeibuzai/xmm/main/maimai](https://raw.githubusercontent.com/yunfeibuzai/xmm/main/maimai) && bash maimai

