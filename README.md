# 基于BERT的招聘文本薪资预测（2025年大学生统计建模大赛）

本项目为“2025 年大学生统计建模大赛”参赛作品，围绕招聘文本进行薪资区间预测。核心流程包括数据爬取、数据分析、特征处理与基于 BERT 的建模训练。

## 项目内容

- `boss-zhipin-spider.ipynb`：招聘信息采集与数据初步整理。
- `boss-zhipin-data-analysis.ipynb`：数据探索性分析与可视化。
- `boss-zhipin-data-modeling-train.ipynb`：BERT 模型训练与薪资预测实验。

## 数据集

- 数据来源（Kaggle）：https://www.kaggle.com/datasets/jeanshendev/boss-zhipin-sample-data

## 使用说明

1. 安装依赖（按需）：
   - Python 3.8+、Jupyter Notebook
   - 相关数据处理与深度学习库（如 pandas、numpy、scikit-learn、transformers、torch 等）
2. 按顺序运行 Notebook：
   - `boss-zhipin-spider.ipynb` → `boss-zhipin-data-analysis.ipynb` → `boss-zhipin-data-modeling-train.ipynb`

## 备注

- 模型与数据处理细节请参考各 Notebook 中的注释与结果输出。
- 若需复现实验，请根据环境与硬件条件调整参数设置。
