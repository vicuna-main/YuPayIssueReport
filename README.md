# ✨ YuPay Issue Report | 问题反馈处 ✨

<p align="center">
  <strong>💳 为 Minecraft Java 版服务器打造的现代化赞助支付与自动发奖插件</strong><br>
  <em>Modern donation payment and automatic reward plugin for Minecraft: Java Edition Servers</em>
</p>

---

## 🇨🇳 中文版

### 📌 问题反馈处
若您在使用 **YuPay** 过程中遇到任何问题、Bug、兼容性异常或功能建议，请在此处提交反馈。  
> ✨ **格式完整、内容详实** 的反馈将会获得 **优先处理**！  
感谢您的支持与理解，每一份反馈都是让插件变得更好的动力 ❤️

### 🧩 插件简介
**YuPay** 是一款面向 Minecraft 服务器赞助场景打造的现代化支付插件，集成微信支付与支付宝支付，提供订单创建、二维码支付、支付回调、自动发奖、赞助排行榜、赞助总额统计、订单历史、卡密核销、退款流程、跨服发奖、健康检查与安全审计等能力。插件支持直接对接微信 / 支付宝官方接口，帮助服务器构建可审计、可追踪、可扩展的赞助系统。

### ✨ 核心能力
- `/yupaypay` 发起赞助，别名 `/ypay`
- `/yupaytop` 查看赞助排行榜，`/yupaytotal` 查看赞助总额
- `/yupay` 管理订单、重载、配置、封禁、转换、卡密、退款、审计与健康检查
- 微信支付与支付宝支付渠道，支持二维码与异步回调
- 订单生命周期管理：创建、取消、过期、补发、查询、异常诊断
- 自动发奖与跨服发奖，支持命令奖励与经济奖励
- 卡密系统：创建、启用 / 停用、修改、查询、列表、核销记录
- 退款流程：玩家申请、管理员审核、直接退款、状态同步
- SQLite / MySQL 存储、回调账本、安全审计、敏感信息脱敏
- Vault、PlayerPoints、PlaceholderAPI、ProtocolLib 等可选联动

### 🛠️ 兼容性说明
YuPay 基于 Bukkit / Spigot 生态设计，面向需要官方支付渠道、赞助统计与自动发奖的 Minecraft Java 版服务器。建议在正式服中使用经过充分测试的 Paper / Spigot / Bukkit 系服务端，并确保 Java、数据库与网络回调环境稳定。

支持或可选联动包括：

- Vault
- PlaceholderAPI
- PlayerPoints
- ProtocolLib
- SQLite / MySQL
- 微信支付 / 支付宝支付官方接口

如遇兼容性问题，请在 QQ 群或 Issues 内反馈，并尽量附带服务端核心、Minecraft 版本、插件版本、Java 版本、数据库类型、支付渠道、回调地址配置、报错日志与复现步骤。

