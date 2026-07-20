# Changelog

## v0.8 — 技術正確性修正（Review-06）

- **Ch1**: Workflow/Agent 比較修正、新增付款確認原則、新增不可逆操作安全原則
- **Ch2**: 移除無來源的 Persistent Contexts/Stateful API 說法；回寫狀態管理說明；KV Cache 三條鐵律→Prompt Cache 實務原則；時間戳案例改為示意情境
- **Ch3**: 擴充 Memory/KB/RAG 定義（記憶不限個人偏好、KB 不限共享、RAG 不限向量搜尋）；修正 Deep Research 案例
- **Ch4**: MCP 定位修正（tools/resources/prompts 協定）；Sidecar 改為可選設計；新增安全順序六大原則
- **Ch5**: 「七個核心工具」→「一組常見工具集合」；修正測試通過的說法；修正對非工程師的論述；移除 Terminal-Bench 無來源數字；移除 Sessionless 名詞
- **Ch6**: Testing vs Evaluation 改為非互斥；Pass@k 範例加入獨立性備註；換模型案例改為示意情境
- **Ch7**: 移除 15 倍成本固定數字；擴充多 Agent 價值來源（平行探索/Context 隔離/專業分工）
- **Ch8**: 新增受控閉環與安全提醒；移除 Anthropic 生產環境無來源宣稱；案例改為示意情境
- **Ch9**: GPT-4.1 改為 Realtime API；移除無來源延遲數字（全雙工 <0.2s、VLA 數十毫秒）；公司策略表弱化為快速變化說明
- **Ch10**: 移除「SFT 記憶，RL 泛化」；修正 DPO 流程說明；修正 Constitutional AI 說明
- **全書**: README 演進敘事修正（Context→Memory→Tools）；新增 glossary/RAG.md；Harness 中文名修正；移除失效的 OpenClaw 連結

## v0.4 — Chapter 3 & Chapter 4

- 完成 Chapter 3：記憶與知識庫（Memory、Knowledge Base、RAG 完整說明）
- 完成 Chapter 4：工具（Tool Calling、Function Calling、MCP、安全機制）
- 更新 `glossary/Memory.md`、`glossary/Knowledge-Base.md`、`glossary/Tool.md`
- 建立 `review/review-02.md` 自評記錄

## v0.3 — 架構定版

- 建立 `glossary/` 目錄，含 10 個核心名詞條目
- 建立 `STYLE_GUIDE.md` 寫作規範
- 建立 `CHANGELOG.md`
- 更新 `README.md` 加入 Repository 結構說明
- 更新 `SUMMARY.md` 加入 glossary 入口
- 專案架構正式定版

## v0.2 — Review 01

- 章節順序調整（07↔09，10 改為延伸閱讀）
- 新增每章三區塊：一句話記住、相關工具/GitHub、延伸閱讀
- 建立 `review/review-01.md`
- README 新增 Review-Driven Development 流程說明
- 所有交叉連結修正

## v0.1 — 初始版本

- 建立 GitHub Repository
- 建立目錄結構：`book/` `images/` `references/`
- 建立 `README.md` `SUMMARY.md`
- 完成 Chapter 1、Chapter 2
- 建立 Chapter 3-10 佔位檔案
