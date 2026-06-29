# Wiki Schema

## Domain
新能源汽车行业知识库 — 涵盖三电技术、智能驾驶、智能座舱、供应链、车企战略、政策法规。

## Conventions
- 文件名：小写字母、连字符分隔、无空格（如 `byd.md`、`solid-state-battery.md`）
- 每个页面必须有 YAML frontmatter（见下方）
- 使用 `[[wikilinks]]` 链接相关页面（每页至少 2 个出站链接）
- 更新页面时必须更新 `updated` 日期
- 新建页面必须添加到 `index.md` 对应分类下
- 每次操作必须追加到 `log.md`

## Frontmatter
```yaml
---
title: 页面标题
created: YYYY-MM-DD
updated: YYYY-MM-DD
type: entity | concept | comparison | query | summary
tags: [来自下方分类]
sources: [raw/articles/source-name.md]
---
```

## Tag Taxonomy

### 车企与组织
- `carmaker`: 整车厂（比亚迪、特斯拉、蔚来等）
- `supplier`: 供应商（宁德时代、地平线等）
- `startup`: 新势力造车
- `consortium`: 行业联盟、协会

### 技术领域
- `battery`: 动力电池、储能
- `motor`: 电机、电驱
- `platform`: 平台架构、电子电气架构
- `adas`: 高级驾驶辅助、自动驾驶
- `cockpit`: 智能座舱、HMI
- `semiconductor`: 车规芯片、功率器件
- `software`: 软件定义汽车、OS、中间件

### 人物
- `ceo`: 企业家、高管
- `engineer`: 技术专家
- `investor`: 投资人

### 产品与车型
- `model`: 具体车型
- `product`: 产品线、子品牌

### 市场与商业
- `market`: 市场分析、销量数据
- `policy`: 政策法规、补贴、标准
- `investment`: 融资、并购
- `supply-chain`: 供应链动态

### 技术概念
- `concept`: 技术概念、方法论
- `trend`: 行业趋势
- `comparison`: 对比分析

### 元数据
- `news`: 新闻资讯
- `research`: 深度研究

## Page Thresholds
- **创建页面**：当实体/概念出现在 2+ 来源，或在单一来源中为核心主题
- **添加到现有页面**：当来源提及已覆盖的内容
- **不创建页面**：仅提及、次要细节、超出领域范围的内容
- **拆分页面**：当页面超过 ~200 行 — 拆分为子主题并交叉链接
- **归档页面**：当内容完全过时 — 移动到 `_archive/`，从 index 移除

## Entity Pages
每个实体一页。包含：
- 概述 / 是什么
- 关键事实和日期
- 与其他实体的关系（[[wikilinks]]）
- 来源引用

## Concept Pages
每个概念/话题一页。包含：
- 定义/解释
- 当前知识状态
- 开放问题或争议
- 相关概念（[[wikilinks]]）

## Comparison Pages
对比分析。包含：
- 对比对象及原因
- 对比维度（表格格式优先）
- 结论或综合
- 来源

## Update Policy
当新信息与现有内容冲突时：
1. 检查日期 — 新来源通常覆盖旧来源
2. 如确有矛盾，标注两个位置并附日期和来源
3. 在 frontmatter 标记矛盾：`contradictions: [page-name]`
4. 在 lint 报告中标记供用户审核