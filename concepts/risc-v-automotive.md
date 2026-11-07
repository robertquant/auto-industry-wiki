---
title: RISC-V 车规化
created: 2026-10-08
updated: 2026-11-07
type: concept
tags: [chip, trend, supply-chain]
sources: [raw/articles/2026-10-08-daily-digest.md, daily-news/2026-11-07-gasgoo-evening.md]
---

# RISC-V 车规化

RISC-V 开放指令集架构在汽车芯片领域的规模化应用进程。2026-10 提速信号：英飞凌透露下一代汽车 MCU 将采用 RISC-V 开放架构，国产车规芯片生态补链加速。

## 定义与现状

- RISC-V：开源指令集架构（ISA），免授权费、可自由扩展——区别于 ARM（授权模式）与 x86（封闭）
- 车规级切入点首先是 **MCU**（英飞凌/瑞萨/恩智浦传统地盘），再向 SoC 延伸
- 中国推动力：规避 ARM/US 授权风险 + 自主可控政策导向（[[auto-chip-self-develop]]）

## 2026-10-09 更新：紫荆半导体车规 RISC-V 破千万颗
- **紫荆半导体 RISC-V 车规芯片累计出货破 1,000 万颗**（盖世）——国产车规 RISC-V 首次进入千万级规模，从「补链叙事」进入「出货验证」
- 结合英飞凌下一代 MCU 采用 RISC-V：国外巨头跟进 + 国产规模化，双线验证 RISC-V 车规化从边缘切入走向主流（对照 [[storage-chip-surge-2026]] 供应链背景）

## 2026-11-07 更新：英飞凌 AURIX RC1——首个 RISC-V 车规 MCU 系列
- **[[infineon]] 发布 AURIX RC1**（11/6）：首个基于 RISC-V 架构的车规 MCU 系列，打破车规 MCU 长期绑定专有内核的格局——从「透露下一代采用 RISC-V」（10/8 已录）到**产品发布落地**
- 判断：RISC-V 车规化完成「工具链/功能安全认证可行性」验证，进入产品化阶段；国产（[[auto-chip-self-develop]] 紫荆破千万颗）+ 国际（英飞凌）双线并进，[[storage-chip-surge-2026]] 背景下的开放架构叙事再获主流背书

## 开放问题

- RISC-V 生态（工具链/中间件/功能安全认证）成熟度 vs ARM 的 20 年积累
- 车规认证周期（ISO 26262，见 [[iso-26262]]）是首批量产落地的主要时间门槛
- 英飞凌等传统 MCU 巨头「双架构并行」（ARM 存量 + RISC-V 增量）策略能否真正放量

## 相关概念

- [[auto-chip-self-develop]] - 车企自研芯片趋势
- [[autonomous-driving-chips]] - 智驾芯片格局
- [[advanced-node-capacity-2027]] - 制程产能约束
- [[storage-chip-surge-2026]] - 芯片供应链压力背景

## 待观察

- 英飞凌 RISC-V MCU 首发量产时间表
- 国产车规 RISC-V 芯片（芯来/赛昉等）上车进度
- RISC-V 是否从 MCU 向智驾 SoC 渗透