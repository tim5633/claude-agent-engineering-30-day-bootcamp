# Day 29 — Go-live simulation

**2026-11-23 | 5 hours** · [Home](../README.md) · [Read Traditional Chinese](#traditional-chinese)

## Objective and official resources

Study Day 29 — Go-live simulation using authorized [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) course content, current exam guides and [Claude documentation](https://docs.anthropic.com/). Focus on enterprise security, design, communication and independent execution.

## Daily schedule

| Time | Task | Evidence |
|---|---|---|
| 0:00–1:30 | Course or exam guide analysis and notes | Five key concepts |
| 1:30–3:00 | Guided challenge: Simulate API timeout, sandbox denial, crash recovery and injected prompts | Reviewable deliverable |
| 3:00–4:30 | Independent client/engineering scenario, failure analysis and revision | Tests, decisions, artifacts |
| 4:30–5:00 | English presentation, self-assessment and commit | Daily log / ADR |

## Completion criteria

- [ ] Independently demonstrate the daily deliverable
- [ ] Identify security, cost and operational trade-offs
- [ ] Retain evidence, technical notes and an implementation or documentation commit
- [ ] Answer questions without reading the lesson

---

<a id="traditional-chinese"></a>

# Day 29 — Go-live simulation

**2026-11-23 · 5 小時** · [Home](../README.md)

## 今日學習目標

深入掌握 **Go-live simulation** 的原理、應用、替代設計、風險與成本。

**課程來源：** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/)（以授權帳號內最新課綱為準）、[Claude Academy](https://academy.claude.com/)、[官方技術文件](https://docs.anthropic.com/)。

## 每日時間線

| 時間 | 學習任務 | 交付 |
|---|---|---|
| 00:00–01:30 | 官方課程與技術文件，整理 5 個核心概念 | Notes |
| 01:30–03:00 | Guided lab：將 Go-live simulation 應用於 Capstone | Working code |
| 03:00–04:30 | Closed-book：自行擴充、注入錯誤、測試與 Debug | Tests + Git commit |
| 04:30–05:00 | 驗收、技術決策、英文解說 | Daily log + ADR |

## 實戰驗收

在 [Enterprise Financial Research Agent](../docs/capstone.md) 實作今日能力，保留測試和 trace。自行說明為何選擇此架構、如何處理權限/成本/失敗、如何客觀評估。

- [ ] 完成官方課程與筆記
- [ ] 獨立完成可執行功能
- [ ] 相關測試通過
- [ ] 記錄失敗案例與修復
- [ ] Git commit、英文 3 分鐘講解


## Advanced Track — Integrated Agent Harness + Sandbox + Eval security gate

Review [Harness](../docs/agent-harness-engineering.md), [Sandbox](../docs/ai-sandbox-security.md) and [Evals](../docs/evaluation-harness.md). Inject simulated long-running task timeout, process crash, denied network egress, malicious retrieved instruction and unauthorized SQL write; verify isolation, checkpoint recovery, audit trail and outcome graders.

**Additional exit check:** Demonstrate the boundary with a repeatable test and record one architecture trade-off in the daily engineering log.
