# Review 03 — Content Review for Chapter 5 & Chapter 6 + Chapter 3 & 4 micro-fixes

## 本次完成內容

### 微調 Chapter 3
- 將「作者真正想表達什麼」從名詞介紹改為問題驅動結構：LLM 限制 → Prompt 不夠 → 需要 KB → 需要 RAG → 需要 Memory
- 新增「人的大腦」比喻（長期記憶→Memory、書櫃→KB、圖書館查資料→RAG）
- 新增 Memory / Knowledge Base / RAG 三方對照表

### 微調 Chapter 4
- 在「作者真正想表達什麼」開頭新增核心觀念：「Tool Calling 不是讓 AI 變得更聰明，而是讓 AI 擁有真正的手腳」
- 同步更新「一句話記住」

### 完成 Chapter 5 — Coding Agent
- 概念誕生故事：Code Generation → Inline Completion → Coding Agent 三代演進
- 回答「為什麼 AI 需要會寫程式」（元能力觀點）
- 七個核心工具對照表
- 4 個案例（生活/企業/AI/軟體開發）
- 為何 Coding Agent 是最成熟的 Agent 類型（可驗證性最高）

### 完成 Chapter 6 — Evaluation
- 概念誕生故事：Prompt 測試過關但上線失敗 → 人工測試太慢 → 自動化評估
- 回答「為什麼 Prompt 看起來很好上線卻失敗」
- Pass@k vs Pass^k 詳細對照
- Rubric 四個準則
- LLM-as-a-Judge 實務與偏見
- 4 個案例（生活/企業/AI/決策）

## 新增永久寫作規則

從 Chapter 5 開始，每個重要概念都加入「概念誕生故事」：
- 以前怎麼做？
- 遇到什麼問題？
- 因此出現新的方法
- 新的方法又有哪些限制？
- 現在大家怎麼做？

## 自我檢查

| 檢查項 | 狀態 |
|--------|------|
| 是否容易閱讀？ | ✅ 各章開頭從日常生活經驗切入 |
| 是否問題導向？ | ✅ Ch3 改為問題驅動結構、Ch5/6 有完整概念誕生故事 |
| 是否有大量案例？ | ✅ 每章 4 個案例，涵蓋生活/企業/AI/軟體開發/決策 |
| 是否有比較表？ | ✅ Ch3 三方對照、Ch5 七工具表、Ch6 Pass@k vs Pass^k |
| 是否有一句話重點？ | ✅ |
| 是否加入概念誕生故事？ | ✅ Ch5 三代演進、Ch6 三階段故事 |
| 是否補充目前業界最佳實務？ | ✅ Ch6 Anthropic/OpenAI 評估工具補充 |

## 建議 ChatGPT Review 時特別注意

1. **Chapter 5「三代演進」**：時間點和技術演進的描述是否準確？Code Generation 到 Coding Agent 的分法是否合理？

2. **Chapter 6「評估的目的」**：把評估定位為「決策工具」而非「打分數」，這個角度是否清楚傳達？

3. **概念誕生故事的長度**：每個故事的長度是否適中？會不會太長讓讀者失去耐心？

4. **術語一致性**：Ch3-6 之間的術語（Context、Tool Calling、RAG 等）是否與前四章一致？

5. **Ch3 改寫後的前後連貫**：問題驅動結構是否流暢？「人的大腦比喻」是否突兀？

6. **Ch4 核心觀念位置**：「Tool Calling 不是讓 AI 變聰明」這個觀念是否在足夠顯眼的位置？
