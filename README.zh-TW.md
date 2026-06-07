# 🎯 AI Project Blueprint — AI 專案藍圖

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![AI Agent](https://img.shields.io/badge/AI-Agent%20Ready-blue)](https://github.com/lunkerchen/ai-project-blueprint-skill)
[![Hermes](https://img.shields.io/badge/Hermes-Skill-orange)](https://hermes-agent.nousresearch.com)
[![Claude](https://img.shields.io/badge/Claude-Projects-purple)](https://claude.ai)

**把泛用 AI 助理打造成客製化 AI 員工。** 一套 6 步驟框架，用於設定高效能的 AI Agent 專案 — 身份、規則、流程、輸出格式、知識庫、入職儀式。

改編自 Khairallah AL-Awady 爆紅的 Claude Projects 方法論。經過三週實測、12 次重構，產出 consistently excellent 的 blueprint。

> 多數人把 AI project 當成有標籤的資料夾。  
> 高手把它們打造成客製化 AI 員工 — 每個 project 在對話開始前就知道你的語氣、標準、受眾、工作流程，以及你對「好 output」的定義。

---

## 為什麼多數 AI Project 失敗

| # | 失敗原因 | 為什麼重要 |
|---|---------|-----------|
| 1 | **System prompt 太模糊** | "You are a helpful assistant" 沒有告訴 AI 任何新資訊。它不知道的是你的具體語氣、受眾、格式規則、品質標準 |
| 2 | **沒有 knowledge files** | 沒有知識庫的 project 只是標籤對話，AI 沒有校準的依據 |
| 3 | **一個 project 想包辦所有事** | 把所有工作塞進同一個 project，結果全部平庸。每個 project 應該專注一件事 |

---

## 6 步驟藍圖

每個高效能 project 都有六個元件。跳過任何一個，輸出品質都會明顯下降。

### 1. 身份定義 (Identity Block)
System prompt 的第一段。告訴 AI 它在這個 project 裡**是誰**。

**錯誤：** `You are a helpful writing assistant.`

**正確：**
```text
你是我的資深內容策略師兼寫手。你跟我合作了兩年，完全了解我的語氣、受眾和品質標準。

你在這個 project 的工作是為 25 萬名 AI 初學者讀者研究、規劃、撰寫和編輯長篇文章。

你直接、具體、絕不灌水。每一句話都必須證明自己值得存在，否則刪掉。
```

**為什麼有效：** 明確的身份讓 AI 預設輸出自信、具體的內容，而非泛泛的安全回答。「跟我合作了兩年」創造信賴框架；具體的受眾數字讓 AI 知道為誰而寫。

### 2. 規則區塊 (Rules Block)
最重要的部分。一組不可協商的 ALWAYS / NEVER 清單，把 AI 限制在你的特定軌道上。

```text
ALWAYS:
- 使用短段落。每段最多 3 句。
- 用具體數字取代模糊宣稱。
- 每節的關鍵洞察要加粗。

NEVER:
- 使用「賦能」「優化」「賦予」等空泛詞彙
- 以「現今」「值得注意的是」開頭
- 寫無法套用到任何人身上的泛泛建議
```

**祕訣：** 每次你發現自己在修正 AI 的輸出，那次修正就成為一條新的 rule。一個月後你的 rules list 就是一把精密工具。

### 3. 流程區塊 (Process Block)
定義 AI 如何思考，而非產出什麼。

```text
流程：
1. 寫之前先想：讀者已經相信什麼？開頭必須挑戰那個信念。
2. 先列大綱再寫任何段落。
3. 第一稿一氣呵成，不要邊寫邊改。
4. 寫完後對照 rules 清單檢查，修正違規。
5. 確認每個宣稱都有具體數字或例子支持。
```

**為什麼有效：** 沒有 process block，AI 直接跳進輸出。有了它，AI 遵循結構化工作流程，品質穩定提升。

### 4. 輸出格式區塊 (Output Format Block)
消除對最終成品的所有猜測空間。

```text
輸出格式：
- 標題：[數字] + [具體主題] + [排除鉤子]
- 長度：2000-3500 字
- 結構：對比開場 > 背景脈絡 > 編號主內容 > 總結行動呼籲
- 副標題：加粗，寫得像鉤子
```

**為什麼有效：** AI 知道正確格式後會平均分配注意力；沒有格式規範時，前面太詳細、後面草草收尾。

### 5. 知識庫 (Knowledge Files)
這是 project 獲得真正智慧的地方。這些文件在每次對話中都會被參考。

| 文件 | 必要？ | 用途 |
|------|-------|------|
| **風格指南** | ✅ 必備 | 至少 3 篇最佳作品 — AI 學會你的語氣 |
| **受眾檔案** | ✅ 必備 | 誰看你的內容？他們知道什麼？困擾什麼？ |
| **競爭者分析** | 📌 建議 | 哪些角度被用爛了？該避開什麼？ |
| **歷史表現數據** | 📌 建議 | 哪些作品表現最好？什麼標題互動最高？ |
| **模板庫** | 📌 建議 | 常見內容類型的可重用格式 |

### 6. 入職訊息 (Onboarding Message)
每次新對話的第一條訊息 — 就像每天給員工的 briefing。

```text
今天要做的是：[任務]

脈絡：[要做什麼、為什麼]

風格參考我的指南。受眾參考我的受眾檔案。

開始之前先回答：
1. 這篇內容跟現有文章比，差異點在哪？
2. 讀者原本相信什麼，我們可以挑戰什麼？
3. 一句話的 hook 是什麼？
```

**為什麼有效：** 這條訊息同時啟動所有 knowledge files、設定任務上下文、強迫 AI 先策略思考再執行。

---

## 完整 System Prompt 模板

```text
身份：
你是我的[角色]。你跟我合作了兩年，完全了解我的語氣、受眾和標準。

你在這個 project 的工作是[主要功能]，為[受眾描述]服務。

你[溝通風格]。你絕不[反模式]。

規則：
一定要：
- [規則 1]
- [規則 2]

絕不能：
- [反規則 1]
- [反規則 2]

流程：
1. [步驟 1 — 思考/規劃]
2. [步驟 2 — 大綱/結構]
3. [步驟 3 — 執行]
4. [步驟 4 — 根據規則審查]
5. [步驟 5 — 品質檢查]

輸出格式：
- 格式：[精確規範]
- 長度：[字數範圍]
- 結構：[段落順序]
```

---

## 你需要的 5 個 Project

| Project | 重點 | 核心知識庫 |
|---------|------|-----------|
| **內容創作** | 寫作語氣、受眾、內容標準 | 風格指南、代表作、受眾 persona、內容行事曆 |
| **研究分析** | 研究結構、來源信任、分析深度 | 研究方法、過往分析、評估標準 |
| **溝通協作** | email/訊息風格、專業語氣 | 優秀範例、常用模板 |
| **策略規劃** | 商業脈絡、目標、限制 | 商業計畫、競爭者資料、策略框架 |
| **程式開發** | 技術棧、編碼慣例、架構 | CLAUDE.md、ADR、範例程式碼 |

---

## 預期效果

| 設定前 | 設定後 |
|--------|--------|
| 寫詳細 prompt → 還可以的答案 | 寫兩行任務 → 輸出已符合你的語氣 |
| 花 20 分鐘編輯每個回應 | 花 2 分鐘審查 |
| 每天重複 5-10 次 | 每天重複 5-10 次 |
| **~90% 時間在編輯** | **減少 90% 編輯時間** |

**一次性設定：約 45 分鐘。每年省 250+ 小時。**

---

## 套用到不同平台

### Hermes Agent
- **身份 + 規則 →** 寫入 `AGENTS.md` 或 profile system prompt
- **流程 + 輸出格式 →** Skill 的 `SKILL.md` 步驟與格式規範
- **知識庫 →** Skill 的 `references/` 目錄、memory 中的範例
- **入職訊息 →** 每次新任務的第一條指令
- **5 個 Project →** 各自的 Hermes profiles，各有自己的 skills/config

### Claude Projects
- **身份 + 規則 + 流程 + 輸出格式 →** Project system prompt
- **知識庫 →** Project knowledge 上傳檔案
- **入職訊息 →** 每次對話的第一條訊息
- **5 個 Project →** 5 個獨立的 Claude projects

### Cursor / VS Code / 任何 AI Chat
- **身份 + 規則 →** `.cursorrules` 或 custom instructions
- **知識庫 →** 專案 `docs/` 或參考檔案
- **流程 + 輸出 →** Task prompt 前綴模式

---

## 專案結構

```
ai-project-blueprint-skill/
├── SKILL.md                  # Hermes Agent skill 完整定義
├── README.md                 # 本文件（英文）
├── README.zh-TW.md           # 說明文件（繁體中文）
├── LICENSE                   # MIT 授權
└── .gitignore
```

---

## 授權

MIT — 見 [LICENSE](LICENSE) 詳細說明。

## 致謝

改編自 [@eng_khairallah1](https://x.com/eng_khairallah1/status/2063186252606865711) 關於 Claude Projects 設定的爆紅貼文。包裝為可重複使用的 skill，適用於任何 AI Agent 生態系統。
