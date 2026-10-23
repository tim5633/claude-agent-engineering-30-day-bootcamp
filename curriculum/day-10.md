# Day 10 — Bounded Tool Loop & Agent Harness

**2026-11-04 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

## Assigned Accenture / Anthropic Partner Academy courses

**Official Partner training:** [Developer: Production-Grade Prompting, Agents & Tool Use (tool loop, agent)](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations). The course title is official; subsections in parentheses indicate which portion to focus on today, not separate certified course titles.

**Certification blueprint mapping:** CCDV-F: tools and agents; CCAR-F: Agentic Architecture (27%), Tools (18%).

**Read these exact references:**
1. [tool-use/how-tool-use-works](https://platform.claude.com/docs/en/agents-and-tools/tool-use/how-tool-use-works)
2. [docs/agent-harness-engineering.md](../docs/agent-harness-engineering.md)

## Daily schedule (5 hours)

| Time | Specific learning task | Evidence |
|---|---|---|
| 0:00–1:30 | Implement model request→tool execution→result→model loop with bounded control. Complete the corresponding named Partner course lesson and read linked docs. | Concept notes and 5 recall questions |
| 1:30–3:00 | Guided lab: Create allowlisted tools, JSON schema validation, max_steps and cost limits. | Working feature / config |
| 3:00–4:30 | Closed-book: reproduce and extend the lab; add negative tests and failure handling. | Tests, traces, Git commit |
| 4:30–5:00 | Map takeaways to CCDV-F: tools and agents; CCAR-F: Agentic Architecture (27%), Tools (18%); explain trade-offs in English. | Exam domain notes + ADR |

## Passing criteria

- [ ] Completed today's named academy lesson(s) and official readings
- [ ] Built and tested the exact daily lab with at least one negative test
- [ ] Can explain the exam domain without notes or copied exam questions
- [ ] Committed results and recorded weaknesses

---

<a id="traditional-chinese"></a>

# Day 10 — Tool Calling 與有界 Agent Harness

**2026-11-04 · 5 小時** · [首頁](../README.md)

## 公司 Anthropic Partner Academy 指定課程

**官方課程：** [Developer: Production-Grade Prompting, Agents & Tool Use (tool loop, agent)](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations)。括號中的「part」是今天的建議閱讀範圍，不是額外捏造的官方課程名稱。

**對應認證考綱：** CCDV-F: tools and agents; CCAR-F: Agentic Architecture (27%), Tools (18%)。

**指定文件直達連結：**
1. [tool-use/how-tool-use-works](https://platform.claude.com/docs/en/agents-and-tools/tool-use/how-tool-use-works)
2. [docs/agent-harness-engineering.md](../docs/agent-harness-engineering.md)

## 每天五小時詳細安排

| 時段 | 必學／必做內容 | 當日交付 |
|---|---|---|
| 00:00–01:30 | 實作模型→工具執行→結果→模型的有界執行迴圈。完成當日公司課程與官方文件。 | 概念筆記＋5 題自我測驗 |
| 01:30–03:00 | 實作：建立工具白名單、Schema 驗證、最大步數與成本上限。 | 可執行功能／設定 |
| 03:00–04:30 | 不看教程自行重做與擴充，並加入至少一個負面／故障測試。 | 測試、Trace、Commit |
| 04:30–05:00 | 把知識對回 CCDV-F: tools and agents; CCAR-F: Agentic Architecture (27%), Tools (18%)，英文解釋技術取捨。 | 考綱筆記與 ADR |

## 驗收

- [ ] 完成公司指定課程與連結文件
- [ ] 完成每日實作並測試失敗情境
- [ ] 不看筆記也能解釋對應考試領域
- [ ] 提交 Git Commit 與學習缺口記錄
