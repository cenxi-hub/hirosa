---
name: tdd
description: 使用 red-green-refactor loop 做 test-driven development。Use when user wants test-first development.
---

# Test-Driven Development

- 通过 public interface 测试 behavior，而不是 implementation details。
- 一次只写一个 failing test。
- 只写足够让当前 test 通过的代码。
- 全部变绿后再 refactor。
- 优先 vertical slices，不要先批量写完所有 tests。
