# Capstone — Enterprise Financial Research & Workflow Agent

## Problem

使用者以自然語言詢問合成企業財務資料和公開文件。系統從授權的工具或文件擷取證據、計算數據、附上來源，產出可審查的報告。高風險操作須人工批准。

## Required features

- [ ] 使用者身分與 session 隔離
- [ ] 文件檢索與可追溯引用
- [ ] 輸入驗證的唯讀財務查詢工具（MCP）
- [ ] Claude API / Agent SDK agent loop
- [ ] 人工審核後才可匯出或觸發高風險動作
- [ ] 50+ evaluation cases 及可重跑的 regression
- [ ] Prompt injection / unauthorized access tests
- [ ] 追蹤 latency、tokens、API cost 與失敗分類
- [ ] Docker + automated tests + deployment runbook

## Acceptance targets (self-defined, not Anthropic guarantees)

- 所有未授權工具呼叫都必須被 deterministic policy 拒絕。
- 每一個分析結論的依據需可回溯至資料或工具結果。
- 每次程式變更可重跑既定資料集。
- 故障時有 timeout、retry policy、人工處理路徑。
- 完整展示單 Agent baseline 與 multi-agent 是否值得的決策。

## Suggested implementation

- `apps/web`: Next.js client（可選）
- `services/api`: FastAPI，服務端管理 secrets
- `agents`: SDK runtime and tool orchestration
- `mcp`: document + readonly finance tools
- `evals`: reference dataset、grading、regression reports

本 Repo 是**學習計畫**，不是已部署的產品或預製完成的 Agent 程式碼。
