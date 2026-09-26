---
title: 芯驰X10 (Xinchi X10)
created: 2026-09-26
updated: 2026-09-26
type: entity
tags: [chip, cockpit, ai, tier1]
sources: [raw/articles/2026-09-26-daily-digest.md]
---

# 芯驰X10 (Xinchi X10)

## 概述
芯驰科技（SemiDrive）2026-09-15 发布的 **4nm 车规级**座舱/端侧 AI 芯片 X10，定位「单芯片支持 **9B 端侧大模型**」。是[[cockpit-model-tiering]]（座舱模型分层）趋势下，国产车规芯片向端侧大模型推理下探的代表产品。

## 核心规格

| 参数 | 数值 |
|------|------|
| 制程 | 4nm 车规级 |
| 算力 | 80 TOPS |
| 内存带宽 | 154 GB/s |
| 端侧大模型 | 单芯片支持 **9B** 参数 |
| 发布 | 2026-09-15 |

## 战略意义

- **端侧大模型的关键瓶颈是内存带宽**：154 GB/s 的带宽指标正是为端侧 LLM 推理（memory-bound）设计，比算力数字更能说明产品取向。
- **与「端侧 3B 以内 + 端云协同」趋势对齐**：2026 行业把常驻车端模型压到 3B 以内，X10 的 9B 上限给了车企更大的常驻层空间，参见 [[cockpit-model-tiering]]。
- **国产车规 SoC 补位**：在[[qualcomm-auto]]（8797/8787/8775）与[[horizon-robotics]]（星空 6）之外，提供座舱侧的国产替代选项。

## 关系网络
- [[cockpit-model-tiering]] - 端侧大模型分层部署
- [[qualcomm-auto]] - 座舱芯片主要竞争者
- [[horizon-robotics]] - 舱驾融合竞品（X10 偏座舱）
- [[advanced-node-capacity-2027]] - 4nm 先进制程产能约束
- [[cockpit-chip]] - 座舱芯片市场格局

## 待观察
- 9B 端侧大模型的实际可用性与时延
- 首批定点车企与量产节奏
- 与高通 8295/8787 在座舱侧的成本竞争
