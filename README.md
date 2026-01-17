# Happy-LLM 学习笔记仓库（个人签名-无名C）

本仓库用于记录《Happy-LLM：从零开始的大语言模型原理与实践教程》的学习过程、笔记整理与代码复现，旨在系统掌握 LLM 核心原理与实战技能。

## 项目简介
《Happy-LLM》是 Datawhale 开源的 LLM 学习教程，涵盖 NLP 基础、Transformer 架构、预训练模型、LLM 训练全流程及前沿应用（RAG、Agent），支持从理论到实战的完整学习路径。

## 学习进度表
| 章节 | 核心内容 | 学习状态 | 笔记/代码链接 |
|------|----------|----------|---------------|
| 前言 | 项目缘起、背景及学习建议 | ✅ 已完成 | [前言笔记](docs/task1-2.md) |
| 第一章 | NLP 基础概念（发展历程、任务分类、文本表示演进） | ✅ 已完成 | [NLP基础笔记](docs/task1-2.md) |
| 第二章 | Transformer 架构（注意力机制、Encoder-Decoder、手动搭建） | ⏳ 进行中 | [Transformer架构笔记](docs/task3-5.md) |
| 第三章 | 预训练语言模型（Encoder-only/Decoder-only 等架构对比） | ☐ 未开始 | - |
| 第四章 | 大语言模型（LLM 定义、训练策略、涌现能力） | ☐ 未开始 | - |
| 第五章 | 动手搭建大模型（实现 LLaMA2、训练 Tokenizer、预训练小型 LLM） | ☐ 未开始 | - |
| 第六章 | 大模型训练实践（预训练、SFT、LoRA/QLoRA 高效微调） | ☐ 未开始 | - |
| 第七章 | 大模型应用（模型评测、RAG、Agent 智能体） | ☐ 未开始 | - |

## 学习资源
- 教程 PDF 下载：[GitHub 地址](https://github.com/datawhalechina/happy-llm/releases/tag/PDF) | [国内镜像](https://www.datawhale.cn/learn/summary/179)
- 模型下载：[ModelScope](https://www.modelscope.cn/)（Happy-LLM-Chapter5-Base-215M / SFT-215M）
- 官方仓库：[datawhalechina/happy-llm](https://github.com/datawhalechina/happy-llm)

## 学习计划
1. 基础阶段（第 1-4 章）：掌握 NLP 核心概念、Transformer 原理、PLM 与 LLM 核心逻辑
2. 实战阶段（第 5-6 章）：复现 LLaMA2 搭建、完成预训练与微调全流程
3. 应用阶段（第 7 章）：实践 RAG 检索增强、Agent 智能体开发
4. 拓展阶段：结合教程代码，尝试二次开发与模型优化

## 仓库结构(预期)
```
happy-llm-learning/
├── docs/          # 章节学习笔记
├── code/          # 教程代码复现（含自定义实现与框架调用）
│   ├── transformer/  # 第二章 Transformer 手动实现
│   ├── llama2/       # 第五章 LLaMA2 搭建代码
│   └── applications/ # 第七章 RAG/Agent 实践
├── data/          # 训练所需数据集（含预处理脚本）
└── README.md      # 学习进度与项目说明
```

## 备注
- 学习过程将重点关注「原理拆解」与「代码复现」，每章笔记包含核心知识点、关键公式推导及问题记录
- 代码将基于 PyTorch + Transformers 框架实现，兼容教程原生代码与最新版本适配
