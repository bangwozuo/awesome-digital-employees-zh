# Awesome Digital Employees 中文精选

> 一句话说明：这是数字员工（Digital Employee）开源生态的总入口与导航中心，精选全球最优秀的数字员工资产包、业务技能、场景工作流与连接器，帮助个人创业者、一人公司与中小企业零成本构建 AI 生产力团队。

[![License: CC-BY-4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Digital Employee](https://img.shields.io/badge/Digital%20Employee-Package-blue)](https://github.com/hermes-agent/digital-employee-spec)
[![Platform](https://img.shields.io/badge/Platform-数字员工平台-green)](https://github.com/hermes-agent)

---

## 你可以直接用什么

| 资产类型 | 说明 | 快速入口 |
|---------|------|---------|
| **DigitalEmployeePackage** | 完整的数字员工资产包，开箱即用 | [浏览资产包](#精选数字员工资产包) |
| **BusinessSkill** | 可复用的业务技能模块 | [浏览技能](#精选业务技能) |
| **ScenarioWorkflow** | 端到端场景工作流模板 | [浏览工作流](#精选场景工作流) |
| **BusinessConnector** | 第三方系统连接器 | [浏览连接器](#精选连接器) |
| **DigitalEmployee** | 单员工开源示例 | [浏览示例](#单员工开源示例) |

---

## 快速开始

### 1. 找一个数字员工资产包

```bash
# 克隆一个示例资产包
git clone https://github.com/hermes-agent/digital-employee-examples.git
cd digital-employee-examples/ecommerce-customer-service-employee
```

### 2. 阅读规范

所有资产遵循统一的 [digital-employee-spec](https://github.com/hermes-agent/digital-employee-spec) 规范，确保跨平台兼容。

### 3. 导入你的平台

支持导入到任何兼容的数字员工平台。详见 [platform-import-rules](https://github.com/hermes-agent/digital-employee-spec/blob/main/docs/platform-import-rules.md)。

---

## 分类地图

```
digital-employee-ecosystem/
├── awesome-digital-employees-zh/      ← 你在这里（总入口）
├── digital-employee-spec/              ← 总规范仓
├── digital-employee-taxonomy/          ← 分类体系仓
├── digital-employee-manifest/          ← 资产清单规范
├── digital-employee-skills-zh/         ← 技能市场
├── digital-employee-connectors-zh/       ← 连接器市场
├── digital-employee-workflows-zh/        ← 工作流市场
├── digital-employee-examples/            ← 开源示例
├── digital-employee-solution-packs-zh/   ← 解决方案包
├── digital-employee-teams-zh/            ← 团队编排
├── digital-employee-schedules-zh/        ← 调度系统
├── digital-employee-quality-gates/       ← 质量门禁
└── digital-employee-marketplace-spec/    ← 市场规范
```

---

## 精选数字员工资产包

### 电商客服员工包
- **ID**: `ecommerce-customer-service-employee`
- **描述**: 处理售前咨询、订单查询、售后退换货的全自动电商客服
- **技能**: 商品推荐、订单追踪、退换货处理、情绪安抚
- **连接器**: 淘宝/天猫、京东、拼多多、微信客服
- [查看详情](https://github.com/hermes-agent/digital-employee-examples/tree/main/ecommerce-customer-service-employee)

### 内容营销员工包
- **ID**: `content-repurposing-employee`
- **描述**: 将长文自动拆解为多平台短内容，定时发布与数据追踪
- **技能**: 内容拆解、标题生成、多平台适配、发布调度
- **连接器**: 微信公众号、小红书、抖音、知乎
- [查看详情](https://github.com/hermes-agent/digital-employee-examples/tree/main/content-repurposing-employee)

### 会议纪要员工包
- **ID**: `meeting-minutes-digital-employee`
- **描述**: 自动参会、记录、提取行动项并同步到任务系统
- **技能**: 语音转写、要点提取、行动项识别、待办同步
- **连接器**: 飞书会议、腾讯会议、钉钉、Notion
- [查看详情](https://github.com/hermes-agent/digital-employee-examples/tree/main/meeting-minutes-digital-employee)

---

## 精选业务技能

| 技能名称 | 分类 | 描述 | 来源 |
|---------|------|------|------|
| `product-recommendation` | 电商零售 | 基于用户画像的商品推荐 | digital-employee-skills-zh |
| `content-repurposing` | 内容营销 | 长文拆解多平台短内容 | digital-employee-skills-zh |
| `meeting-minutes-extraction` | 自动化办公 | 会议要点与行动项提取 | digital-employee-skills-zh |
| `customer-sentiment-analysis` | 客户服务 | 客户情绪识别与分级 | digital-employee-skills-zh |
| `invoice-processing` | 财税 | 发票识别与台账录入 | digital-employee-skills-zh |
| `contract-review` | 法务合同 | 合同风险条款识别 | digital-employee-skills-zh |
| `candidate-screening` | 招聘 | 简历筛选与匹配度评分 | digital-employee-skills-zh |
| `data-report-generation` | 数据分析 | 自动数据报表生成 | digital-employee-skills-zh |

---

## 精选场景工作流

| 工作流名称 | 触发方式 | 描述 | 来源 |
|-----------|---------|------|------|
| `ecommerce-order-fullfillment` | 事件触发 | 从下单到发货的全自动处理 | digital-employee-workflows-zh |
| `content-publish-pipeline` | 定时触发 | 内容生产-审核-发布-数据追踪 | digital-employee-workflows-zh |
| `customer-complaint-escalation` | 事件触发 | 客诉识别-分级-升级-闭环 | digital-employee-workflows-zh |
| `daily-sales-report` | 定时触发 | 每日销售数据汇总与推送 | digital-employee-workflows-zh |
| `lead-nurture-sequence` | 定时触发 | 潜客培育自动化流程 | digital-employee-workflows-zh |

---

## 精选连接器

| 连接器名称 | 平台类型 | 支持操作 | 来源 |
|-----------|---------|---------|------|
| `wechat-official-connector` | 私域运营 | 消息收发、粉丝管理、菜单配置 | digital-employee-connectors-zh |
| `taobao-open-connector` | 电商零售 | 订单查询、物流同步、退款处理 | digital-employee-connectors-zh |
| `feishu-connector` | 协同办公 | 文档、表格、会议、审批 | digital-employee-connectors-zh |
| `notion-connector` | 知识库 | 页面、数据库、搜索、同步 | digital-employee-connectors-zh |
| `stripe-connector` | 财税 | 支付、对账、发票 | digital-employee-connectors-zh |
| `zhipu-ai-connector` | AI模型 | 文本生成、Embedding、微调 | digital-employee-connectors-zh |

---

## 单员工开源示例

| 示例名称 | 行业 | 复杂度 | 快速体验 |
|---------|------|--------|---------|
| [电商客服员工](https://github.com/hermes-agent/digital-employee-examples/tree/main/ecommerce-customer-service-employee) | 电商零售 | 中级 | `git clone` + 配置API Key |
| [内容营销员工](https://github.com/hermes-agent/digital-employee-examples/tree/main/content-repurposing-employee) | 内容营销 | 初级 | `git clone` + 配置账号 |
| [会议纪要员工](https://github.com/hermes-agent/digital-employee-examples/tree/main/meeting-minutes-digital-employee) | 自动化办公 | 中级 | `git clone` + 配置会议平台 |
| [客户反馈分析师](https://github.com/hermes-agent/digital-employee-examples/tree/main/customer-feedback-analyst) | 客户服务 | 初级 | `git clone` + 上传数据 |
| [报价估算员工](https://github.com/hermes-agent/digital-employee-examples/tree/main/quote-estimator-digital-employee) | 销售增长 | 初级 | `git clone` + 配置产品库 |
| [PRD助手员工](https://github.com/hermes-agent/digital-employee-examples/tree/main/prd-assistant-digital-employee) | 互联网产品研发 | 中级 | `git clone` + 配置模板 |
| [现金流提醒员工](https://github.com/hermes-agent/digital-employee-examples/tree/main/cashflow-reminder-employee) | 财税 | 初级 | `git clone` + 配置数据源 |
| [外包需求分析师](https://github.com/hermes-agent/digital-employee-examples/tree/main/outsourcing-requirement-analyst) | 技术外包 | 高级 | `git clone` + 配置行业知识库 |
| [GitHub仓库分析师](https://github.com/hermes-agent/digital-employee-examples/tree/main/github-repo-analyst-employee) | 平台运营 | 中级 | `git clone` + 配置GitHub Token |

---

## 平台入口

- **数字员工平台主站**: [https://github.com/hermes-agent](https://github.com/hermes-agent)
- **规范文档**: [digital-employee-spec](https://github.com/hermes-agent/digital-employee-spec)
- **分类体系**: [digital-employee-taxonomy](https://github.com/hermes-agent/digital-employee-taxonomy)
- **技能市场**: [digital-employee-skills-zh](https://github.com/hermes-agent/digital-employee-skills-zh)
- **连接器市场**: [digital-employee-connectors-zh](https://github.com/hermes-agent/digital-employee-connectors-zh)
- **示例仓库**: [digital-employee-examples](https://github.com/hermes-agent/digital-employee-examples)

---

## 贡献方式

我们欢迎所有形式的贡献！详见 [CONTRIBUTING.md](./CONTRIBUTING.md)。

### 快速贡献清单

- [ ] 阅读 [CONTRIBUTING.md](./CONTRIBUTING.md)
- [ ] 阅读 [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)
- [ ] 确保你的资产符合 [digital-employee-spec](https://github.com/hermes-agent/digital-employee-spec)
- [ ] 提交 PR 到本仓库的对应分类

---

## 目录结构

```
awesome-digital-employees-zh/
├── README.md                          # 本文件
├── LICENSE                            # CC-BY-4.0
├── NOTICE                             # 归属与致谢
├── CONTRIBUTING.md                    # 贡献指南
├── CODE_OF_CONDUCT.md                 # 行为准则
├── SECURITY.md                        # 安全政策
├── SUPPORT.md                         # 获取帮助
└── .github/
    ├── ISSUE_TEMPLATE/
    │   ├── bug_report.md              # Bug 报告模板
    │   └── feature_request.md         # 功能请求模板
    └── PULL_REQUEST_TEMPLATE.md       # PR 模板
```

---

## License 与来源说明

本仓库采用 [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/) 授权。

- 你可以自由分享、改编本仓库内容
- 必须注明出处：Hermes Agent / 数字员工平台
- 本仓库中的精选资产链接指向各自原仓库，其 License 以原仓库为准

---

## Topics

`digital-employee` `ai-agent` `agentic-workflow` `business-skill` `business-connector` `scenario-workflow` `scheduled-task` `small-business` `solo-founder` `one-person-company` `china-smb` `hermes-agent` `open-source-agents`
