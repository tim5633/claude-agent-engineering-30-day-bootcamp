# Day 04 — Hooks, Permissions & Sandbox Foundations

**2026-10-29 · 5 hours** · [Home](../README.md) · [繁體中文 ↓](#traditional-chinese)

## Assigned lessons & direct learning links

**Partner Academy module:** [Claude Code, MCP & Integration — permissions and hooks](https://anthropic-partners.skilljar.com/claude-code-mcp-integration) (sign in using your company account; select the named topic).

1. [Claude Code hooks](https://code.claude.com/docs/en/hooks)
2. [Claude Code permissions](https://code.claude.com/docs/en/permissions)
3. [Claude Code sandboxing](https://code.claude.com/docs/en/sandboxing)

**Study topics:** Distinguish permission checks, hooks and OS sandbox boundaries.

**Required hands-on lab:** Create deny tests for sensitive files and prohibited commands.

**Validation:** Demonstrate the lab with automated checks and explain why these sources apply to today's implementation.

## Learning outcomes

Study Claude Code permission modes, PreToolUse/PostToolUse hooks, and how policy checks differ from OS-level isolation.

**Course material:** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) (authorized curriculum only), [Claude docs](https://docs.anthropic.com/). **Deep-dive reference:** [Hooks, Permissions & Sandbox Foundations](../docs/ai-sandbox-security.md).

## Daily 5-hour learning and implementation plan

| Time | Required action | Deliverable |
|---|---|---|
| 00:00–01:30 | Study Claude Code permission modes, PreToolUse/PostToolUse hooks, and how policy checks differ from OS-level isolation. | Concept notes + trust-boundary sketch |
| 01:30–03:00 | Configure project-specific tool allow/deny rules and a hook that blocks risky file operations. | Working implementation / design artifact |
| 03:00–04:30 | In a disposable sample workspace, test allowed edits and denied out-of-scope file reads; record whether the hook or sandbox blocked execution. | Unit / integration / security tests |
| 04:30–05:00 | Write a least-privilege policy and a boundary comparison table. | ADR + trace/eval evidence + English explanation |

## Definition of done

**Denied operations are blocked and logged by an actual policy or isolation boundary; authorized writes continue normally.**

- [ ] Relevant concepts and official reading completed
- [ ] Capstone implementation and positive/negative tests completed
- [ ] Evidence and architecture decision committed
- [ ] Explain trade-offs without step-by-step assistance

---

<a id="traditional-chinese"></a>

# Day 04 — Hooks、權限與 Sandbox 基礎

**2026-10-29 · 5 小時** · [首頁](../README.md)

## 今日指定教材與直達連結

**Partner Academy 課程：** [Claude Code, MCP & Integration — permissions and hooks](https://anthropic-partners.skilljar.com/claude-code-mcp-integration)（使用公司帳號登入，選擇上述主題）。

1. [Claude Code hooks](https://code.claude.com/docs/en/hooks)
2. [Claude Code permissions](https://code.claude.com/docs/en/permissions)
3. [Claude Code sandboxing](https://code.claude.com/docs/en/sandboxing)

**閱讀重點：** Identify permission checks, hooks and OS sandbox boundaries,Implement deny tests for sensitive files and disallowed commands。

**指定實作：** undefined。

## 今日能力目標

理解 Claude Code Permissions、PreToolUse／PostToolUse Hooks，以及它們與 OS Sandbox 的不同。

**指定教材：** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/)（依帳號內授權課程）、[Claude 官方文件](https://docs.anthropic.com/)；深入參考 [Hooks、權限與 Sandbox 基礎](../docs/ai-sandbox-security.md)。

## 每日五小時實作時間線

| 時段 | 指定學習／實作任務 | 產出 |
|---|---|---|
| 00:00–01:30 | 理解 Claude Code Permissions、PreToolUse／PostToolUse Hooks，以及它們與 OS Sandbox 的不同。 | 概念筆記與信任邊界圖 |
| 01:30–03:00 | 配置專案工具 Allow/Deny 規則與阻擋敏感檔案操作的 Hook。 | 可執行實作／架構交付 |
| 03:00–04:30 | 在一次性測試目錄驗證允許的編輯與跨範圍讀取遭拒；分辨由 Hook 還是 Sandbox 阻擋。 | 單元、整合與安全測試 |
| 04:30–05:00 | 整理最小權限規範與信任邊界比較表。 | ADR、Trace／Eval 證據及英文解說 |

## 驗收標準

**越權操作真正被策略或隔離層拒絕並留下記錄，正常授權寫入不受影響。**

- [ ] 完成課程、概念整理與閱讀
- [ ] 完成 Capstone 實作與正反測試
- [ ] 上傳可驗證成果、測試與技術取捨
- [ ] 不依賴逐步教學解釋整體設計
