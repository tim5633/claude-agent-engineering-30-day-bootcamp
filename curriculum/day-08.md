# Day 08 — Messages API & Model Engineering

**2026-11-02 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

## Company course / exact topic assignment / lab / exam

1. **Open:** [Developer: MSO Foundations](https://anthropic-partners.skilljar.com/page/claude-certification-exam-prep-courses) through corporate Partner Academy login.
2. **Study:** Messages API, SDK, tokens, rate limits, streaming (target subsection; verify gated lesson title in account).
3. **Build:** Write API client with timeouts, retries, token and cost tracking.; prove one failure or authorization boundary.
4. **Certification:** **CCDV-F**, using [official exam guides](https://anthropic-partners.skilljar.com/page/partner-certifications).
5. **Submit:** Code, evaluation/trace, Git commit, 5-minute recall quiz.

## Assigned Accenture / Anthropic Partner Academy courses

**Official Partner training:** [Developer: MSO Foundations (complete 57 min total); Production-Grade Prompting module (part 2)](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations). The course title is official; subsections in parentheses indicate which portion to focus on today, not separate certified course titles.

**Certification blueprint mapping:** CCDV-F: API/model fundamentals; CCAR-F: Prompt & Context.

**Read these exact references:**
1. [api/messages](https://platform.claude.com/docs/en/api/messages)
2. [en/home](https://platform.claude.com/docs/en/home)

## Daily schedule (5 hours)

| Time | Specific learning task | Evidence |
|---|---|---|
| 0:00–1:30 | Read Messages API schema, tokens, streaming, errors and SDK/REST decisions. Complete the corresponding named Partner course lesson and read linked docs. | Concept notes and 5 recall questions |
| 1:30–3:00 | Guided lab: Write API client with timeouts, retries, token and cost tracking. | Working feature / config |
| 3:00–4:30 | Closed-book: reproduce and extend the lab; add negative tests and failure handling. | Tests, traces, Git commit |
| 4:30–5:00 | Map takeaways to CCDV-F: API/model fundamentals; CCAR-F: Prompt & Context; explain trade-offs in English. | Exam domain notes + ADR |

## Passing criteria

- [ ] Completed today's named academy lesson(s) and official readings
- [ ] Built and tested the exact daily lab with at least one negative test
- [ ] Can explain the exam domain without notes or copied exam questions
- [ ] Committed results and recorded weaknesses

---

<a id="traditional-chinese"></a>

# Day 08 — Messages API 與模型工程

**2026-11-02 · 5 小時** · [首頁](../README.md)

## 公司課程／指定主題／Lab／認證

1. **打開：** [Developer: MSO Foundations](https://anthropic-partners.skilljar.com/page/claude-certification-exam-prep-courses)（公司 Partner Academy 登入）。
2. **指定 Section：** Messages API, SDK, tokens, rate limits, streaming（登入後核對課內標題）。
3. **Lab：** Write API client with timeouts, retries, token and cost tracking.，至少驗證一個失敗或越權案例。
4. **證書：** **CCDV-F**，依[正式考綱](https://anthropic-partners.skilljar.com/page/partner-certifications)。
5. **成果：** Code、Evaluation／Trace、Commit、5 分鐘自測。

## 公司 Anthropic Partner Academy 指定課程

**官方課程：** [Developer: MSO Foundations (complete 57 min total); Production-Grade Prompting module (part 2)](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations)。括號中的「part」是今天的建議閱讀範圍，不是額外捏造的官方課程名稱。

**對應認證考綱：** CCDV-F: API/model fundamentals; CCAR-F: Prompt & Context。

**指定文件直達連結：**
1. [api/messages](https://platform.claude.com/docs/en/api/messages)
2. [en/home](https://platform.claude.com/docs/en/home)

## 每天五小時詳細安排

| 時段 | 必學／必做內容 | 當日交付 |
|---|---|---|
| 00:00–01:30 | 理解 Messages API 格式、Token、Streaming、錯誤處理與 SDK/REST 取捨。完成當日公司課程與官方文件。 | 概念筆記＋5 題自我測驗 |
| 01:30–03:00 | 實作：建立具有 Timeout、Retry、Token 及成本追蹤的 API Client。 | 可執行功能／設定 |
| 03:00–04:30 | 不看教程自行重做與擴充，並加入至少一個負面／故障測試。 | 測試、Trace、Commit |
| 04:30–05:00 | 把知識對回 CCDV-F: API/model fundamentals; CCAR-F: Prompt & Context，英文解釋技術取捨。 | 考綱筆記與 ADR |

## 驗收

- [ ] 完成公司指定課程與連結文件
- [ ] 完成每日實作並測試失敗情境
- [ ] 不看筆記也能解釋對應考試領域
- [ ] 提交 Git Commit 與學習缺口記錄
