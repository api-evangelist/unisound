---
title: "面向情感计算的双分支 Transformer：通过安全注意力机制与 Focal Loss 应对模态缺失和数据不平衡"
url: "https://www.unisound.com/research/150"
date: "2026-06-03"
feed_url: "https://www.unisound.com/rss.xml"
---
现实环境中的情绪识别常受到局部遮挡、模态缺失以及严重类别不平衡等问题影响。针对这些挑战，尤其是面向野外情感行为分析（ABAW）Expression 挑战赛，我们提出了一种可动态融合视觉与音频表征的多模态框架。 该方法采用双分支 Transformer 架构，并引入安全交叉注意力机制（Safe Cross-Attention）和模态丢弃（Modality Dropout）策略，使模型在视觉信息缺失时仍可依赖音频信息进行预测。针对 Aff-Wild2 数据集中的长尾分布问题，我们采用 Focal Loss 进行优化，并结合滑动窗口软投票策略，以捕捉动态情绪变化并减少帧级分类抖动。 实验结果表明，该框架能够有效应对模态缺失和复杂时空依赖问题，并最终获得第十届 ABAW Expression 挑战赛第三名。
