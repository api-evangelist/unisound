---
title: "GuideTree：面向长篇医疗记录的指南引导式审阅树"
url: "https://www.unisound.com/research/144"
date: "2026-07-07"
feed_url: "https://www.unisound.com/rss.xml"
---
阅读顺序检测是文档理解的基础。现有方法大多采用统一监督，默认不同版面区域的学习难度基本一致。本文指出这一假设存在明显缺陷，并发现一种“位置差异（Positional Disparity）”现象：模型在相对确定的起始和结束区域表现良好，但在结构复杂的中间区域性能明显下降。这是因为大量简单样本会淹没复杂版面中的有效学习信号。 为解决这一问题，本文提出基于**焦点偏好优化（Focal Preference Optimization，FPO）**的 FocalOrder 框架。该方法利用指数移动平均机制动态识别难学习的阅读顺序转换，并通过难度校准的成对排序目标增强全局逻辑一致性。 大量实验表明，FocalOrder 在 OmniDocBench v1.0 和 Comp-HRDoc 上取得了新的 SOTA 性能。其轻量级模型不仅优于多种专用基线，还显著超过大规模通用视觉语言模型，证明针对文档自身结构歧义进行优化，是准确理解复杂文档结构的关键。
