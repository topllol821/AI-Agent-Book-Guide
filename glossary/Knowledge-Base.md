# Knowledge Base（知識庫）

## 定義

所有使用者共享的集體知識，通常透過 RAG（檢索增強生成）在需要時檢索相關片段，作為 Context 的一部分送給模型。與記憶（個人化）相對。

## 白話說法

就像公司的員工手冊——裡面有退貨政策、客服流程、產品規格。任何 Agent 都可以翻閱這本手冊來回答問題。但它不是你個人的筆記本，是所有人都能查的。

## 與哪些概念容易混淆？

- **Memory**：記憶是個人化的（「你喜歡什麼」），知識庫是共用的（「世界長怎樣」）。
- **RAG**：RAG 是從知識庫檢索資訊的技術，不是知識庫本身。就像「翻書的動作」跟「書」的差別。
- **Context**：知識庫的檢索結果會被載入 Context，但知識庫本身是持久儲存。Context 是單次請求的暫存。
- **Fine-tuning**：Fine-tuning 是把知識寫進模型權重，RAG 是把知識當作 Context。RAG 更靈活、更新更方便。

## 第一次出現在哪一章？

第 03 章

## 建議閱讀章節

第 03 章（核心）

第 06 章（評估 RAG 效果）

## 相關 GitHub

- [LangChain RAG](https://github.com/langchain-ai/langchain)
- [LlamaIndex](https://github.com/run-llama/llama_index)
- [Chroma](https://github.com/chroma-core/chroma)

## 延伸閱讀

- 原書第三章
- [OpenAI RAG Guide](https://platform.openai.com/docs/guides/rag)
- [Anthropic Contextual Retrieval](https://www.anthropic.com/news/contextual-retrieval)
