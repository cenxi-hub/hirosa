---
name: to-issues
description: 使用 tracer-bullet vertical slices，把 plan、spec 或 PRD 拆成项目 issue tracker 上可独立领取的 issues。Use when user wants to convert a plan into issues, create implementation tickets, or break down work into issues.
---

# To Issues

使用 vertical slices（tracer bullets）把计划拆成可独立领取的 issue tracker issues。

Issue tracker 和 triage label vocabulary 应该已经提供给你；如果没有，运行 `/setup-matt-pocock-skills`。

## Process

1. 基于已有 conversation context 工作；必要时读取 parent issue。
2. 先理解 codebase，再起草 vertical slices。
3. 每个 slice 都应是薄而完整的 end-to-end 路径，而不是单层的 horizontal slice。
4. 先向用户展示拆分，再发布到 issue tracker。
