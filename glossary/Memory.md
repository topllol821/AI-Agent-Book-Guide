# Memory（記憶）

## 定義

Agent 跨會話保留的使用者個人化資訊，如偏好、習慣、歷史記錄。屬於使用者層級的長期儲存，與知識庫（共享知識）相對。

## 白話說法

就像你的助理有一本筆記本，記錄你喜歡靠窗座位、不吃牛肉、會員編號是多少。下次你找它，它不用重新問你。這就是「記憶」——針對你個人的。

## 與哪些概念容易混淆？

- **Knowledge Base**：記憶是針對個人的，知識庫是全體使用者共享的。你的飲食偏好不該影響其他使用者的推薦。
- **Context**：記憶需要被載入 Context 才能使用，但兩者是不同的層級——記憶是持久儲存，Context 是單次請求的輸入。
- **RAG**：RAG 是從知識庫檢索資訊的技術，記憶通常用更簡單的結構（如 JSON）直接儲存和讀取。

## 第一次出現在哪一章？

第 03 章

## 建議閱讀章節

第 03 章（核心）

第 09 章（自我進化中的記憶整合）

## 相關 GitHub

- [Mem0](https://github.com/mem0ai/mem0)
- [LangChain Memory](https://github.com/langchain-ai/langchain)
- [OpenAI Memory API](https://platform.openai.com)

## 延伸閱讀

- 原書第三章
- [Building Effective AI Agents (Anthropic)](https://docs.anthropic.com/en/docs/build-with-claude/agent)
