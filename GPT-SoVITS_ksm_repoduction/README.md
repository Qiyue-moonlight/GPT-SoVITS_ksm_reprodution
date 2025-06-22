# 基于GPT-SoVITS的AI音色克隆算法复现与评估

## 项目概述

本项目复现并评估了GPT-SoVITS音色克隆算法，这是一种结合生成式预训练变换器(GPT)与变分推断语音合成(SoVITS)的先进语音合成技术。项目重点验证了该算法在少样本学习和跨语言语音合成方面的性能表现。

## 项目结构

GPT-SoVITS_ksm_reproduction
├── GPT-SoVITS-main/      # 主程序
│   ├── tools/           # 实验所需工具
│   └── ....../          			
├── Local_Data/                  # 本地数据
│   ├── GPT_models/          # GPT模型
│   └── SoVITS_models/     # SoVITS模型
├── workplace/               		# 工作区
│   ├── ColorSplitter  		# 音色分类工具
│   └── KiraKsm-main       # 音频爬取工具
├── kasumi                 	  # 数据集音频文件
└── README.md                # 项目说明

## 主要特性

- 复现了最新的GPT-SoVITS音色克隆算法
- 支持中英文跨语言语音合成
- 实现少样本(最低5秒)音色克隆
- 包含完整的训练和推理流程
- 提供性能评估指标计算