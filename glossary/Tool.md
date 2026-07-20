# Tool / Tool Calling（工具／工具呼叫）

## 定義

Agent 用來與外部世界互動的功能介面，包括感知（搜尋、讀檔）和執行（寫檔、發郵件、執行程式碼）。Tool Calling 是 LLM 決定使用哪個工具並產生呼叫請求的過程。

## 白話說法

工具就是 Agent 的手腳。LLM 只能思考不能做事，工具讓它能去搜尋資料、操作電腦、改變世界。Tool Calling 就是 LLM 說「我要用這個工具」——實際執行是 Agent 框架做的。

## 與哪些概念容易混淆？

- **Function Calling**：同義詞。OpenAI 用 Function Calling 這個名稱，但做的事跟 Tool Calling 一樣。
- **MCP**：MCP 是工具的標準化通訊協定，不是工具本身。MCP 定義工具怎麼寫、怎麼傳、怎麼叫。
- **Plugin**：Plugin 偏向人類使用的介面（有 UI），Tool 是純為 LLM 設計的介面（只有結構化參數）。
- **Workflow**：Workflow 是固定步驟，Tool 是 Agent 動態選擇呼叫的功能單位。

## 第一次出現在哪一章？

第 01 章（公式中的 Tools）

第 04 章（完整討論）

## 建議閱讀章節

第 04 章

第 05 章（Coding Agent 的工具集）

## 相關 GitHub

- [MCP Specification](https://github.com/modelcontextprotocol/specification)
- [OpenAI Function Calling](https://platform.openai.com/docs/guides/function-calling)
- [Anthropic Tool Use](https://docs.anthropic.com/en/docs/build-with-claude/tool-use)
- [Claude Code](https://github.com/anthropics/claude-code)

## 延伸閱讀

- 原書第四章
- [Model Context Protocol 官方文件](https://modelcontextprotocol.io)
