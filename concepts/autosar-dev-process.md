---
title: AUTOSAR开发流程
created: 2026-06-25
updated: 2026-06-25
type: concept
tags: [technology, software, autosar, development-process]
sources: [memory/2026-06-25.md]
---

# AUTOSAR开发流程

汽车软件标准化开发架构，从需求到代码的系统化流程。

## SWRS → 架构设计 → Simulink建模

### 1. SWRS输出

软件需求规范（Software Requirements Specification）定义：

| 维度 | 内容 |
|------|------|
| 功能需求 | 系统功能描述 |
| 输入输出信号 | 信号列表、数据类型、有效范围 |
| 服务调用关系 | SWC间通信关系 |
| 时序约束 | 实时性要求、调度周期 |
| 安全等级 | ASIL等级（A/B/C/D） |

### 2. SWC划分原则

软件组件（Software Component）划分依据：

1. **功能内聚**：相关功能封装在同一SWC
2. **ASIL隔离**：不同安全等级分离，避免ASIL混用
3. **复用性**：可复用模块独立封装
4. **调度粒度**：匹配调度周期要求
5. **团队边界**：考虑开发团队分工

### 3. VFB设计

虚拟功能总线（Virtual Functional Bus）定义SWC间通信：

| 端口类型 | 特点 | 使用场景 |
|----------|------|----------|
| Sender-Receiver | 单向数据传输 | 传感器信号、状态信息 |
| Client-Server | 双向服务调用 | 诊断服务、控制命令 |

### 4. 接口定义

- 数据类型：uint8/uint16/uint32/boolean/struct
- Initial Value：初始值设置
- Synchronous/Asynchronous：同步/异步调用方式

### 5. Simulink建模

- SWC骨架模型：由ARXML自动生成
- Runnable Entity映射：模型函数与AUTOSAR调度关联
- Stateflow状态机：可选C动作语言（Stateflow支持类C语法）

## MATLAB单元测试语法

| 特点 | 说明 |
|------|------|
| 风格 | 脚本风格（Python-like），不是类C |
| Stateflow | 可选C动作语言 |
| 函数定义 | `function y = myFunc(x)` |
| 测试框架 | MATLAB Unit Test Framework |

## 为什么汽车行业用建模

| 原因 | 说明 |
|------|------|
| 降低认知负担 | 可视化比代码更直观 |
| 早期验证 | 仿真验证逻辑正确性 |
| 需求追溯 | 证明需求被正确实现 |
| 自动代码生成 | 避免低级编码错误 |
| ISO 26262 | ASIL-C/D等级要求建模验证 |

## 与其他概念关联

- [[iso-26262]] - 功能安全标准，ASIL等级要求
- [[ai-software-engineering]] - AI对传统开发流程的影响
- [[ai-testing-automation]] - AI自动化测试与AUTOSAR兼容性

## 来源

- memory/2026-06-25.md：AUTOSAR开发流程深度讨论