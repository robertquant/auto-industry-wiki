---
title: QNX Hypervisor
created: 2026-04-30
updated: 2026-11-07
type: concept
tags: [technology, cockpit, adas]
sources: [memory/2026-04-30.md, daily-news/2026-11-07-gasgoo-evening.md]
---

# QNX Hypervisor

## 概述
黑莓（BlackBerry）开发的Type 1虚拟化方案，汽车行业座舱+智驾融合的主流选择。

## 技术架构
- **基础**：QNX Neutrino RTOS作为Type 1 Hypervisor
- **功能**：单芯片上创建多个隔离的虚拟机（VM）
- **典型配置**：QNX（智驾）+ Android（座舱）或 Linux（智驾）

## 2026-11-07 更新：法雷奥前视摄像头平台集成 QNX OS for Safety
- **[[valeo]] 新一代前视摄像头平台集成 QNX OS for Safety**（进博会 11/6）：支持车辆/行人/标线/交通标识检测，**已获多家中国车企定点**、2026 年内投产——QNX 从座舱虚拟化（Android+Linux 共存）延伸到**前视摄像头功能安全域**
- 判断：QNX 的「Type 1 Hypervisor + 功能安全 OS」双产品线，正把座舱统治力复制到智驾传感器域（对照 [[cockpit-chip]]、[[iso-26262]] 功能安全要求）

## 核心优势

| 特性 | 说明 |
|------|------|
| ASIL-D认证 | 原生支持最高功能安全等级 |
| 实时性 | 微内核架构，中断响应<1μs |
| 硬件隔离 | 内存、外设、CPU核心严格切分 |
| 故障隔离 | 一个VM崩溃不影响其他VM |

## 已量产案例
- 沃尔沃EX90（高通8295+QNX Hypervisor）
- 蔚来NT3.0平台部分车型
- 凯迪拉克锐歌（Ultifi平台）

## 主流Hypervisor对比

| 方案 | 厂商 | 安全认证 | 特点 |
|------|------|----------|------|
| QNX Hypervisor | 黑莓 | ASIL-D | 汽车行业标准，主流 |
| INTEGRITY | Green Hills | 安全认证强 | 军工背景，少量高端 |
| PikeOS | SYSGO | 欧洲认证 | 欧洲OEM |
| ACRN | Intel开源 | 认证弱 | 免费，成本敏感方案 |
| 英伟达/高通方案 | 芯片厂商 | 配套认证 | 自家芯片专用 |

## 商业化问题

| 问题 | 说明 |
|------|------|
| 许可费贵 | 按芯片数收费 |
| 授权流程复杂 | 中小玩家难以承受 |
| 黑莓战略摇摆 | 汽车业务多次传出出售传闻 |

## 替代趋势
- 英伟达推自有虚拟化方案，与QNX解耦
- 高通在8775上推自有Hypervisor
- 中国车企倾向本土方案：华为鸿蒙虚拟化、阿里AliOS

## 2026年格局

| 阵营 | Hypervisor选择 |
|------|----------------|
| 特斯拉 | 自研，不需要QNX |
| 英伟达Thor系 | 英伟达虚拟化 + QNX/Android |
| 高通8775系 | 高通方案 + QNX/Android |
| 华为系 | 鸿蒙虚拟化 |
| 低成本方案 | ACRN/PikeOS |

## 判断
QNX现在还是主流，但"成熟"的另一面是"垄断溢价"。芯片厂商正在推自家方案稀释QNX份额。

## 关系网络
- [[舱驾融合]] - 应用场景
- [[黑莓]] - 开发商
- [[英伟达Thor]] - 竞品方案
- [[高通8775]] - 竞品方案
- [[华为鸿蒙]] - 中国替代方案