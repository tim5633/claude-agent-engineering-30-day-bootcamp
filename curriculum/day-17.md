# Day 17 — Governance, Safety & Sandbox Isolation

**2026-11-11 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

## Open course → assigned section → lab → credential

- **Official company learning:** [Associate: Governance, Risk & Responsible Use; Developer: Production Security](https://anthropic-partners.skilljar.com/page/claude-certification-exam-prep-courses).
- **Section/topic:** Sandbox boundaries, least privilege and prompt injection. Focus selected for this day; gated lesson headings should be checked in your logged-in course.
- **Hands-on lab:** Test blocked file/network access in disposable sandbox with synthetic fixtures. plus negative/security test.
- **Exam:** **CCAO-F, CCDV-F, CCAR-P** ([official guide](https://anthropic-partners.skilljar.com/page/partner-certifications)).
- **Pass:** demonstrate implementation, tests, trace and architecture trade-off.

## Accenture Partner Academy mapping

**Official module or exam domain:** [Associate – Governance, Risk & Responsible Use (55 min); Developer – Production Engineering, Evals & Security](https://anthropic-partners.skilljar.com/path/claude-certified-associate-foundations). When a domain is shown rather than a course, follow the linked certification's authoritative exam guide.

**Certification mapping:** CCAO-F: Governance, Risk & Responsible Use (15%); CCDV-F: Security.

**Direct study references:**
1. [en/sandboxing](https://code.claude.com/docs/en/sandboxing)
2. [docs/ai-sandbox-security.md](../docs/ai-sandbox-security.md)

## Daily five-hour schedule

| Time | What to study or build | Evidence |
|---|---|---|
| 0:00–1:30 | Study data classification, prompt injection, untrusted tools, network egress and container isolation; study the mapped official module and links. | Notes, 5 recall questions |
| 1:30–3:00 | Implement: Test blocked file/network access in disposable sandbox with synthetic fixtures. | Lab/code/architecture artifact |
| 3:00–4:30 | Reproduce closed-book, test negative outcomes and explain controls. | Tests and traces |
| 4:30–5:00 | Map to CCAO-F: Governance, Risk & Responsible Use (15%); CCDV-F: Security and record an English architecture explanation. | ADR and Git commit |

**Completion:** Read mapped official content; finish lab; pass positive/negative tests; state failure, cost and security trade-offs.

---

<a id="traditional-chinese"></a>

# Day 17 — 治理、安全與 Sandbox 隔離

**2026-11-11 · 5 小時** · [首頁](../README.md)

## 每日課程 → Section → 實作 → 認證

- **公司官方課程：** [Associate: Governance, Risk & Responsible Use; Developer: Production Security](https://anthropic-partners.skilljar.com/page/claude-certification-exam-prep-courses)。
- **Section：** Sandbox boundaries, least privilege and prompt injection（指定主題，登入確認實際 Lesson 名稱）。
- **Lab：** Test blocked file/network access in disposable sandbox with synthetic fixtures.，加入越權／失敗測試。
- **認證：** **CCAO-F, CCDV-F, CCAR-P**（[官方考綱](https://anthropic-partners.skilljar.com/page/partner-certifications)）。
- **驗收：** 實作、測試、Trace 與架構取捨。

## Accenture Partner Academy 指定內容

**官方課程模組或考綱：** [Associate – Governance, Risk & Responsible Use (55 min); Developer – Production Engineering, Evals & Security](https://anthropic-partners.skilljar.com/path/claude-certified-associate-foundations)。如果標註的是考綱領域而非課程，請以該官方認證頁面的 Exam Guide 為準。

**對應認證：** CCAO-F: Governance, Risk & Responsible Use (15%); CCDV-F: Security。

**當日直達文件：**
1. [en/sandboxing](https://code.claude.com/docs/en/sandboxing)
2. [docs/ai-sandbox-security.md](../docs/ai-sandbox-security.md)

## 五小時每日實作安排

| 時段 | 今天具體學習與實作 | 證據 |
|---|---|---|
| 00:00–01:30 | 學習資料分類、Prompt Injection、不可信工具、網路出口與容器隔離，完成對應官方模組和文件。 | 概念筆記、5 題自測 |
| 01:30–03:00 | 實作：在一次性 Sandbox 測試阻擋檔案與網路越權。 | 程式／架構成果 |
| 03:00–04:30 | 閉卷重做與反向測試，解釋安全控制。 | 測試與 Trace |
| 04:30–05:00 | 對照 CCAO-F: Governance, Risk & Responsible Use (15%); CCDV-F: Security 並完成英文架構解說。 | ADR、Git Commit |

**驗收：** 完成指定官方模組、實作並通過正反測試，能說明故障、成本與安全取捨。
