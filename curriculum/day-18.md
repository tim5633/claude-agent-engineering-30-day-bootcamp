# Day 18 — Evaluation Harness & Quality Gates

**2026-11-12 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

## Open course → assigned section → lab → credential

- **Official company learning:** [Developer: Production Engineering, Evals & Security](https://anthropic-partners.skilljar.com/page/claude-certification-exam-prep-courses).
- **Section/topic:** Golden cases, outcome graders and evaluation harness. Focus selected for this day; gated lesson headings should be checked in your logged-in course.
- **Hands-on lab:** Create a 50-case clean-fixture eval harness and baseline report. plus negative/security test.
- **Exam:** **CCDV-F, CCAO-F** ([official guide](https://anthropic-partners.skilljar.com/page/partner-certifications)).
- **Pass:** demonstrate implementation, tests, trace and architecture trade-off.

## Accenture Partner Academy mapping

**Official module or exam domain:** [Developer – Production Engineering, Evals & Security: evals and tests; Associate – Output Evaluation review](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations). When a domain is shown rather than a course, follow the linked certification's authoritative exam guide.

**Certification mapping:** CCDV-F: Evals & Security; CCAO-F: Output Evaluation (21%).

**Direct study references:**
1. [research/demystifying-evals-for-ai-agents](https://www.anthropic.com/research/demystifying-evals-for-ai-agents)
2. [docs/evaluation-harness.md](../docs/evaluation-harness.md)

## Daily five-hour schedule

| Time | What to study or build | Evidence |
|---|---|---|
| 0:00–1:30 | Differentiate deterministic graders, LLM-as-judge, task outcomes and regression; study the mapped official module and links. | Notes, 5 recall questions |
| 1:30–3:00 | Implement: Create a 50-case clean-fixture eval harness and baseline report. | Lab/code/architecture artifact |
| 3:00–4:30 | Reproduce closed-book, test negative outcomes and explain controls. | Tests and traces |
| 4:30–5:00 | Map to CCDV-F: Evals & Security; CCAO-F: Output Evaluation (21%) and record an English architecture explanation. | ADR and Git commit |

**Completion:** Read mapped official content; finish lab; pass positive/negative tests; state failure, cost and security trade-offs.

---

<a id="traditional-chinese"></a>

# Day 18 — Evaluation Harness 與品質閘門

**2026-11-12 · 5 小時** · [首頁](../README.md)

## 每日課程 → Section → 實作 → 認證

- **公司官方課程：** [Developer: Production Engineering, Evals & Security](https://anthropic-partners.skilljar.com/page/claude-certification-exam-prep-courses)。
- **Section：** Golden cases, outcome graders and evaluation harness（指定主題，登入確認實際 Lesson 名稱）。
- **Lab：** Create a 50-case clean-fixture eval harness and baseline report.，加入越權／失敗測試。
- **認證：** **CCDV-F, CCAO-F**（[官方考綱](https://anthropic-partners.skilljar.com/page/partner-certifications)）。
- **驗收：** 實作、測試、Trace 與架構取捨。

## Accenture Partner Academy 指定內容

**官方課程模組或考綱：** [Developer – Production Engineering, Evals & Security: evals and tests; Associate – Output Evaluation review](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations)。如果標註的是考綱領域而非課程，請以該官方認證頁面的 Exam Guide 為準。

**對應認證：** CCDV-F: Evals & Security; CCAO-F: Output Evaluation (21%)。

**當日直達文件：**
1. [research/demystifying-evals-for-ai-agents](https://www.anthropic.com/research/demystifying-evals-for-ai-agents)
2. [docs/evaluation-harness.md](../docs/evaluation-harness.md)

## 五小時每日實作安排

| 時段 | 今天具體學習與實作 | 證據 |
|---|---|---|
| 00:00–01:30 | 理解確定性 Grader、LLM-as-Judge、實際結果與回歸，完成對應官方模組和文件。 | 概念筆記、5 題自測 |
| 01:30–03:00 | 實作：建立 50 筆乾淨測試環境評估與 Baseline 報告。 | 程式／架構成果 |
| 03:00–04:30 | 閉卷重做與反向測試，解釋安全控制。 | 測試與 Trace |
| 04:30–05:00 | 對照 CCDV-F: Evals & Security; CCAO-F: Output Evaluation (21%) 並完成英文架構解說。 | ADR、Git Commit |

**驗收：** 完成指定官方模組、實作並通過正反測試，能說明故障、成本與安全取捨。
