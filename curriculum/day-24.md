# Day 24 — Enterprise Harness & Sandbox Architecture

**2026-11-18 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

**Reference:** [Partner Academy](https://anthropic-partners.skilljar.com/) authorized modules, [Claude documentation](https://docs.anthropic.com/), [deep-dive](../docs/ai-sandbox-security.md).

## Assigned Partner Academy lesson and direct reading links

**Partner Academy:** [Claude Platform & Solution Design](https://anthropic-partners.skilljar.com/claude-platform-solution-design) (verified public landing page; sign in for lessons).

1. [Architect platform and solution design module](https://anthropic-partners.skilljar.com/claude-platform-solution-design)
2. [Agent SDK](https://platform.claude.com/docs/en/agent-sdk/overview)
3. [Sandbox architecture](../docs/ai-sandbox-security.md)

**Read and understand:** Compare augmentation, workflow and agent choices; document tool, authorization and sandbox boundaries.

**Hands-on assignment:** Write a client HLD and a Messages API vs SDK vs managed architecture decision.

## Five-hour integrated daily plan

| Time | Action | Evidence |
|---|---|---|
| 00:00–01:30 | Draw trust boundaries across client, API, harness, MCP and sandbox workers | Notes and sketches |
| 01:30–03:00 | Compare Messages API, Agent SDK, managed agents and self-hosted isolation | Build / design |
| 03:00–04:30 | Build HLD, runtime topology, permissions matrix and threat model | Evaluation, security and failure evidence |
| 04:30–05:00 | Defend trade-offs in cost, reliability, auditability and operations | ADR + commit + English explanation |

**Acceptance:** Security reviewer can identify enforcement points and data flows.

- [ ] Concepts and coursework completed
- [ ] Independently tested outcome
- [ ] Architecture decision and evidence committed

---

<a id="traditional-chinese"></a>

# Day 24 — 企業 Harness 與 Sandbox 架構

**2026-11-18 · 5 小時** · [首頁](../README.md)

**教材：** [Partner Academy](https://anthropic-partners.skilljar.com/) 授權課程、[官方文件](https://docs.anthropic.com/)、[深入參考](../docs/ai-sandbox-security.md)。

## 今日 Partner Academy 課程與直達教材

**Partner Academy：** [Claude Platform & Solution Design](https://anthropic-partners.skilljar.com/claude-platform-solution-design)（已確認公開課程入口；登入後查看內部單元）。

1. [Architect platform and solution design module](https://anthropic-partners.skilljar.com/claude-platform-solution-design)
2. [Agent SDK](https://platform.claude.com/docs/en/agent-sdk/overview)
3. [Sandbox architecture](../docs/ai-sandbox-security.md)

**閱讀目標：** Compare augmentation, workflow and agent choices; document tool, authorization and sandbox boundaries。

**對應實作：** Write a client HLD and a Messages API vs SDK vs managed architecture decision。

## 每日融合式五小時課表

| 時段 | 學習與實作 | 證據 |
|---|---|---|
| 00:00–01:30 | 畫出 Client、API、Harness、MCP、Sandbox 的信任邊界 | 觀念筆記與架構圖 |
| 01:30–03:00 | 比較 Messages API、Agent SDK、Managed Agents 與自架隔離 | 實作或設計 |
| 03:00–04:30 | 交付 HLD、Runtime 拓樸、權限矩陣與威脅模型 | 評估、安全與故障測試 |
| 04:30–05:00 | 向客戶說明成本、可靠性、稽核與維運取捨 | ADR、Commit、英文說明 |

**驗收：** 資安審查能清楚識別強制控制的位置。

- [ ] 完成課程與理解
- [ ] 獨立測試成果
- [ ] 提交設計取捨及證據
