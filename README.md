# Clash 转换配置库

这是一个用于Clash代理工具的配置和转换规则库。

## 📋 项目说明

本项目为Clash代理工具提供自定义规则集合和代理组配置。包含多地区节点分组、媒体服务分流、游戏平台支持等功能。

## 📂 文件结构

- **clash_guize.ini** - Clash规则配置文件
  - 基于ACL4SSR规则集
  - 包含广告拦截、应用净化、全球直连等规则分类
  - 支持自动测速、微软分流、苹果分流等功能

- **FuXieJiaoBen.yaml** - Clash Party 代理组转换配置文件
  - 为Clash Party专用配置
  - 定义各地区节点组（香港、台湾、新加坡、日本、美国、韩国等）
  - 包含自动选择、手动切换等策略
  - 支持Telegram、OpenAI、Gemini等专用分流

## 🎯 核心功能

### 规则分类
- 🎯 全球直连 - 国内网站和本地局域网
- 🛑 广告拦截 - 去除各类广告
- 🍃 应用净化 - 清理应用内置广告
- 📢 谷歌FCM - Google推送服务
- Ⓜ️ 微软服务 - OneDrive、Microsoft服务
- 🍎 苹果服务 - Apple相关服务
- 📲 电报消息 - Telegram服务
- 🎶 网易音乐 - 国内音乐服务
- 🎮 游戏平台 - Steam、Epic、Xbox、PlayStation等
- 🎵 媒体服务 - TikTok、Spotify、Disney+、Netflix等

### 代理策略
- ♻️ 自动选择 - 自动选择最优节点（URL测试）
- 🚀 手动切换 - 手动选择代理节点
- 🌍 国外媒体 - 国外媒体服务专用
- 🌏 国内媒体 - 国内媒体直连

## 💬 专用分流

- OpenAI
- Gemini
- Telegram

## 🔧 使用方法

1. **clash_guize.ini** - 用于规则转换工具（如ACL4SSR Online）生成Clash配置
2. **FuXieJiaoBen.yaml** - Clash Party专用配置文件，可直接导入Clash Party使用

## 📝 注意事项

- 不要随意改变配置文件中的关键字，否则会导致出错
- 规则源来自ACL4SSR、blackmatrix7等第三方维护的规则库
- 建议定期更新规则以获取最新的分流效果

## 📦 依赖

- Clash 代理工具
- 可选：ACL4SSR Online（用于处理clash_guize.ini）

## 📄 许可证

遵循导入的规则库的相应许可证

---

**最后更新**: 2026年4月
