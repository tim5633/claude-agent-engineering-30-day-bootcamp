# Day 16 — Persistent Session, Checkpoint & Approval

**2026-11-10 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

## Open course → assigned section → lab → credential

- **Official company learning:** [Developer: Production-Grade Prompting, Agents & Tool Use](https://anthropic-partners.skilljar.com/page/claude-certification-exam-prep-courses).
- **Section/topic:** Sessions, checkpoint and idempotency. Focus selected for this day; gated lesson headings should be checked in your logged-in course.
- **Hands-on lab:** Crash/restart an agent and prove no duplicate consequential operation. plus negative/security test.
- **Exam:** **CCDV-F, CCAR-F** ([official guide](https://anthropic-partners.skilljar.com/page/partner-certifications)).
- **Pass:** demonstrate implementation, tests, trace and architecture trade-off.

## Accenture Partner Academy mapping

**Official module or exam domain:** [Developer – Production-Grade Prompting, Agents & Tool Use: orchestration and memory](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations). When a domain is shown rather than a course, follow the linked certification's authoritative exam guide.

**Certification mapping:** CCDV-F: agents; CCAR-F: Context Management & Reliability (15%).

**Direct study references:**
1. [agent-sdk/overview](https://platform.claude.com/docs/en/agent-sdk/overview)
2. [docs/agent-harness-engineering.md](../docs/agent-harness-engineering.md)

## Daily five-hour schedule

| Time | What to study or build | Evidence |
|---|---|---|
| 0:00–1:30 | Study checkpoint persistence, replay protection, idempotency and risk-aware approvals; study the mapped official module and links. | Notes, 5 recall questions |
| 1:30–3:00 | Implement: Crash/restart an agent and prove no duplicate consequential operation. | Lab/code/architecture artifact |
| 3:00–4:30 | Reproduce closed-book, test negative outcomes and explain controls. | Tests and traces |
| 4:30–5:00 | Map to CCDV-F: agents; CCAR-F: Context Management & Reliability (15%) and record an English architecture explanation. | ADR and Git commit |

**Completion:** Read mapped official content; finish lab; pass positive/negative tests; state failure, cost and security trade-offs.

---

<a id="traditional-chinese"></a>

# Day 16 — 長任務 Session、Checkpoint 與核准

**2026-11-10 · 5 小時** · [首頁](../README.md)

## 每日課程 → Section → 實作 → 認證

- **公司官方課程：** [Developer: Production-Grade Prompting, Agents & Tool Use](https://anthropic-partners.skilljar.com/page/claude-certification-exam-prep-courses)。
- **Section：** Sessions, checkpoint and idempotency（指定主題，登入確認實際 Lesson 名稱）。
- **Lab：** Crash/restart an agent and prove no duplicate consequential operation.，加入越權／失敗測試。
- **認證：** **CCDV-F, CCAR-F**（[官方考綱](https://anthropic-partners.skilljar.com/page/partner-certifications)）。
- **驗收：** 實作、測試、Trace 與架構取捨。

## Accenture Partner Academy 指定內容

**官方課程模組或考綱：** [Developer – Production-Grade Prompting, Agents & Tool Use: orchestration and memory](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations)。如果標註的是考綱領域而非課程，請以該官方認證頁面的 Exam Guide 為準。

**對應認證：** CCDV-F: agents; CCAR-F: Context Management & Reliability (15%)。

**當日直達文件：**
1. [agent-sdk/overview](https://platform.claude.com/docs/en/agent-sdk/overview)
2. [docs/agent-harness-engineering.md](../docs/agent-harness-engineering.md)

## 五小時每日實作安排

| 時段 | 今天具體學習與實作 | 證據 |
|---|---|---|
| 00:00–01:30 | 理解 Checkpoint 持久化、防止重放、冪等與風險式核准，完成對應官方模組和文件。 | 概念筆記、5 題自測 |
| 01:30–03:00 | 實作：讓 Agent 中斷／恢復並證明高風險操作不會重複。 | 程式／架構成果 |
| 03:00–04:30 | 閉卷重做與反向測試，解釋安全控制。 | 測試與 Trace |
| 04:30–05:00 | 對照 CCDV-F: agents; CCAR-F: Context Management & Reliability (15%) 並完成英文架構解說。 | ADR、Git Commit |

**驗收：** 完成指定官方模組、實作並通過正反測試，能說明故障、成本與安全取捨。
