# AI Sandbox & Secure Execution｜隔離執行環境與安全邊界

[README](../README.md) · [Harness](agent-harness-engineering.md) · [Evals](evaluation-harness.md)

## Core concept

**Harness controls the workflow; Sandbox restricts the execution environment.** Prompt rules or permission prompts alone are not OS isolation. Defense in depth: sandboxing + tool permissions + network policies + credential isolation + human approval.

## Study map

| Area | Concepts | Lab |
|---|---|---|
| Threat modeling | Prompt injection, malicious repositories, untrusted documents | Design attacker/defender scenarios |
| Filesystem isolation | Read-only mounts, workspace allowlist, ephemeral storage | Deny attempts to read outside workspace |
| Process isolation | Non-root users, Linux namespaces, container/VM trade-offs | Containerize untrusted test command |
| Network egress | Default deny, allowlisted hosts, SSRF, metadata endpoints | Deny unauthorized outbound connections |
| Secrets | Credential broker, scoped tokens, short-lived credentials | Verify secrets are not exposed to tools/logs |
| Resource limits | CPU, memory, time, storage, process limits | Terminate runaway processes safely |
| Tool authorization | Per-tool ACL, input validation, approval | Deny unauthorized SQL writes |
| Browser/computer use | Dedicated container per session, URL policy, upload/download constraints | Simulate hostile webpage instructions |
| Auditability | Immutable-ish trace, retention and data minimization | Record denied and approved tool calls |

## Practical labs — ~10 hours (integrated into Days 04, 06, 12, 17, 20, 29)

1. Compare **Claude Code /sandbox**, Claude API's hosted code-execution tool, Claude Managed Agents' environment sandbox, and a self-hosted container. These have **different boundaries**; do not treat them as equivalent.
2. Create a **throwaway local sandbox** using a deliberately non-privileged container, limited filesystem mounts, memory/CPU/time limits and disabled networking for tests that need no network. Do not mount host secrets, the Docker socket, or production credentials.
3. Write tests where an agent attempts disallowed file reads, unauthorized tool calls, arbitrary outbound requests and retrieval of masked secrets. Confirm denial at the environment boundary, not only at prompt level.
4. Implement an explicit approval step for consequential actions and correlate each decision to an audit trail.
5. Separate trusted tool descriptions from untrusted web pages, files and tool outputs. Add prompt-injection regression cases.

## Security gate

- [ ] Tool policies implement least privilege
- [ ] Isolation boundaries and trust assumptions documented
- [ ] No secrets in prompts, logs, Git history or execution containers unless explicitly needed
- [ ] Egress restrictions verified through tests
- [ ] Runaway task has bounded resource use and termination
- [ ] All externally consequential actions require appropriate authorization
- [ ] Sandbox escape risk and residual risk documented; no claim of perfect security

## Official documentation

- [Claude Code sandboxing](https://code.claude.com/docs/en/sandboxing)
- [Managed Agents: security risks and sandbox boundaries](https://platform.claude.com/docs/en/managed-agents/secure-deployment-risks)
- [Claude API code execution tool](https://platform.claude.com/docs/en/agents-and-tools/tool-use/code-execution-tool)
- [Browser and computer use security](https://platform.claude.com/docs/en/agents-and-tools/tool-use/browser-use-sdk)

> Safety-first labs only. Never test against networks, data or services without authorization.
