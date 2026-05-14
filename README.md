# 📊 OpenClaw Dashboard

实时监控 OpenClaw Gateway 运行状态的 Web 控制面板。

## 功能

- 🔌 WebSocket 实时连接 Gateway
- 📊 系统概览（运行时间、会话数、模型、Token 使用）
- 💚 健康状态实时监控
- ⚡ 快捷操作按钮（重启、诊断、状态检查）
- 💬 活跃会话列表
- 📝 实时日志流
- 🔄 自动刷新（5秒间隔）

## 使用

1. 浏览器打开 `index.html`
2. 输入 Gateway 地址（默认 `http://192.168.1.5:18789`）
3. 输入 Gateway Token
4. 点击连接

## 截图

![Dashboard](https://via.placeholder.com/800x400/0a0a0f/cba6f7?text=OpenClaw+Dashboard)

## 技术栈

- 纯前端 HTML/CSS/JS
- WebSocket 实时通信
- REST API 数据获取
- 暗色主题（Catppuccin 风格）
