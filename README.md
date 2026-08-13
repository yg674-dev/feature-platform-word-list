# Feature Platform · Word List

Feature Platform 内**词表 (Word List) 管理**能力相关的原型和 PRD 归档。

覆盖：词库主列表 (F1) · 创建/编辑向导 (E2) · 批量导入 (E3) · 引用血缘 (F3) · 效果监控 (G1) · 审批流三视角 (owner / reviewer / prototype) · 命中溯源 (trace-hit)。

## 在线预览（直接浏览器打开）

### 主流程原型

- [F1 · 词库管理主列表 v0.3](https://htmlpreview.github.io/?https://github.com/yg674-dev/feature-platform-word-list/blob/main/feature-platform-word-list-prototype-v0.3.html) — 最新主页面 (2025-07-31)
- [E2 · 创建/编辑向导 v0.3](https://htmlpreview.github.io/?https://github.com/yg674-dev/feature-platform-word-list/blob/main/feature-platform-word-list-prototype-v0.3-E2.html) — 3-step wizard (2025-07-14)
- [E3 · 批量导入 v0.3](https://htmlpreview.github.io/?https://github.com/yg674-dev/feature-platform-word-list/blob/main/feature-platform-word-list-prototype-v0.3-E3.html) — CSV / 粘贴批量上传 (2025-06-24)
- [F3 · 词表引用血缘 v0.3](https://htmlpreview.github.io/?https://github.com/yg674-dev/feature-platform-word-list/blob/main/feature-platform-word-list-prototype-v0.3-F3.html) — 引用关系查询 (2025-06-25)
- [G1 · 效果监控 v0.3](https://htmlpreview.github.io/?https://github.com/yg674-dev/feature-platform-word-list/blob/main/feature-platform-word-list-prototype-v0.3-G1.html) — 命中 metrics 面板 (2025-07-17)

### 审批流三视角

- [Approval · Owner 视角 v0.1](https://htmlpreview.github.io/?https://github.com/yg674-dev/feature-platform-word-list/blob/main/feature-platform-word-list-approval-owner-v0.1.html) — 词表 Owner 侧 (2025-06-25)
- [Approval · Reviewer 视角 v0.1](https://htmlpreview.github.io/?https://github.com/yg674-dev/feature-platform-word-list/blob/main/feature-platform-word-list-approval-reviewer-v0.1.html) — 审批人侧 (2025-07-14)
- [Approval · 工单总览 v0.1](https://htmlpreview.github.io/?https://github.com/yg674-dev/feature-platform-word-list/blob/main/feature-platform-word-list-approval-prototype-v0.1.html) — 审批流原型 (2025-06-23)

### 追溯 & 分析

- [Trace Hit · 命中溯源 v0.1](https://htmlpreview.github.io/?https://github.com/yg674-dev/feature-platform-word-list/blob/main/feature-platform-word-list-trace-hit-v0.1.html) — 单条命中回溯 (2025-07-21)

### PRD

- [Word List Lifecycle PRD](https://htmlpreview.github.io/?https://github.com/yg674-dev/feature-platform-word-list/blob/main/Word%20List%20Lifecycle%20PRD.html) — Feature Platform + IDSP 双语 PRD (2025-07-21)

## 文件清单

| 文件 | 类型 | 版本 | 日期 |
| --- | --- | --- | --- |
| `feature-platform-word-list-prototype-v0.3.html` | F1 主列表 | v0.3 | 2025-07-31 |
| `feature-platform-word-list-prototype-v0.3-E2.html` | E2 创建向导 | v0.3 | 2025-07-14 |
| `feature-platform-word-list-prototype-v0.3-E3.html` | E3 批量导入 | v0.3 | 2025-06-24 |
| `feature-platform-word-list-prototype-v0.3-F3.html` | F3 引用血缘 | v0.3 | 2025-06-25 |
| `feature-platform-word-list-prototype-v0.3-G1.html` | G1 效果监控 | v0.3 | 2025-07-17 |
| `feature-platform-word-list-approval-owner-v0.1.html` | 审批·Owner | v0.1 | 2025-06-25 |
| `feature-platform-word-list-approval-reviewer-v0.1.html` | 审批·Reviewer | v0.1 | 2025-07-14 |
| `feature-platform-word-list-approval-prototype-v0.1.html` | 审批·工单 | v0.1 | 2025-06-23 |
| `feature-platform-word-list-trace-hit-v0.1.html` | 命中溯源 | v0.1 | 2025-07-21 |
| `Word List Lifecycle PRD.html` | PRD | Lifecycle | 2025-07-21 |

## 关键口径参考

- **命名**：`Block list / Allow list`（避免 blacklist/whitelist 术语）· 字段名 `List Type`
- **权限**：全员默认 View · Draft/Archive Owner-only · **Active edit 全员可改 + 走审批**（reviewer pool + 禁止自审）
- **MVP scope**：手动输入 + 批量导入 + IDSP 规则引用 + 增删改；不含翻译 / 效果监控 / 血缘的高级能力
- **审核语言优先级**：`en → es → id → ar → vi → th → ms → tr → fil → ja → fr → de → ro → it → pt → ko`

## 本地打开

```bash
git clone https://github.com/yg674-dev/feature-platform-word-list.git
cd feature-platform-word-list
open "feature-platform-word-list-prototype-v0.3.html"
```
