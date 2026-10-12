# Awesome Digital Employees · 数字员工开源生态总入口

> **25 名开箱即用的中文数字员工**——无需 API Key、无需部署、平台无关（Coze / WorkBuddy / Dify / Claude / ChatGPT 均可导入），模型算力来自你自己的订阅。

[![License: CC-BY-4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Employees](https://img.shields.io/badge/%E6%95%B0%E5%AD%97%E5%91%98%E5%B7%A5-25%20%E5%90%8D-blue)](#数字员工目录)
[![Assets](https://img.shields.io/badge/%E8%B5%84%E4%BA%A7-137%20%E6%8A%80%E8%83%BD%20%2B%20119%20%E5%B7%A5%E4%BD%9C%E6%B5%81-green)](#数字员工目录)
[![Spec](https://img.shields.io/badge/%E8%A7%84%E8%8C%83-digital--employee--spec-orange)](https://github.com/bangwozuo/digital-employee-spec)

## 这是什么

每个数字员工是一个**完整的资产包仓库**，包含：

- `skills/` 原子业务技能（SKILL.md + prompt + schema + 实跑产物）
- `workflows/` 场景工作流（DAG 编排 + run_flow.py）
- `docs/` 交付文档 + 每资产一支演示视频（GIF 内联，点开即看）
- `tests/` 结构校验 pytest，256 资产 × 10 项深度校验全通过

## 数字员工目录（25 名已上线）

| 客群 | 员工 | 仓库 | 技能 | 工作流 |
|---|---|---|---:|---:|
| OPC | **出海增长官** | [`coldstart-growth-zh`](https://github.com/bangwozuo/coldstart-growth-zh) | 7 | 5 |
|  | **发布指挥官** | [`launch-commander-zh`](https://github.com/bangwozuo/launch-commander-zh) | 9 | 5 |
|  | **SEO 架构师** | [`seo-matrix-zh`](https://github.com/bangwozuo/seo-matrix-zh) | 7 | 6 |
|  | **反馈分析师** | [`feedback-hub-zh`](https://github.com/bangwozuo/feedback-hub-zh) | 6 | 5 |
|  | **分发中控** | [`multi-publish-zh`](https://github.com/bangwozuo/multi-publish-zh) | 6 | 5 |
| 自媒体创作者 | **选题策划师** | [`topic-planner-zh`](https://github.com/bangwozuo/topic-planner-zh) | 6 | 4 |
|  | **脚本创作师** | [`script-writer-zh`](https://github.com/bangwozuo/script-writer-zh) | 6 | 4 |
|  | **评论运营官** | [`engagement-ops-zh`](https://github.com/bangwozuo/engagement-ops-zh) | 6 | 4 |
|  | **引流转化师** | [`funnel-builder-zh`](https://github.com/bangwozuo/funnel-builder-zh) | 6 | 4 |
|  | **分发改写师** | [`cross-post-zh`](https://github.com/bangwozuo/cross-post-zh) | 6 | 4 |
|  | **数据复盘师** | [`data-recap-zh`](https://github.com/bangwozuo/data-recap-zh) | 6 | 4 |
| 电商小卖家 | **商品视觉师** | [`product-visual-zh`](https://github.com/bangwozuo/product-visual-zh) | 6 | 5 |
|  | **店铺客服官** | [`shop-support-zh`](https://github.com/bangwozuo/shop-support-zh) | 6 | 5 |
|  | **评价运营官** | [`review-manager-zh`](https://github.com/bangwozuo/review-manager-zh) | 5 | 5 |
|  | **Listing 文案师** | [`listing-copy-zh`](https://github.com/bangwozuo/listing-copy-zh) | 5 | 5 |
|  | **多店运营官** | [`multi-shop-ops-zh`](https://github.com/bangwozuo/multi-shop-ops-zh) | 5 | 5 |
|  | **店铺编导** | [`shop-video-zh`](https://github.com/bangwozuo/shop-video-zh) | 5 | 5 |
|  | **选品分析师** | [`product-research-zh`](https://github.com/bangwozuo/product-research-zh) | 5 | 5 |
| 本地生活商家 | **探店编导** | [`local-content-zh`](https://github.com/bangwozuo/local-content-zh) | 5 | 5 |
|  | **口碑捍卫者** | [`review-firefighter-zh`](https://github.com/bangwozuo/review-firefighter-zh) | 4 | 5 |
|  | **复购管家** | [`local-retention-zh`](https://github.com/bangwozuo/local-retention-zh) | 5 | 5 |
|  | **经营日报员** | [`daily-report-zh`](https://github.com/bangwozuo/daily-report-zh) | 3 | 4 |
|  | **团购设计师** | [`groupbuy-designer-zh`](https://github.com/bangwozuo/groupbuy-designer-zh) | 4 | 5 |
|  | **排班调度师** | [`appointment-scheduler-zh`](https://github.com/bangwozuo/appointment-scheduler-zh) | 4 | 5 |
|  | **会员唤醒师** | [`member-reactivation-zh`](https://github.com/bangwozuo/member-reactivation-zh) | 4 | 5 |

### 按客群找

- **OPC**（5 名）：独立开发者与一人公司——增长获客、发布冲刺、SEO 矩阵、反馈与分发
- **自媒体创作者**（6 名）：选题、脚本、评论区、分发改写与数据复盘，一条内容生产线
- **电商小卖家**（7 名）：商品视觉、客服、评价、Listing、多店运营与选品
- **本地生活商家**（7 名）：探店内容、差评处置、私域复购、团购与排班调度

## 快速开始

```bash
# 1. 挑一名员工，克隆它的仓库
git clone https://github.com/bangwozuo/topic-planner-zh.git

# 2. 读 README 与 skills/*/SKILL.md，每个技能都有 prompt + schema + 实跑示例
# 3. 把 SKILL.md 导入你的平台（Coze / WorkBuddy / Dify / Claude / ChatGPT）
```

不看代码想先看效果？每名员工的 `docs/demo.mp4` 是真实执行录播合集，仓库 README 首屏就是内联 GIF 演示。

## 规范与质量

- 资产格式对齐 [digital-employee-spec](https://github.com/bangwozuo/digital-employee-spec)（SKILL.md 事实标准）
- 定义卡 12 主字段 + 能力分级（S/M/L 人日）+ 可信三字段
- 全部 256 个资产通过 V1-V10 深度校验（脚本可跑、示例真实、无占位符）

## 生态地图

| 位置 | 用途 |
|---|---|
| [官网](https://bangwozuo.github.io) | 品牌首页与员工总览 |
| [digital-employees-hub-zh](https://github.com/bangwozuo/digital-employees-hub-zh) | 25 员工总目录 + 256 支演示视频索引 |
| 本仓库 | 对外精选导航（你在这里） |
| [digital-employee-spec](https://github.com/bangwozuo/digital-employee-spec) | 资产格式总规范 |

## License

内容以 [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/) 开源，代码片段以 MIT 开源。
