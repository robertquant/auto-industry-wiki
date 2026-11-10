---
title: 芯驰X10 (Xinchi X10)
created: 2026-09-26
updated: 2026-11-10
type: entity
tags: [chip, cockpit, ai, tier1]
sources: [raw/articles/2026-09-26-daily-digest.md, daily-news/2026-11-10-gasgoo-evening.md]
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

## 2026-11-10 更新：前三季装机 35.3 万颗居本土第一 + 「座舱 SoC+AI Box」替代者定位（盖世 11/10）
- **市占数据**：2026 前三季度芯驰车机芯片在国内 10 万-30 万元市场装机 **35.3 万颗，居本土供应商第一**
- **X10 新卖点**：单芯片替代「座舱 SoC + 外挂 AI Box」——**省约 25% DDR 容量、BOM 降 1500-3000 元**（4nm/80 TOPS/154GB/s/9B 端侧规格页首已录）
- 判断：「单芯替代双盒」直击 [[ai-box-independent-compute]] 的形态之争——独立 AI 盒子的内存带宽隔离价值正被高带宽座舱 SoC 吸收；35.3 万颗 = 国产座舱芯片在 10-30 万价格带的份额底座（[[cockpit-chip]]），但 9B 端侧实际体验仍是量产验证点（对照 [[qualcomm-auto]] 8295 生态位）
