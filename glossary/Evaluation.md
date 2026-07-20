# Evaluation（評估）

## 定義

衡量 Agent 系統表現的方法與流程，包含測試用例、評分標準（Rubric）、自動化評分機制。核心目的是輔助決策（該不該換模型、改 Prompt），而非單純打分。

## 白話說法

就像學生的考試——你需要同樣的題目、同樣的評分標準、同樣的考試環境，才能知道學生真的進步了還是只是運氣好。評估不是為了考倒 Agent，是為了幫你做決定。

## 與哪些概念容易混淆？

- **Benchmark**：Benchmark 是公開的標準化考試（如 SWE-Bench），Evaluation 是針對你自己任務的評量
- **Monitoring**：Monitoring 是在生產環境中觀察即時狀況，Evaluation 是在測試環境中評量表現
- **Ablation**：Ablation 是關掉某個組件看影響，是 Evaluation 的一種手法
- **Pass@k vs Pass^k**：前者測能力上限（k 次中至少 1 次對），後者測穩定度（k 次全部對）

## 第一次出現在哪一章？

第 01 章（強調評估的重要性）

第 06 章（完整討論）

## 建議閱讀章節

第 06 章

## 相關 GitHub

- [LangSmith](https://github.com/langchain-ai/langsmith)
- [OpenAI Evals](https://github.com/openai/evals)
- [Anthropic Evaluation](https://docs.anthropic.com/en/docs/evaluation)

## 延伸閱讀

- 原書第六章
- [Anthropic 評估指南](https://docs.anthropic.com/en/docs/evaluation)
