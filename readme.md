<p align="center">
  <img src="/images/wled_logo_akemi.png">
  <a href="https://github.com/kslpix/WLED_ZH/releases"><img src="https://img.shields.io/github/release/kslpix/WLED_ZH.svg?style=flat-square"></a>
  <a href="https://raw.githubusercontent.com/kslpix/WLED_ZH/master/LICENSE"><img src="https://img.shields.io/github/license/kslpix/WLED_ZH?color=blue&style=flat-square"></a>
  <a href="https://wled.discourse.group"><img src="https://img.shields.io/discourse/topics?colorB=blue&label=forum&server=https%3A%2F%2Fwled.discourse.group%2F&style=flat-square"></a>
  <a href="https://discord.gg/QAh7wJHrRM"><img src="https://img.shields.io/discord/473448917040758787.svg?colorB=blue&label=discord&style=flat-square"></a>
  <a href="https://kno.wled.ge"><img src="https://img.shields.io/badge/quick_start-wiki-blue.svg?style=flat-square"></a>
  <a href="https://github.com/Aircoookie/WLED-App"><img src="https://img.shields.io/badge/app-wled-blue.svg?style=flat-square"></a>
  <a href="https://gitpod.io/#https://github.com/kslpix/WLED_ZH"><img src="https://img.shields.io/badge/Gitpod-ready--to--code-blue?style=flat-square&logo=gitpod"></a>

  </p>

# 欢迎来到 WLED-ZH 项目! ✨

快速且功能丰富的 ESP8266/ESP32 网络服务器实现，用于控制 NeoPixel(WS2812B、WS2811、SK6812)LED 或基于 SPI 的芯片组，如 WS2801 和 APA102！

## ⚙️ 特性
- 98% 汉化程度(usermod 暂时无法汉化)
- WS2812FX 库，有 100 多种特效 
- FastLED 噪声效果和 50 个调色板 
- 具有颜色、效果和分段控件的现代用户界面 
- 分段以将不同的效果和颜色设置为用户定义的 LED 灯串部分 
- 设置页面 - 通过网络进行配置 
- 接入点和站模式 - 自动故障安全 AP 
- 每个实例最多 10 个 LED 输出
- 支持 RGBW 条带 
- 多达 250 个用户预设可轻松保存和加载颜色/效果，支持循环浏览它们。 
- 预设可用于自动执行 API 调用 
- 夜灯功能(逐渐变暗) 
- 完整的OTA软件可更新性(HTTP + ArduinoOTA)，密码保护 
- 可配置的模拟时钟(通过 usermods 支持 Cronixie、7 段和 EleksTube IPS 时钟)
- 可配置自动亮度限制，确保安全操作 
- 基于文件系统的配置，便于备份预设和设置 

## 💡 支持的灯光控制接口
- 适用于 [Android](https://play.google.com/store/apps/details?id=com.aircoookie.WLED) 和 [iOS](https://apps.apple.com/us/app/wled/id1475695033) 的 WLED 应用程序
- JSON 和 HTTP 请求 API 
- MQTT
- E1.31、Art-Net、DDP 和 TPM2.net
- [diyHue](https://github.com/diyhue/diyHue) (Wled 由 diyHue 支持，包括 udp 下的 Hue Sync Entertainment。感谢 [Gregory Mallios](https://github.com/gmallios))
- [hyperion](https://github.com/hyperion-project/hyperion.ng)
- UDP 实时 
- Alexa 语音控制(包括调光和颜色) 
- 与飞利浦色调灯同步 
- Adalight(通过串行的 PC 流光溢彩)和 TPM2 
- 多个 WLED 器件的同步颜色(UDP 通知器) 
- 红外遥控器(24键RGB，需要接收器) 
- 简单的计时器/时间表(来自 NTP 的时间，支持时区/DST) 

## 📲 快速入门指南和文档

请参阅[我们官方网站上的文档](https://kno.wled.ge)！

[本页内容](https://kno.wled.ge/basics/tutorials/) 您可以找到出色的教程和工具来帮助您启动和运行新项目！

## 🖼️ 用户界面
<img src="/images/macbook-pro-space-gray-on-the-wooden-table.jpg" width="50%"><img src="/images/walking-with-iphone-x.jpg" width="50%">

## 💾 兼容硬件

参阅 [这里](https://kno.wled.ge/basics/compatible-hardware)!

## ✌️ 其他

开源协议 MIT 许可证
致谢[这里](https://kno.wled.ge/about/contributors/)！

加入 Discord 服务器，讨论有关 WLED 的一切！

<a href="https://discord.gg/QAh7wJHrRM"><img src="https://discordapp.com/api/guilds/473448917040758787/widget.png?style=banner2" width="25%"></a>

查看 WLED [Discord](https://wled.discourse.group)！ 

您也可以向我发送邮件至 [dev.aircoookie@gmail.com](mailto:dev.aircoookie@gmail.com)，但请仅在您想私下与我交谈时才这样做。 

如果WLED真的照亮了你的一天，你可以[![](https://img.shields.io/badge/send%20me%20a%20small%20gift-paypal-blue.svg?style=flat-square)](https://paypal.me/aircoookie)

*免责声明：*  

如果您容易患上光敏性癫痫，我们建议您不要使用本软件。 
如果您仍想尝试，请不要使用频闪、灯光或噪音模式或高效果速度设置。

根据 MIT 开源协议，我对您或任何其他人或设备造成的任何损害不承担任何责任。 

