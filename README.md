# DIC3 · AI Fitness Coach

**以對話為入口的智慧慢跑教練系統**｜物聯網應用與資料分析期末專題

本專題提出一個整合運動、天氣、路線與飲食資訊的 AI 慢跑教練。使用者可透過文字或語音描述可用時間、地點、身體狀況與飲食限制，由系統查詢相關資訊並提供符合當下情境的運動與飲食建議。

## 三項核心設計

1. **文字與語音互動**：以 Vanilla JavaScript 提供對話介面，支援語音回覆與虛擬教練口型同步。
2. **情境式工具查詢**：由 FastAPI 整合 CyborAgent 與 CyborAssistant，結合天氣、路線及營養工具，支援慢跑規劃與飲食建議。
3. **免費優先的部署與用量控制**：以 Vercel 與 Supabase 為部署架構，透過 ScopeGuard 限定代理人任務範圍，並設定模型和工具呼叫預算。

## 評估規劃

端到端情境涵蓋對話、天氣與路線查詢、運動紀錄、飲食建議及口型同步。提案列出頁面查詢 P95 低於 2 秒、語音回覆 P95 低於 12 秒的效能目標。

## 專題資料

| 文件 | 內容 |
| --- | --- |
| [專題簡報](myplan/AI-Fitness-Coach-slides.pdf) | 研究動機、系統架構與驗證規劃 |
| [完整提案](myplan/proposal.pdf) | 依 A–Z 架構撰寫的研究提案 |
| [提案解析](myplan/proposal-analysis.pdf) | 對照課程規範的符合度與待補項目 |
| [A–Z 大綱範例](myplan/A2Z-outline-example.pdf) | 提案撰寫模板 |
| [期末專題提案作業規範](myplan/final-project-proposal-requirements.pdf) | 課程要求與評分項目 |
