# 每日评论聚合分类

> 拉取当日评论→提问/赞美/吐槽/黑粉四分→优先级排序

工作流 `wf-creator-comment-aggregate`　·　归属 评论区运营官　·　触发 定时（每日 21:00）　·　
复杂度 M　·　阶段 P0

## 调用链

- `评论情绪识别`（review-sentiment-tag）

## 文档

- [`WORKFLOW.md`](WORKFLOW.md) — 完整编排、闸门、降级与验收标准
- [`tests/cases.yaml`](tests/cases.yaml) — 端到端 / 闸门 / 降级用例

## 一句话试用

```text
帮我跑 评论区运营官 的「每日评论聚合分类」：<你的输入>
```
