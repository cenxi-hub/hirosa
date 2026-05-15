---
name: to-prd
description: 将当前 conversation context 转成 PRD 并发布到项目 issue tracker。Use when user wants to create a PRD from the current context.
---

这个 skill 使用当前 conversation context 和 codebase understanding 产出 PRD。**不要**访谈用户，只综合你已经知道的内容。

Issue tracker 和 triage label vocabulary 应该已经提供给你；如果没有，运行 `/setup-matt-pocock-skills`。

## Process

1. 如果还没有探索 repo，先探索它以理解 codebase 当前状态。在 PRD 中始终使用项目 domain glossary vocabulary，并遵守相关 ADRs。
2. 草拟完成 implementation 需要 build 或 modify 的主要 modules。主动寻找可以抽出 deep modules 并独立测试的机会。
3. 使用模板写 PRD，并发布到项目 issue tracker。应用 `ready-for-agent` triage label；不需要额外 triage。
