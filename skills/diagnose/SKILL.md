---
name: diagnose
description: 面向棘手 bug 和性能回退的纪律化 diagnosis loop。Use when debugging bugs or regressions.
---

# Diagnose

1. 先建立可重复的 feedback loop。
2. 复现问题。
3. 列出多个可证伪 hypotheses。
4. 一次只验证一个变量。
5. 在正确 seam 上补 regression test。
6. 清理临时 instrumentation，并记录最终原因。
