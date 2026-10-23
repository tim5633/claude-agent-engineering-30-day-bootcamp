# Day 19 — Tracing, Cost, Reliability & FinOps

**2026-11-13 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

## Corporate academy course, section, lab and exam

- **Open:** [Developer: Production Engineering, Evals & Security](https://anthropic-partners.skilljar.com/page/claude-certification-exam-prep-courses) (company email).
- **Study focus:** Tracing, cost, latency and regression evidence (recommended reading within official course; not a verified internal lesson title).
- **Lab:** Correlate model turns, tool calls and sandbox decisions to eval outcomes.; include reproducible evidence and risk assessment.
- **Certifications:** **CCDV-F, CCAR-F**; match current [official exam guide](https://anthropic-partners.skilljar.com/page/partner-certifications).
- **Completion:** pass simulated test or client defense; record learning gaps.

## Accenture Partner Academy mapping

**Official module or exam domain:** [Developer – Production Engineering, Evals & Security: tracing and budgets](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations). When a domain is shown rather than a course, follow the linked certification's authoritative exam guide.

**Certification mapping:** CCDV-F: Production engineering; CCAR-F: Reliability.

**Direct study references:**
1. [build-with-claude/prompt-caching](https://platform.claude.com/docs/en/build-with-claude/prompt-caching)
2. [docs/evaluation-harness.md](../docs/evaluation-harness.md)

## Daily five-hour schedule

| Time | What to study or build | Evidence |
|---|---|---|
| 0:00–1:30 | Study task cost, prompt caching, latency percentiles, error taxonomy, retries; study the mapped official module and links. | Notes, 5 recall questions |
| 1:30–3:00 | Implement: Correlate model turns, tool calls and sandbox decisions to eval outcomes. | Lab/code/architecture artifact |
| 3:00–4:30 | Reproduce closed-book, test negative outcomes and explain controls. | Tests and traces |
| 4:30–5:00 | Map to CCDV-F: Production engineering; CCAR-F: Reliability and record an English architecture explanation. | ADR and Git commit |

**Completion:** Read mapped official content; finish lab; pass positive/negative tests; state failure, cost and security trade-offs.

---

<a id="traditional-chinese"></a>

# Day 19 — Tracing、成本、可靠性與 FinOps

**2026-11-13 · 5 小時** · [首頁](../README.md)

## 公司官方課程、Section、Lab 與證書

- **打開：** [Developer: Production Engineering, Evals & Security](https://anthropic-partners.skilljar.com/page/claude-certification-exam-prep-courses)（公司信箱）。
- **指定 Section：** Tracing, cost, latency and regression evidence（官方課程內建議主題，非核實的內部 Lesson 標題）。
- **Lab：** Correlate model turns, tool calls and sandbox decisions to eval outcomes.，保留可重現的測試及風險證據。
- **對應證書：** **CCDV-F, CCAR-F**，以[官方 Exam Guide](https://anthropic-partners.skilljar.com/page/partner-certifications)為準。
- **驗收：** 完成測試或客戶情境答辯，記錄缺口。

## Accenture Partner Academy 指定內容

**官方課程模組或考綱：** [Developer – Production Engineering, Evals & Security: tracing and budgets](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations)。如果標註的是考綱領域而非課程，請以該官方認證頁面的 Exam Guide 為準。

**對應認證：** CCDV-F: Production engineering; CCAR-F: Reliability。

**當日直達文件：**
1. [build-with-claude/prompt-caching](https://platform.claude.com/docs/en/build-with-claude/prompt-caching)
2. [docs/evaluation-harness.md](../docs/evaluation-harness.md)

## 五小時每日實作安排

| 時段 | 今天具體學習與實作 | 證據 |
|---|---|---|
| 00:00–01:30 | 學習任務成本、Prompt Caching、延遲、錯誤分類與重試，完成對應官方模組和文件。 | 概念筆記、5 題自測 |
| 01:30–03:00 | 實作：關聯模型輪次、工具呼叫、Sandbox 決策與評估。 | 程式／架構成果 |
| 03:00–04:30 | 閉卷重做與反向測試，解釋安全控制。 | 測試與 Trace |
| 04:30–05:00 | 對照 CCDV-F: Production engineering; CCAR-F: Reliability 並完成英文架構解說。 | ADR、Git Commit |

**驗收：** 完成指定官方模組、實作並通過正反測試，能說明故障、成本與安全取捨。
