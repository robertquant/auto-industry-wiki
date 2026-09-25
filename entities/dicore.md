---
title: DiCore (比亚迪座舱OS中间件)
created: 2026-09-25
updated: 2026-09-25
type: entity
tags: [system, cockpit, sw, oem-cn]
sources: [raw/articles/2026-09-25-daily-digest.md]
---

# DiCore (比亚迪座舱OS中间件)

## 概述
比亚迪自建的**座舱 OS 中间件**，是 [[di-di-xia]] 超级智能体向下控制车辆的执行层。核心价值：让上层 AI Agent 直接调用 CAN FD 总线、V2X、AR-HUD、座椅按摩 ECU 等整车功能。

## 为什么它是"真壁垒"
- 需要**整车总线控制权**（CAN FD / 车载以太网）——外部软件公司拿不到
- 需要 **ECU 级集成**——要打通座舱域与车控域
- 需要**功能安全**（[[iso-26262]]）——AI 建议须能确定性、可回滚地执行
- 结论：只有主机厂能做，是**主机厂独占**的中等强度壁垒

## 与迪迪虾的分工
| 层 | 组件 | 壁垒 |
|----|------|------|
| 上层 Agent | [[di-di-xia]]（通义千问+阿里生态） | 零壁垒（模型/协议公开） |
| 下层中间件 | **DiCore** | 中等（主机厂独占） |
| 底座架构 | 璇玑架构 2.0（舱驾电一体） | 强 |

## 战略含义
- 比亚迪的护城河不在"迪迪虾 Agent"，而在 **DiCore** 这类向下打通车控的中间件
- 印证 [[cockpit-ai-barrier-layering]]：功能层公开战场，约束层才是护城河
- 对标其他主机厂的舱驾融合底座（[[cabin-drive-integration]]、[[qnx-hypervisor]]）

## 关系网络
- [[byd]] - 母公司
- [[di-di-xia]] - 上层超级智能体
- [[cockpit-ai-barrier-layering]] - 所属壁垒框架
- [[cabin-drive-integration]] - 舱驾融合底座对照
- [[iso-26262]] - 功能安全基础

## 待观察
- DiCore 是否对外开放（第三方车企/供应商接入）
- 与华为乾崑 OS、地平线咖咖虾 OS 的生态竞争
- 璇玑架构 2.0 舱驾电一体的量产落地节奏
