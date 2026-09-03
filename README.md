<div align="center">

# 📊 凯利公式财富博弈模拟器

**无限按钮 + 蒙特卡洛模拟，亲手感受"久赌必输"与仓位管理**

[![Live Demo](https://img.shields.io/badge/🎮_在线体验-点开即玩-722ed1?style=for-the-badge)](https://BEE-COME.github.io/keili/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/BEE-COME/keili)](https://github.com/BEE-COME/keili/commits/main)

🌐 在线体验：**https://BEE-COME.github.io/keili/**

</div>

> 别再空谈凯利公式了——按 100 次按钮，看看你的本金还剩多少。

## 🎮 玩法

| 模式 | 操作 | 说明 |
| :--- | :--- | :--- |
| 👆 手动 | 按"按一下按钮" | 每次 50% 概率本金 ×9，50% 概率只剩 ×0.1，心跳拉满 |
| 🤖 自动 | 按"开始自动" | 机器替你连按，可随时停止，适合跑大样本 |
| 🔄 重置 | 按"重置" | 本金、次数、曲线一键清零，再来一局 |

## ✨ 功能特性

- 📈 **资金曲线图**（Chart.js）：每一按都落在曲线上，直观看到波动与回撤
- 🧮 **实时统计卡**：次数、余额、胜负，一目了然
- 📱 **移动端优化**：大按钮、单列布局，手机上也能连按
- ⚡ **零构建单文件**：一个 `index.html` 即全部，CDN 引入 Chart.js，双击就能跑（需联网加载图表库）

## 🧠 背后的数学（一句话版）

期望值为正的游戏也可能让你破产——关键在**下注比例**。凯利公式告诉你每次该押多少，本模拟器让你用手指先亏明白，再去看公式。

## 🚀 本地运行

直接双击 `index.html`（需联网加载 Chart.js CDN），或：
```bash
npx serve .
```

## 📁 目录结构

```
keili/
├── index.html  # 全部：UI + 模拟逻辑 + 图表
├── README.md   # 本文档
└── LICENSE     # MIT 开源协议
```

## 📄 开源协议

本项目采用 [MIT](./LICENSE) 协议，© BEE-COME。拿去教学、魔改随意，亏了钱别找我 😄
