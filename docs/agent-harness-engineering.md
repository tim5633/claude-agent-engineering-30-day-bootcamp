# Agent Harness Engineering

[README](../README.md) · [Sandbox](ai-sandbox-security.md) · [Eval Harness](evaluation-harness.md)

## What is an Agent Harness?

The model reasons about next steps; the harness manages sessions, context, routing, permissions, retries, termination and persistence. Distinguish these components:

- **Claude model:** reasoning + tool requests
- **Agent harness:** run loop, tool dispatch, budgets, policies, traces
- **Claude Agent SDK:** libraries and capabilities to implement or use a harness
- **MCP:** tool integration protocol, not a security boundary
- **Sandbox:** isolated runtime in which selected tools/code run
- **Eval harness:** reproducible environment + graders + reporting

## Architecture

```mermaid
flowchart TD
 USER[Task] --> SESSION[Session and context]
 SESSION --> LOOP[Harness: bounded agent loop]
 LOOP --> MODEL[Claude API]
 MODEL --> POLICY[Tool policy and approval]
 POLICY --> TOOL[Tool dispatcher / MCP]
 TOOL --> BOX[Sandbox runtime]
 BOX --> OBS[Tool result / trace]
 OBS --> LOOP
 LOOP --> STOP[Answer / checkpoint / stop]
```

## Labs — ~10 hours (integrated into Day 10, 11, 15, 16, 19)

1. **Loop from scratch:** implement max_steps and max_cost_usd controls; allowlist tools and validate schemas; defend against malformed model tool requests.
2. **Session manager:** persisted sessions, summarization, checkpoint and resume across process restarts; never blindly rerun consequential tools.
3. **Reliable execution:** timeouts, cancellation, retries with exponential backoff, idempotency keys and deterministic stopping.
4. **Comparative architecture:** hand-written Messages API harness vs Claude Agent SDK vs managed runtime; measure time, cost and failure rate.
5. **Observability:** emit trace IDs, model/tool events, permissions decisions, task outcomes and tokens.

## Harness acceptance tests

- [ ] Infinite-loop prevention; max-step, max-time and max-spend policies
- [ ] Denied tool call cannot be run by a fallback path
- [ ] Interrupted session resumes without repeating a high-risk action
- [ ] Tool errors and malformed outputs are handled predictably
- [ ] Trace links model actions to tool effects and final outcomes
- [ ] Evaluate single-agent vs multi-agent only where data supports added complexity

## Official references

- [Effective harnesses for long-running agents](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents)
- [Scaling Managed Agents](https://www.anthropic.com/research/managed-agents)
- [Claude Agent SDK](https://platform.claude.com/docs/en/agent-sdk/overview)

> Always follow the current documentation and do not embed Partner Academy copyrighted course contents.

---

<a id="traditional-chinese"></a>

# Agent Harness Engineering｜代理執行框架

Harness 負責 Agent Loop、Context、工具路由、Session、Checkpoint、預算限制、重試、停止與追蹤；模型負責推理，Sandbox 限制實際執行權限，Evaluation Harness 驗證成果。

實作：從零建立有次數、時間及成本上限的工具循環；實作狀態保存、當機恢復、冪等性、工具授權和 Trace；比較手寫 Claude API Harness 與 Agent SDK。

驗收：無限循環被限制、拒絕工具無法繞過、中斷後不重複高風險動作、錯誤能恢復且有完整追蹤。
