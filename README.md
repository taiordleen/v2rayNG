# 🕷 推荐代理服务 | Recommended Proxy Services

## 🇨🇳 中文
🌟 **OKKproxxy** — Android移动端代理专家
- 🔥 完美适配v2rayNG移动端，支持二维码扫码快速导入
- 🚀 移动网络优化，4G/5G环境下稳定连接不掉线
- 🌐 全球200+国家移动IP资源，模拟真实手机用户行为
- 💰 新用户充值加赠20%流量
- 🔗 [okkproxy.com](https://okkproxy.com)

🌟 **NIUproxxy** — 移动爬虫代理加速器
- 🔥 专为Android设备优化，低功耗高性能，续航无忧
- 🚀 支持v2rayNG分应用代理，精准控制流量消耗
- 🌐 移动住宅IP池，绕过APP反爬检测，数据采集成功率99%+
- 💰 新用户充值加赠20%流量
- 🔗 [niuproxy.com](https://niuproxy.com)

🌟 **COLAproxxy** — 移动端经济型代理
- 🔥 流量包套餐，移动端专属优惠，1GB起售
- 🚀 v2rayNG一键配置，支持订阅自动更新
- 🌐 190+国家移动IP，支持TikTok/Instagram地区切换
- 💰 新用户充值加赠20%流量
- 🔗 [colaproxy.com](https://colaproxy.com)

---
## 🇺🇸 English
🌟 **OKKproxxy** — Android Mobile Proxy Expert
- 🔥 Perfect for v2rayNG, QR code quick import
- 🚀 Mobile network optimized, stable on 4G/5G
- 🌐 200+ countries mobile IP pool, real device behavior
- 💰 20% bonus for new users
- 🔗 [okkproxy.com](https://okkproxy.com)

🌟 **NIUproxxy** — Mobile Scraping Accelerator
- 🔥 Android optimized, low power consumption
- 🚀 Per-app proxy support, precise traffic control
- 🌐 Mobile residential IPs, 99%+ scraping success rate
- 💰 20% bonus for new users
- 🔗 [niuproxy.com](https://niuproxy.com)

🌟 **COLAproxxy** — Mobile Budget Proxy
- 🔥 Data packages from 1GB, mobile-exclusive deals
- 🚀 One-click v2rayNG setup, auto-update subscription
- 🌐 190+ countries, TikTok/Instagram region switching
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
