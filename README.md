# BaiRui Product Case Library

百瑞产品案例库用于沉淀真实客户项目、交付复盘、需求共创记录和产品标准化经验。

这个仓库不是代码主仓库，而是公司内部和对外可脱敏复用的案例资产库。后续每个项目都应沉淀为一篇结构化案例，方便销售、产品、研发、交付和管理复用。

## 快速入口

- [案例总索引](INDEX.md)
- [分类与标签规范](taxonomy/README.md)
- [项目案例复盘模板](templates/case-review-template.md)

## 当前案例

| 编号 | 案例 | 类型 | 阶段 | 关键主题 |
| --- | --- | --- | --- | --- |
| CASE-2026-001 | [AI Agent 项目交付复盘：从定制交付到标准化产品平台](cases/2026-06-ai-agent-standardization-review.md) | 交付复盘 / 产品标准化 | 已完成初版 | Agent、平台化、需求冻结、部署、GitHub、微信、模型中转站 |

## 案例应回答的问题

1. 客户最初要解决什么业务问题。
2. 项目过程中暴露了哪些需求、技术、交付和沟通问题。
3. 我们从这单里抽象出了什么可复用产品能力。
4. 下一次如何用平台化和标准化减少反复改方向、部署痛苦和验收不清。

## 推荐目录结构

```text
BaiRui-Product-Case-Library/
  README.md
  INDEX.md
  cases/
    2026-06-ai-agent-standardization-review.md
  taxonomy/
    README.md
  templates/
    case-review-template.md
```

## 命名规则

案例文件建议使用：

```text
cases/YYYY-MM-short-topic.md
```

示例：

```text
cases/2026-06-ai-agent-standardization-review.md
cases/2026-07-customer-service-agent-review.md
cases/2026-08-private-deployment-acceptance.md
```

## 关联工程仓库

以下仓库作为当前案例的业务和技术背景，只读引用，不在本案例库中复制源码或改动源码：

- [LUTAO581314/赫尔墨斯-](https://github.com/LUTAO581314/hermes-)
- [LUTAO581314/MOXI-cloud-agent](https://github.com/LUTAO581314/MOXI-cloud-agent)

## 使用方式

- 销售和客户沟通：先读案例里的“客户共创需求”和“标准化边界”，避免承诺无限定制。
- 产品规划：把案例中的痛点归入平台能力、配置项、交付流程和验收标准。
- 研发排期：优先建设能减少重复部署、重复改方向、重复解释的基础能力。
- 交付复盘：每单结束后按模板补充事实、证据、决策和可复用资产。

## 维护规则

- 新增案例时，必须同步更新 [案例总索引](INDEX.md)。
- 每篇案例顶部必须保留元数据块，包含编号、日期、类型、阶段、标签和关联仓库。
- 案例不要写入客户敏感信息、密钥、密码、Token、服务器口令或未脱敏截图。
- 涉及源码仓库时只放链接和背景说明，不复制无关源码。
- 对外公开前必须检查品牌、客户名称、账号、域名、密钥和合同信息。
