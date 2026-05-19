# Log To Alert

[中文版](./README_zh.md)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0-blue)](SKILL.md)

> user provides server log text and needs to extract error patterns into actionable alerts

## What Problem This Solves

Brief paragraph explaining the specific engineering problem this skill solves.
When triggered: [trigger condition].

## Features

- Feature 1
- Feature 2
- Feature 3

## Quick Start

### Installation

```bash
# Via ClawHub
clawhub install Log To Alert

# Or manually
cp -r Log To Alert ~/.openclaw/skills/
```

### Usage

```bash
# Mode 1
clawhub run Log To Alert --mode read

# Mode 2
clawhub run Log To Alert --mode write --input ./data.json
```

## Directory Structure

```
Log To Alert/
├── SKILL.md          # Entry point
├── LICENSE           # MIT
├── README.md         # This file
├── README_zh.md      # Chinese version
├── CONTRIBUTING.md    # Contribution guide
├── .gitignore
├── references/       # Templates and schemas
│   └── ...
└── scripts/          # Helper scripts (if any)
    └── ...
```

## Configuration

| Variable | Required | Description |
|----------|----------|-------------|
| `API_KEY` | Yes | API key for the service |

## License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.

---

Powered by [MiniMax](https://minimax.io).