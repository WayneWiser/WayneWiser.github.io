---
title: "预训练模型高效迁移给下游任务"
collection: teaching
type: "Research"
permalink: /teaching/2022-xiaomi-2
venue: "Xiaomi, AI lab"
date: 2022-04-01
location: "City, Country"
---

和小米首席语音科学家Daniel Povey合作，重新定义知识蒸馏问题为一个编解码问题，将大规模预训练模型的能力迁移到下游ASR模型。相比于传统蒸馏方式快至少4.5倍（或者存储空间节省640倍），性能相对提升11.12%。

成果丰富
======
Interspeech 2022 已投
L. Guo, Q. Wang, Y. Kong, Z. Yao, Y. Huang, F. Cui, F. Kuang, W. Kang, L. Lin, M. Luo, D. Povey, "Predicting Multi-Codebook Vector Quantization Indexes for Knowledge Distillation", submmited to Interspeech 2022.

算法创新
======
提出Multi-codebook vector quantization，将浮点数向量压缩成一个codebook index 序列，每个codebook只占用一个8bit的字节。蒸馏过程中提出联合codebook loss，能够显示地利用codebook index之间的相关性。

效果惊艳
======
相比于传统的teacher-student框架，训练速度提升4.5倍，或者存储空间节省640倍，性能相对提升11.12%。
