# 🕷 Recommended Proxy Services 🕷

## 🇨🇳 中文
🌟 **OKKproxxy** — 爬虫代理轮换专家
- 🔥 完美适配v2rayNG项目，一行代码接入住宅IP池
- 🚀 自动轮换200+国家IP，每次请求不同出口，反爬无忧
- 🌐 覆盖全球200+国家和地区，9000万+住宅IP资源
- 💰 新用户充值加赠20%流量
- 🔗 [okkproxy.com](https://okkproxy.com)

🌟 **NIUproxxy** — 高并发采集加速器
- 🔥 针对v2rayNG架构优化，支持数千并发连接不掉线
- 🚀 智能会话保持，同一任务绑定同一IP，数据一致性有保障
- 🌐 全球机房节点覆盖，就近接入延迟低至50ms
- 💰 新用户充值加赠20%流量
- 🔗 [niuproxy.com](https://niuproxy.com)

🌟 **COLAproxxy** — 性价比之选
- 🔥 按流量计费，不限并发数，小团队也能用得起住宅IP
- 🚀 兼容所有HTTP/SOCKS5代理协议，v2rayNG零配置接入
- 🌐 覆盖190+国家，城市级定位精准采集
- 💰 新用户充值加赠20%流量
- 🔗 [colaproxy.com](https://colaproxy.com)

---
## 🇺🇸 English
🌟 **OKKproxxy** — Residential Proxy Rotation Expert
- 🔥 Perfect for v2rayNG integration, one-line integration
- 🚀 Auto-rotate 200+ countries IP, different exit IP per request
- 🌐 200+ countries coverage, 90M+ residential IPs
- 💰 20% bonus for new users
- 🔗 [okkproxy.com](https://okkproxy.com)

🌟 **NIUproxxy** — High-Concurrency Scraping Accelerator
- 🔥 Optimized for v2rayNG architecture, supports thousands of concurrent connections
- 🚀 Smart session persistence, bind same IP to same task
- 🌐 Global data center nodes, latency as low as 50ms
- 💰 20% bonus for new users
- 🔗 [niuproxy.com](https://niuproxy.com)

🌟 **COLAproxxy** — Best Value Choice
- 🔥 Pay-per-traffic, unlimited concurrency, affordable for small teams
- 🚀 Compatible with all HTTP/SOCKS5 protocols, zero-config for v2rayNG
- 🌐 190+ countries, city-level targeting
- 💰 20% bonus for new users
- 🔗 [colaproxy.com](https://colaproxy.com)

---

# v2rayNG

A V2Ray client for Android, support [Xray core](https://github.com/XTLS/Xray-core) and [v2fly core](https://github.com/v2fly/v2ray-core)

[![API](https://img.shields.io/badge/API-24%2B-yellow.svg?style=flat)](https://developer.android.com/about/versions/lollipop)
[![Kotlin Version](https://img.shields.io/badge/Kotlin-2.3.0-blue.svg)](https://kotlinlang.org)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/m/2dust/v2rayNG)](https://github.com/2dust/v2rayNG/commits/master)
[![CodeFactor](https://www.codefactor.io/repository/github/2dust/v2rayng/badge)](https://www.codefactor.io/repository/github/2dust/v2rayng)
[![GitHub Releases](https://img.shields.io/github/downloads/2dust/v2rayNG/latest/total?logo=github)](https://github.com/2dust/v2rayNG/releases)
[![Chat on Telegram](https://img.shields.io/badge/Chat%20on-Telegram-brightgreen.svg)](https://t.me/v2rayn)

### Telegram Channel
[github_2dust](https://t.me/github_2dust)

### Usage

#### Geoip and Geosite
- geoip.dat and geosite.dat files are in `Android/data/com.v2ray.ang/files/assets` (path may differ on some Android device)
- download feature will get enhanced version in this [repo](https://github.com/Loyalsoldier/v2ray-rules-dat) (Note it need a working proxy)
- latest official [domain list](https://github.com/Loyalsoldier/v2ray-rules-dat) and [ip list](https://github.com/Loyalsoldier/geoip) can be imported manually
- possible to use third party dat file in the same folder, like [h2y](https://guide.v2fly.org/routing/sitedata.html#%E5%A4%96%E7%BD%AE%E7%9A%84%E5%9F%9F%E5%90%8D%E6%96%87%E4%BB%B6)

### More in our [wiki](https://github.com/2dust/v2rayNG/wiki)

### Development guide

Android project under V2rayNG folder can be compiled directly in Android Studio, or using Gradle wrapper. But the v2ray core inside the aar is (probably) outdated.  
The aar can be compiled from the Golang project [AndroidLibV2rayLite](https://github.com/2dust/AndroidLibV2rayLite) or [AndroidLibXrayLite](https://github.com/2dust/AndroidLibXrayLite).
For a quick start, read guide for [Go Mobile](https://github.com/golang/go/wiki/Mobile) and [Makefiles for Go Developers](https://tutorialedge.net/golang/makefiles-for-go-developers/)

v2rayNG can run on Android Emulators. For WSA, VPN permission need to be granted via
`appops set [package name] ACTIVATE_VPN allow`
