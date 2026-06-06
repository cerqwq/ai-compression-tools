# 📦 AI Compression Tools

AI压缩工具，支持数据压缩、图片压缩、视频压缩。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 🏗️ 压缩策略设计
- 🖼️ 图片优化方案
- 🎬 视频压缩方案
- 📋 Brotli配置
- ⚖️ 算法比较
- 🌐 CDN压缩设计

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from ai_compression_tools import create_tools

tools = create_tools()

# 压缩策略
strategy = tools.design_compression_strategy("JSON数据", {"ratio": "高"})

# 图片优化
image = tools.generate_image_optimization("电商网站")

# 视频压缩
video = tools.generate_video_compression("YouTube", "高清")

# Brotli配置
brotli = tools.generate_brotli_config("静态资源")

# 算法比较
comparison = tools.compare_compression_algorithms("文本数据")

# CDN压缩
cdn = tools.design_cdn_compression(["HTML", "CSS", "JS", "图片"])
```

## 📁 项目结构

```
ai-compression-tools/
├── tools.py       # 压缩工具核心
└── README.md
```

## 📄 许可证

MIT License
