# Wiki Schema

## Domain
新能源汽车行业知识库 — 覆盖车企动态、三电技术、智能驾驶、供应链、市场格局、政策法规。服务于汽车行业深度分析与决策。

## Conventions
- 文件名：小写字母+连字符，无空格（如 `byd.md`、`world-model.md`）
- 每个页面必须有 YAML frontmatter（见下方模板）
- 使用 `[[wikilinks]]` 链接相关页面（每页至少2个出站链接）
- 更新页面时必须更新 `updated` 日期
- 新建页面必须添加到 `index.md` 对应分类下
- 所有操作必须追加到 `log.md`

## Frontmatter
```yaml
---
title: 页面标题
created: YYYY-MM-DD
updated: YYYY-MM-DD
type: entity | concept | comparison | query
tags: [来自下方标签分类]
sources: [raw/articles/来源文件.md]
---
```

## Tag Taxonomy

### 车企 (Companies)
- oem-cn: 中国自主品牌
- oem-eu: 欧洲车企
- oem-us: 美国车企
- oem-jp: 日本车企
- tier1: 一级供应商
- chip: 芯片厂商
- battery: 电池厂商

### 产品 (Products)
- vehicle: 车型
- platform: 平台架构
- chip: 芯片产品
- battery: 电池产品
- system: 系统/解决方案

### 人物 (People)
- ceo: CEO/创始人
- executive: 高管
- engineer: 技术专家

### 技术 (Technology)
- ev-tech: 电动化技术
- battery-tech: 电池技术
- adas: 智能驾驶
- cockpit: 智能座舱
- ai: AI技术
- sw: 软件架构

### 市场 (Market)
- sales: 销量数据
- pricing: 价格策略
- export: 出口/国际化
- policy: 政策法规

### 概念 (Concepts)
- strategy: 战略分析
- trend: 行业趋势
- ecosystem: 生态布局
- supply-chain: 供应链

### 元数据 (Meta)
- comparison: 对比分析
- timeline: 时间线
- controversy: 争议事件
- prediction: 预测判断

## Page Thresholds
- **创建页面**：实体/概念在2+来源中出现，或单一来源的核心主题
- **更新页面**：新来源提及已有页面的内容
- **不创建页面**：仅作为案例/数据点提及的实体，或领域外的内容
- **拆分页面**：页面超过200行时，拆分为子主题并交叉链接
- **归档页面**：内容完全过时被取代时，移至 `_archive/`，从 index 移除

## Entity Pages
每个实体一个页面，包含：
- 概述/是什么
- 关键事实与时间线
- 与其他实体的关系（[[wikilinks]]）
- 来源引用

## Concept Pages
每个概念/主题一个页面，包含：
- 定义/解释
- 当前认知状态
- 开放问题或争议
- 相关概念（[[wikilinks]]）

## Comparison Pages
对比分析页面，包含：
- 对比对象及目的
- 对比维度（表格形式优先）
- 结论或综合判断
- 来源

## Update Policy
当新信息与已有内容冲突时：
1. 检查日期 — 新来源一般取代旧来源
2. 如确实矛盾，同时标注两个观点并附日期和来源
3. 在 frontmatter 标记：`contradictions: [页面名]`
4. 在 lint 报告中标记供用户审核