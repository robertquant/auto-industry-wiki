---
title: 底盘域控 (Chassis Domain Control)
created: 2026-10-06
updated: 2026-10-06
type: concept
tags: [ev-tech, trend, system]
sources: [raw/articles/2026-10-06-daily-digest.md]
---

# 底盘域控 (Chassis Domain Control)

## 定义
把传统分散的底盘电子控制（制动/转向/悬架/驱动/车身稳定）收敛到单一域控制器，配合线控执行器（线控转向、线控制动、主动悬架）实现整车级运动协同控制。是 L3/L4 时代的刚需——智驾决策需要底盘毫秒级可执行、冗余可兜底（见 [[l3-autonomous-driving]]）。

## 2026-10 更新：智驾战外溢到底盘——「底盘域控三强」
- 竞争格局：**华为 / 蔚来 / 岚图** 三家率先把底盘域控做成独立卖点与技术叙事
- 逻辑：智驾（[[vla-model]]、[[world-model]]）同质化后，车企需要新的体验差异化抓手——「智驾+底盘」协同控制（华为途灵底盘、蔚来天行底盘等）成为分层竞争新战场
- 触发点：[[tesla]] Cybercab（无方向盘/线控底盘）把「线控」从概念推向量产，激活全行业底盘域控军备（对照 [[2026-paris-auto-show]] 特斯拉参展）
- 规律：与 [[cabin-drive-integration]]（舱驾融合）同构——从「多域分离」走向「单域融合」，驱动力都是降本+性能冗余

## 当前状态与争议
- 线控转向（SBW）法规与可靠性仍是最大门槛，主流方案仍是「域控+电控冗余/液压冗余」混合
- 成本：全线控方案较传统底盘成本高 30%+，2026 年仍集中在 30 万+车型
- 开放问题：底盘域控的「安全认证」归谁（车企自证 vs 第三方）；与 [[iso-26262]]/功能安全体系如何衔接

## 相关概念
- [[cabin-drive-integration]] - 舱驾融合，同构的「单域融合」趋势
- [[li-l9-livis-tech]] - 理想 L9 Livis：线控底盘+800V 主动悬架量产标杆
- [[driving-tech-fusion-paradigm]] - 智驾技术路线收敛背景
- [[tesla]] - Cybercab 无方向盘点燃线控需求