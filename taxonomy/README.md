# 分类与标签规范

本规范用于保证案例库可检索、可统计、可复用。新增案例时，应从以下分类中选择，不够再补充。

## 案例类型

- `交付复盘`：真实客户项目交付后的复盘。
- `产品标准化`：从项目中抽象出标准产品能力。
- `故障复盘`：线上、部署、第三方服务或配置问题复盘。
- `客户共创`：线下或线上共创需求沉淀。
- `售前方案`：售前沟通、方案设计和边界确认。
- `验收案例`：部署验收、效果验证和客户确认记录。

## 客户类型

- `商业化试点客户`
- `内部试用客户`
- `私有化部署客户`
- `行业样板客户`
- `渠道合作客户`

## 项目阶段

- `线索沟通`
- `需求共创`
- `方案确认`
- `开发中`
- `部署中`
- `验收中`
- `已交付`
- `复盘完成`

## 推荐标签

### 产品与业务

- `agent`
- `platformization`
- `standardization`
- `requirement-freeze`
- `customer-co-creation`
- `acceptance`
- `pricing`
- `license`

### 技术能力

- `model-api`
- `github`
- `wechat`
- `tts`
- `memory`
- `scheduler`
- `knowledge-base`
- `hotspot`
- `deployment`
- `observability`

### 风险与问题

- `scope-creep`
- `manual-deployment`
- `third-party-config`
- `brand-governance`
- `security`
- `privacy`
- `ops-risk`

## 案例元数据格式

每篇案例顶部建议使用：

```yaml
---
case_id: CASE-YYYY-NNN
title: 案例标题
date: YYYY-MM
status: 初版完成
case_types:
  - 交付复盘
customer_type: 商业化试点客户
project_stage: 复盘完成
owner: 百瑞团队
related_repositories:
  - https://github.com/example/repo
tags:
  - agent
  - deployment
visibility: public-redacted
---
```

## 可公开级别

- `internal`：仅内部可见，可能包含客户细节。
- `public-redacted`：已脱敏，可公开展示。
- `customer-approved`：客户明确同意公开引用。

默认使用 `public-redacted`，除非客户明确批准公开名称、截图或业务数据。
