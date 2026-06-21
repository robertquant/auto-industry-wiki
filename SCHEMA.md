# 汽车行业Wiki Schema

## Domain
新能源汽车行业知识库 — 覆盖车企战略、技术路线、供应链、全球化竞合、智能化转型

## Conventions
- 文件命名：小写、连字符、无空格（如 `byd-tang-ev.md`）
- 每个Wiki页面必须以YAML frontmatter开头
- 使用 `[[wikilinks]]` 链接页面（每页至少2个出站链接）
- 更新页面时必须更新 `updated` 日期
- 新页面必须添加到 `index.md` 对应分类下
- 每次操作必须追加到 `log.md`

## Frontmatter
```yaml
---
title: 页面标题
created: YYYY-MM-DD
updated: YYYY-MM-DD
type: entity | concept | comparison | query | summary
tags: [从下方标签分类选取]
sources: [raw/articles/source-name.md]
---
```

## Tag Taxonomy

### 车企 (Company)
- 中国: byd, geely, nio, xiaomi, xiaopeng, li-auto, leapmotor, saic, changan, great-wall, chery
- 欧洲: volkswagen, mercedes, bmw, stellantis, renault, volvo
- 美国: tesla, ford, gm, rivian, lucid
- 日韩: toyota, honda, hyundai, nissan

### 技术 (Technology)
- 三电: battery, motor, electric-arch, 800v, solid-state
- 智驾: adas, l2, l3, l4, end-to-end, vla, world-model, liDAR
- 座舱: cockpit, infotainment, voice-ai, huawei-harmony, xiaomi-hyperos
- 平台: bea, mma, neue-klasse, stla, sea

### 业务 (Business)
- 战略: strategy, investment, partnership, acquisition
- 市场: china, europe, us, southeast-asia, latin-america
- 产品: sedan, suv, mpv, truck, launch, pricing

### 供应链 (Supply Chain)
- 电池: catl, byd-findreams, cald, svolt, econ
- 芯片: nvidia, qualcomm, horizon, blacksesame
- 智驾供应商: momenta, huawei-ads, desay, bosch

### 行业趋势 (Trend)
- 政策: policy, subsidy, carbon-neutral, regulation
- 数据: sales, market-share, penetration-rate
- 舆论: controversy, recall, scandal

## Page Thresholds
- **创建页面**：某实体/概念出现2+次提及，或单篇来源的核心主题
- **更新现有页面**：来源提及已有页面覆盖的内容
- **不创建页面**：仅一笔带过的次要信息、超出领域范围的细节
- **拆分页面**：内容超过200行 → 拆分子主题并交叉链接
- **归档页面**：内容完全过时 → 移至 `_archive/`，从index移除

## Entity Pages
每个重要实体一个页面，包含：
- 概述 / 简介
- 关键事实和时间线
- 与其他实体的关系（[[wikilinks]]）
- 来源引用

## Concept Pages
每个技术概念/趋势一个页面，包含：
- 定义/解释
- 当前知识状态
- 待解决问题或争议
- 相关概念（[[wikilinks]]）

## Comparison Pages
对比分析页面，包含：
- 对比对象及原因
- 对比维度（表格形式）
- 结论/综合判断
- 来源

## Update Policy
当新信息与现有内容冲突：
1. 检查日期 — 较新的来源通常取代旧的
2. 如 genuine 矛盾，记录双方观点和日期、来源
3. 在frontmatter中标记：`contradictions: [page-name]`
4. 在lint报告中标记为待用户审核