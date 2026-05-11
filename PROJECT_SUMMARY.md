# 人工智能信息隐藏基准测试平台

英文名称：`ai-stego-benchmark`

开源地址：`https://github.com/Buzzbbb/ai-stego-benchmark`

项目时间：2024年11月-至今

## 作者信息

- 负责人：林裕斌，专业：网络空间安全，硕士生
- 参与人：曾科，专业：网络空间安全，硕士生
- 参与人：田承金，专业：网络空间安全，硕士生
- 指导教师：吕善翔，网络空间安全学院教师

## 项目内容

本项目面向人工智能信息隐藏算法构建统一基准测试平台，提供数据管理、算法注册、批量实验、指标计算和报告生成等功能。平台支持图像、音频、文本等多模态载体，可统一评估嵌入容量、载体失真、提取准确率、抗压缩能力和隐写分析检测率。项目采用配置文件驱动实验流程，便于课题组把不同学生开发的模型纳入同一评测框架，形成可复用、可比较、可追踪的实验结果，并支持导出 Markdown 和表格化实验摘要。

## 影响力

项目开源后可作为课题组多模态信息隐藏实验的公共评测底座，为论文实验、课程作业和横向项目原型提供统一的算法比较与结果归档方式。

## 开发语言

Python

## 代码规模

1012行（按当前项目 src/tests/examples 下 Python 代码统计）

## 建议仓库结构

```text
ai-stego-benchmark/
├── README.md
├── LICENSE
├── PROJECT_SUMMARY.md
├── src/
├── examples/
├── tests/
├── docs/
└── screenshots/
```

## 截图材料

- 项目目录截图：`screenshots/directory.png`
- 项目说明截图：`screenshots/readme.png`
- 项目声明截图：`screenshots/license.png`

## 关键词

benchmark, AI steganography, multimodal, evaluation
