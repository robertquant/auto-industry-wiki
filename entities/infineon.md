---
title: 英飞凌 (Infineon)
created: 2026-10-21
updated: 2026-11-07
type: entity
tags: [chip, tier1, supply-chain, oem-eu]
sources: [raw/articles/2026-10-21-daily-digest.md, concepts/risc-v-automotive.md, concepts/power-module-market-2026.md, daily-news/2026-10-25-gasgoo-evening.md, daily-news/2026-11-06-gasgoo-evening.md, daily-news/2026-11-07-gasgoo-evening.md]
---

# 英飞凌 (Infineon)

德国车规半导体龙头，全球汽车 MCU（AURIX 系列）与功率半导体（IGBT/SiC）核心供应商。中国功率模块市场与中车时代并列第二（各10.3%，2026年1-7月，见 [[power-module-market-2026]]）；下一代汽车 MCU 采用 RISC-V 架构（见 [[risc-v-automotive]]）。

## 2026-10-21 更新：×大众 CARIAD/VCTC 合肥创新应用中心挂牌

- **英飞凌×大众 [[volkswagen]] CARIAD/VCTC 合肥创新应用中心**正式挂牌
- 核心逻辑：**芯片需求定义前移**——英飞凌工程师嵌入大众中国研发体系，AURIX MCU + 车规功率模块直接适配 CEA 电子电气架构（[[volkswagen]] CEA）
- 意义：传统「芯片厂-车企」买卖关系 → 联合定义关系；外资 Tier1/芯片厂绑定中国合资研发体系的又一例

**判断**：英飞凌在合肥与「CARIAD中国+VCTC」双研发中心绑定 = 欧洲芯片巨头对「中国定义、全球输出」（对照 [[mercedes-benz]] 战略）的直接下注。与 [[xinhe-hangtu]]（雷诺/奇瑞投中国芯片）互为镜像：欧洲巨头两头下注——既投中国本土芯片，也把自家芯片嵌入中国研发链。

## 2026-11-07 更新：首个 RISC-V 车规 MCU 系列 AURIX RC1
- **发布首个基于 RISC-V 架构的车规 MCU 系列 AURIX RC1**（11/6）——打破车规 MCU 长期绑定专有内核格局，为下一代电子电气架构提供开放生态选项（[[risc-v-automotive]]）
- 与 11/6「×高通共同开发中央车载计算机」呼应：AURIX MCU 存量（专有内核）+ RC1（RISC-V 增量）+ 高通 SoC 捆绑——英飞凌「双架构并行 + 捆绑外援」策略进入产品落地期
- 判断：AURIX 是车规 MCU 事实标准，RC1 若放量 = RISC-V 车规化从「边缘切入」进入「主流替换」临界（[[storage-chip-surge-2026]] 背景下开放架构/国产替代双叙事）

## 相关页面
- [[volkswagen]] - 大众 CEA 架构与合肥 VCTC
- [[risc-v-automotive]] - RISC-V 车规化（英飞凌下一代 MCU）
- [[power-module-market-2026]] - 功率模块装机份额
- [[xinhe-hangtu]] - 欧洲OEM资本绑定中国芯片样本

## 来源
- raw/articles/2026-10-21-daily-digest.md
- concepts/risc-v-automotive.md
- concepts/power-module-market-2026.md

## 2026-10-25 更新：× Wolfspeed 200mm SiC 多年期供货协议
- **与 Wolfspeed 签署 200mm SiC 晶圆多年期供货协议**：供货关系由 150mm 衬底转向 200mm，直接支撑英飞凌 200mm 碳化硅大规模制造转型——**马来西亚居林工厂剑指全球最大 SiC 基地**（电动车、光伏与 AI 数据中心需求交汇，单位衬底成本曲线是下一轮竞争焦点）
- 判断：SiC 衬底代际切换（150→200mm）与 IGBT 国产化（[[power-module-market-2026]] 比亚迪半导体 19.2% 登顶）同步发生——英飞凌用「大尺寸衬底锁定」对冲中国功率模块份额追赶；200mm 产能爬坡速度决定 2027-28 SiC 价格战走向

## 2026-11-06 更新：×高通共同开发中央车载计算机（盖世芯片快讯 11/6）
- **与高通合作开发中央车载计算机**——典型分工：英飞凌 AURIX MCU（功能安全/实时控制）+ 高通 SoC（AI 算力）——中央计算+区域控制（[[cabin-driving-fusion]]）架构下的标准卡位组合
- 判断：芯片厂在给 2027-28 中央计算节点（[[courizon]] CEA 2027 中央计算/L3 已录）提前锁定「MCU+SoC」捆绑方案；与 RISC-V 下一代 MCU（[[risc-v-automotive]]）并行——英飞凌同时押注「高通绑定」与「RISC-V 自主」两条线，对冲架构风险（[[qualcomm-auto]]）