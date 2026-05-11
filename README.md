# 人工智能信息隐藏基准测试平台

`ai-stego-benchmark` 是一个信息隐藏与网络空间安全方向的可运行开源项目，包含核心算法代码、命令行入口、实验配置、示例脚本和 smoke tests。

## Overview

本项目面向人工智能信息隐藏算法构建统一基准测试平台，提供数据管理、算法注册、批量实验、指标计算和报告生成等功能。平台支持图像、音频、文本等多模态载体，可统一评估嵌入容量、载体失真、提取准确率、抗压缩能力和隐写分析检测率。项目采用配置文件驱动实验流程，便于课题组把不同学生开发的模型纳入同一评测框架，形成可复用、可比较、可追踪的实验结果，并支持导出 Markdown 和表格化实验摘要。

## Features

- 统一的数据加载、实验配置和结果保存流程
- 面向信息隐藏/数字水印/隐写分析任务的模块化设计
- 支持实验指标输出、样例结果归档和后续算法扩展
- 适合课程实验、毕业设计、论文复现实验和课题组日常开发

## Quick Start

```bash
python examples/demo.py
python -m unittest discover -s tests
python -m ai_stego_benchmark.cli --message "demo payload" --report docs/cli_report.md
```

## Keywords

benchmark · AI steganography · multimodal · evaluation

## Authors

- 负责人：林裕斌
- 参与人：曾科、田承金
- 指导教师：吕善翔
- 单位：暨南大学网络空间安全学院

## License

本项目采用 MIT License 开源。Copyright (c) 2026 Lin Yubin, Zeng Ke, Tian Chengjin, Shanxiang Lv, Jinan University.
