# Day 29 — Go-Live Drill: Harness, Sandbox & Evaluation

**2026-11-23 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

**Reference:** [Partner Academy](https://anthropic-partners.skilljar.com/) authorized modules, [Claude documentation](https://docs.anthropic.com/), [deep-dive](../docs/evaluation-harness.md).

## Assigned Partner Academy lesson and direct reading links

**Partner Academy:** [Enterprise Integration & Production](https://anthropic-partners.skilljar.com/enterprise-integration-production) (company login required for course modules).

1. [Production integration module](https://anthropic-partners.skilljar.com/enterprise-integration-production)
2. [Evaluation harness](../docs/evaluation-harness.md)
3. [Sandbox boundaries](../docs/ai-sandbox-security.md)

**Study topics:** Review fail-closed security, bounded harnesses, checkpoint restore and outcome evaluation.

**Required deliverable:** Run failure drills and fresh-fixture evals; produce go/no-go report with metrics.

## Five-hour integrated daily plan

| Time | Action | Evidence |
|---|---|---|
| 00:00–01:30 | Plan failure tests: infinite loop, tool crash, injected document, denied egress and write attempt | Notes and sketches |
| 01:30–03:00 | Run complete golden evaluations from isolated disposable fixtures | Build / design |
| 03:00–04:30 | Verify safe stop, session recovery, denied actions, approval gates and rollback | Evaluation, security and failure evidence |
| 04:30–05:00 | Write go/no-go report with evidence and residual risks | ADR + commit + English explanation |

**Acceptance:** Critical controls survive fault injection and a clean eval run is recorded.

- [ ] Concepts and coursework completed
- [ ] Independently tested outcome
- [ ] Architecture decision and evidence committed

---

<a id="traditional-chinese"></a>

# Day 29 — Harness、Sandbox 與 Evaluation 上線演練

**2026-11-23 · 5 小時** · [首頁](../README.md)

**教材：** [Partner Academy](https://anthropic-partners.skilljar.com/) 授權課程、[官方文件](https://docs.anthropic.com/)、[深入參考](../docs/evaluation-harness.md)。

## 今日 Partner Academy 課程與直達教材

**Partner Academy:** [Enterprise Integration & Production](https://anthropic-partners.skilljar.com/enterprise-integration-production) (company login required for course modules).

1. [Production integration module](https://anthropic-partners.skilljar.com/enterprise-integration-production)
2. [Evaluation harness](../docs/evaluation-harness.md)
3. [Sandbox boundaries](../docs/ai-sandbox-security.md)

**學習重點:** Review fail-closed security, bounded harnesses, checkpoint restore and outcome evaluation.

**當天交付:** Run failure drills and fresh-fixture evals; produce go/no-go report with metrics.

## 每日融合式五小時課表

| 時段 | 學習與實作 | 證據 |
|---|---|---|
| 00:00–01:30 | 設計無限循環、工具當機、惡意文件、拒絕外連與越權寫入測試 | 觀念筆記與架構圖 |
| 01:30–03:00 | 在乾淨隔離 Fixture 執行 Golden Evaluation | 實作或設計 |
| 03:00–04:30 | 驗證停止、恢復、拒絕操作、人工核准與 Rollback | 評估、安全與故障測試 |
| 04:30–05:00 | 以證據完成 Go／No-Go 報告與殘餘風險表 | ADR、Commit、英文說明 |

**驗收：** 故障情境下安全控制仍有效，且有可重現的評估證據。

- [ ] 完成課程與理解
- [ ] 獨立測試成果
- [ ] 提交設計取捨及證據
