# Tool / Tool Calling（工具／工具呼叫）

## 定義

Agent 用來與外部世界互動的功能介面，包括感知（搜尋、讀檔）和執行（寫檔、發郵件、執行程式碼）。

## 白話說法

工具就是 Agent 的手腳。LLM 只能思考不能做事，工具讓它能去搜尋資料、操作電腦、改變世界。

## 與哪些概念容易混淆？

- **Function Calling**：同義詞，模型決定呼叫哪個函式的過程
- **MCP**：MCP 是工具的標準化通訊協定，不是工具本身
- **Plugin**：Plugin 偏向人類使用的介面，Tool 是為模型設計的

## 第一次出現在哪一章？

第 01 章（公式中的 Tools）

第 04 章（完整討論）

## 建議閱讀章節

第 04 章

第 05 章（Coding Agent 的工具集）

## 相關 GitHub

- [MCP Specification](https://github.com/modelcontextprotocol/specification)
- [OpenAI Function Calling](https://platform.openai.com/docs/guides/function-calling)

## 延伸閱讀

- 原書第四章
