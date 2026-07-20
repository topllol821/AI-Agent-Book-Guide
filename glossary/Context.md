# Context（上下文）

## 定義

每次呼叫 LLM 時送給模型的所有資訊，包括系統提示詞、工具定義、對話歷史、工具執行結果。

## 白話說法

Context 是 Agent 的「入職手冊」。你每次跟 Agent 說話，都要把這本手冊連同之前的對話記錄一起附上去。

## 與哪些概念容易混淆？

- **Prompt**：Prompt 只是 Context 的一部分（系統提示詞），Context 還包含工具定義和完整對話歷史
- **Memory**：Memory 是跨會話的長期儲存，Context 是單次請求的全部輸入
- **Knowledge Base**：知識庫是外部資料，Context 是本次請求中實際送給模型的內容

## 第一次出現在哪一章？

第 01 章（公式：Agent = LLM + Context + Tools）

第 02 章（完整討論）

## 建議閱讀章節

第 02 章

## 相關 GitHub

- [OpenAI Messages API](https://platform.openai.com/docs/api-reference/chat)
- [Anthropic Messages API](https://docs.anthropic.com/en/api/messages)
- [LangChain Context Management](https://github.com/langchain-ai/langchain)

## 延伸閱讀

- 原書第二章
- [Lost in the Middle (Liu et al., 2023)](https://arxiv.org/abs/2307.03172)
