# EverTemp — Temperature Tracker & Fever Log

<p align="center">
  <img src="screenshots/IMG_0015.PNG" width="155">
  <img src="screenshots/IMG_0010.PNG" width="155">
  <img src="screenshots/IMG_0016.PNG" width="155">
  <img src="screenshots/IMG_0012.PNG" width="155">
  <img src="screenshots/IMG_0017.PNG" width="155">
</p>

<p align="center">
  <strong>Track Fever · Analyze Trends · Medication Reminders</strong><br>
  <sub>体温记录 · 趋势分析 · 用药提醒</sub><br>
  <sub>Designed for families and caregivers to track every fever from start to finish.</sub>
</p>

---

## Features 功能

| | |
|---|---|
| 📋 **Multiple Profiles** | Create individual profiles for every family member — one app for the whole family.<br><sub>为家中每位成员创建独立档案，一个 App 管全家</sub> |
| 🌡️ **Quick Logging** | Log temperature, symptoms, and fever medication all in one screen.<br><sub>精准体温输入 + 症状勾选 + 退烧药选择，一屏完成</sub> |
| ⏰ **Dose Reminders** | Automatically calculates the next dose time and sends a local notification.<br><sub>服药后自动计算下次用药时间，本地通知准时提醒</sub> |
| 📈 **Trend Chart** | Color-coded line chart (Normal / Low / Mid / High Fever) in landscape view.<br><sub>横屏折线图，正常 / 低烧 / 中烧 / 高烧颜色分级，一目了然</sub> |
| 📊 **7-Day Overview** | At-a-glance peak temperature, fever count, medicine count, and next dose time.<br><sub>实时展示峰值体温、发烧次数、服药次数、下次用药时间</sub> |
| 🤖 **AI Consult** | Copies a fever & medication summary to clipboard for use in any AI app. Data never leaves your device.<br><sub>一键将体温摘要复制并跳转 AI 应用咨询，数据不离设备</sub> |
| 📄 **PDF Export** | Generate a report with temperature chart, perfect for sharing with your doctor.<br><sub>生成含体温曲线图的报告，方便就医时分享</sub> |
| 🌙 **Dark Mode** | Full support for system light / dark mode.<br><sub>完整支持系统深色 / 浅色模式自动切换</sub> |
| 🌐 **Multilingual** | English · Simplified Chinese · Traditional Chinese · Japanese<br><sub>英文 · 简体中文 · 繁体中文 · 日本語</sub> |

---

## Screenshots 截图

### English Interface

<p align="center">
  <img src="screenshots/IMG_0015.PNG" width="160" alt="Home Screen">
  <img src="screenshots/IMG_0010.PNG" width="160" alt="Add Record">
  <img src="screenshots/IMG_0016.PNG" width="160" alt="Temperature Trend">
  <img src="screenshots/IMG_0017.PNG" width="160" alt="AI Consult">
</p>

### 中文界面

<p align="center">
  <img src="screenshots/IMG_0009.PNG" width="160" alt="首页（空状态）">
  <img src="screenshots/IMG_0011.PNG" width="160" alt="体温列表">
  <img src="screenshots/IMG_0012.PNG" width="160" alt="概览与用药提醒">
  <img src="screenshots/IMG_0013.PNG" width="160" alt="体温趋势图">
</p>

---

## Privacy 隐私

All data is stored **locally on your device only** and never uploaded to any server.  
所有数据仅保存在您的设备本地，不会上传至任何服务器。

The AI feature copies a text summary to your clipboard — you choose which AI app to use.  
AI 咨询功能通过剪贴板传递摘要文本，由用户自行选择使用哪款 AI 应用。

---

## Support 支持

For bug reports or feature requests, please open an **[Issue](https://github.com/levili-T/EverTemp/issues)**.  
遇到问题或有功能建议，请在 **[Issues](https://github.com/levili-T/EverTemp/issues)** 提交反馈。

---

## Tech Stack 技术栈

- **Flutter** 3.22+ / Dart 3.4+
- `sqflite` — Local SQLite database / 本地 SQLite 数据库
- `fl_chart` — Temperature trend chart / 体温趋势折线图
- `flutter_local_notifications` — Dose reminder notifications / 用药提醒通知
- `provider` — State management / 状态管理
- `pdf` + `printing` — PDF report export / PDF 报告导出
- `flutter_slidable` — Swipe actions / 滑动操作

---

<p align="center">Made with ❤️ for families</p>

<p align="center"><strong>We hope this is the least-opened app on your phone.<br><sub>希望这是你手机里启动次数最少的 App。</sub></strong></p>
