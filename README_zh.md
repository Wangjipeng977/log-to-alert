# Log To Alert

[English](./README.md)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![版本](https://img.shields.io/badge/version-1.0-blue)

> user provides server log text and needs to extract error patterns into actionable alerts

## 解决什么问题

简要说明这个技能解决的具体工程问题。
触发条件：[trigger condition]。

## 功能特性

- 特性 1
- 特性 2
- 特性 3

## 快速开始

### 安装

```bash
# 通过 ClawHub 安装
clawhub install Log To Alert

# 或手动复制
cp -r Log To Alert ~/.openclaw/skills/
```

### 使用方法

```bash
# 模式 1：读取
clawhub run Log To Alert --mode read

# 模式 2：写入
clawhub run Log To Alert --mode write --input ./data.json
```

## 目录结构

```
Log To Alert/
├── SKILL.md          # 技能入口
├── LICENSE           # MIT 许可证
├── README.md         # 英文说明
├── README_zh.md      # 本文件
├── CONTRIBUTING.md    # 贡献指南
├── .gitignore
├── references/       # 模板和 schema
│   └── ...
└── scripts/          # 辅助脚本（如有）
    └── ...
```

## 配置

| 变量名 | 必填 | 说明 |
|--------|------|------|
| `API_KEY` | 是 | 服务 API Key |

## 许可证

本项目采用 MIT 许可证 — 详见 [LICENSE](LICENSE)。

---

由 [MiniMax](https://minimax.io) 提供支持。