### 🔗 官方链接
- 💬 **插件 QQ 交流群**：[点击加入](https://qm.qq.com/q/CihYemKufS)
- 📚 **插件 Wiki / 使用文档**：[YuPluginHub](https://vicuna-main.github.io/YuPluginHub/)
- 🐛 **Bug 与建议反馈**：[GitHub Issues](https://github.com/vicuna-main/YuPayIssueReport)
- ☕ **高级版本赞助**：[爱发电支持](https://afdian.com/item/0699c320541211f1b9e952540025c377)

> ⚠️ 本插件仅限用于服务器赞助用途；请确保使用方式符合当地法律法规及微信 / 支付宝等支付平台规则。

### 📝 反馈建议格式
为了更快定位问题，提交反馈时建议包含以下信息：

```text
插件版本：
服务端核心：
Minecraft 版本：
Java 版本：
是否为混合端：
数据库类型（SQLite/MySQL）：
支付渠道（微信/支付宝）：
是否启用回调服务器：
回调地址是否可公网访问：
是否安装 Vault / PlayerPoints / PlaceholderAPI / ProtocolLib：
订单号或退款号（如有）：
问题描述：
复现步骤：
完整报错日志：
截图或视频：
```

### 🧾 使用此插件的服务器信息
> 欢迎已安装 YuPay 的服主在此登记您的服务器～  
> 每条信息请包含：服务器名称、地址、QQ群（若有）、官网（若有）、版本。

| 服务器名称 | 服务器地址 | 服务器 QQ 群 | 官网 | 版本 |
|-----------|------------|--------------|------|------|
| 宇钛纪元 | mc.yutay.cn | 1011284597 | 待补充 | 1.21.1 |

---

## 🇬🇧 English Version

### 📌 Issue Tracker
If you encounter any issues, bugs, compatibility problems, or have suggestions while using **YuPay**, please submit your feedback here.  
> ✨ **Well-formatted and detailed reports** will be **prioritized**!  
Thank you for your support and understanding. Every report helps make the plugin better ❤️

### 🧩 Plugin Introduction
**YuPay** is a modern payment plugin for Minecraft server donation scenarios. It integrates WeChat Pay and Alipay, and provides order creation, QR-code payments, payment callbacks, automatic reward delivery, donation leaderboards, total donation statistics, order history, redeem codes, refund workflows, cross-server rewards, health checks, and security auditing. It connects directly to official WeChat / Alipay APIs to help servers build an auditable, traceable, and extensible donation system.

### ✨ Core Features
- `/yupaypay` starts a donation payment, with `/ypay` alias
- `/yupaytop` shows donation rankings, and `/yupaytotal` shows donation totals
- `/yupay` manages orders, reloads, settings, bans, conversion, redeem codes, refunds, audit, and health checks
- WeChat Pay and Alipay channels with QR-code payments and async callbacks
- Order lifecycle management: create, cancel, expire, retry rewards, query, and diagnose exceptions
- Automatic and cross-server reward delivery with command and economy rewards
- Redeem code system: create, enable / disable, modify, query, list, and redemption logs
- Refund workflows: player requests, admin review, direct refunds, and status sync
- SQLite / MySQL storage, callback ledger, security audit, and sensitive data masking
- Optional Vault, PlayerPoints, PlaceholderAPI, and ProtocolLib integrations

### 🛠️ Compatibility
YuPay is designed for the Bukkit / Spigot ecosystem and targets Minecraft: Java Edition servers that need official payment channels, donation statistics, and automatic reward delivery. For production use, run it on a thoroughly tested Paper / Spigot / Bukkit-based server and make sure Java, database, and public callback environments are stable.

Supported or optional integrations include:

- Vault
- PlaceholderAPI
- PlayerPoints
- ProtocolLib
- SQLite / MySQL
- WeChat Pay / Alipay official APIs

If you encounter compatibility issues, please report them in the QQ group or GitHub Issues and include your server core, Minecraft version, plugin version, Java version, database type, payment channel, callback URL settings, error logs, and reproduction steps whenever possible.

### 🔗 Official Links
- 💬 **Plugin QQ Group**: [Click to join](https://qm.qq.com/q/CihYemKufS)
- 📚 **Plugin Wiki / Documentation**: [YuPluginHub](https://vicuna-main.github.io/YuPluginHub/)
- 🐛 **Bug Reports & Suggestions**: [GitHub Issues](https://github.com/vicuna-main/YuPayIssueReport)
- ☕ **Sponsor Advanced Version**: [Support via AiFaDian](https://afdian.com/item/0699c320541211f1b9e952540025c377)

> ⚠️ This plugin is intended only for server donation scenarios. Make sure your usage complies with local laws and WeChat / Alipay payment platform rules.

### 📝 Suggested Report Format
To help us locate issues faster, please include the following information when submitting feedback:

```text
Plugin version:
Server core:
Minecraft version:
Java version:
Hybrid server or not:
Database type (SQLite/MySQL):
Payment channel (WeChat/Alipay):
Callback server enabled or not:
Callback URL publicly accessible or not:
Vault / PlayerPoints / PlaceholderAPI / ProtocolLib installed:
Order ID or refund ID if available:
Issue description:
Steps to reproduce:
Full error log:
Screenshots or videos:
```

### 🧾 Server Information Using This Plugin
> Server owners using YuPay are welcome to register their servers here.  
> Each entry should include: server name, address, QQ group if available, website if available, and version.

| Server Name | Server Address | Server QQ Group | Website | Version |
|-------------|----------------|-----------------|---------|---------|
| Yutay Era | mc.yutay.cn | 1011284597 | To be added | 1.21.1 |

---

<p align="center">
  <sub>Made with ❤️ for the Minecraft community</sub>
</p>
