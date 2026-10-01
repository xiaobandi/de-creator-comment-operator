# 高频问题提取→转选题

> 提问类评论聚类→高频问题榜→查重后写入选题库

工作流 `wf-creator-comment-qa-to-topic`　·　归属 评论区运营官　·　触发 事件（WF1 后自动）　·　
复杂度 M　·　阶段 P0

## 调用链

- `高频问题聚类`（faq-clustering）
- `选题知识库管理`（topic-kb-manage）
- `选题查重`（topic-duplicate-check）

## 文档

- [`WORKFLOW.md`](WORKFLOW.md) — 完整编排、闸门、降级与验收标准
- [`tests/cases.yaml`](tests/cases.yaml) — 端到端 / 闸门 / 降级用例

## 一句话试用

```text
帮我跑 评论区运营官 的「高频问题提取→转选题」：<你的输入>
```
