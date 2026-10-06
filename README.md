# FracLogGPT-Reproduction

《软件工程实践》课程论文复现项目。

## 复现论文

- **题目**：FracLogGPT: A Multimodal Large Language Model for Fracture Interpretation in Imaging Logging
- **期刊**：Electronics（MDPI），2026, 15(1): 127
- **DOI**：10.3390/electronics15010127（开放获取，CC BY）
- **作者**：Hushuang Shen、Ang Li（通讯作者）、Liyan Zhang、Xiangxiang Liu（中国石油大学（北京）克拉玛依校区）
- **官方代码**：https://github.com/Darssal/FracLogGPT-Lite

## 复现目标

| 指标 | 论文报告值 | 复现目标值 |
|---|---|---|
| Count-F1（独立测试集 160 张切片） | 0.70（基座模型约 0.42） | ≥ 0.63 |
| BLEU / ROUGE | 均优于未经领域适配的 Qwen2-VL-72B | 达到同趋势结论 |

## 技术路线

以学习理解为主，基于官方开源仓库跑通全流程：环境搭建与数据获取 → 按官方流程训练 / 加载权重 → 独立测试集评测（Count-F1、BLEU/ROUGE）→ 结果对比分析。

## 进度

- [x] 开题任务书（2026-10-06）
- [ ] 环境搭建与数据获取（2026.10.13 – 10.22）
- [ ] 跑通官方训练与推理流程（2026.10.23 – 11.03）
- [ ] 原数据集复现实验，对齐论文结果（2026.11.04 – 11.14）
- [ ] 轻量扩展：少量新图像泛化测试（可选，2026.11.15 – 11.23）
- [ ] 整理代码与结果，撰写报告，准备答辩（2026.11.24 – 12.01）

## 参考文献

[1] Shen H, Li A, Zhang L, et al. FracLogGPT: A Multimodal Large Language Model for Fracture Interpretation in Imaging Logging[J]. Electronics, 2026, 15(1): 127.
