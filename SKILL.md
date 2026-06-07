---
name: ai-project-blueprint
description: 6-Part Blueprint for setting up high-performance AI agent projects — adapted from Khairallah AL-Awady's Claude Projects methodology. Turns generic AI assistants into customized AI employees with persistent identity, rules, process, output format, knowledge files, and onboarding ritual.
---

# AI Project Blueprint — 客製化 AI 員工設定法

## 核心哲學

多數人把 AI projects 當成有標籤的資料夾。高手把它們打造成**客製化 AI 員工** — 每個 project 在對話開始前就知道你的語氣、標準、受眾、工作流程，以及你對「好 output」的定義。

這套 blueprint 來自 @eng_khairallah1 的實測（三週、12 次重構），適用於 Claude Projects、Hermes 的 skills/profile 設定、或其他任何 AI agent 的工作區配置。

---

## 為什麼多數 Project 失敗

1. **System prompt 太模糊** — "You are a helpful assistant" 不是 system prompt。Claude 已經知道怎麼 helpful，它不知道的是你的具體語氣、受眾、格式規則、品質標準、以及你討厭的十五件事
2. **沒有 knowledge files** — 沒有知識庫的 project 只是標籤對話。整個重點是 AI 有持續可參考的文件
3. **一個 project 想包辦所有事** — "Work Stuff" 處理 email、內容、策略、研究、程式、分析 → 全部平庸。每個 project 專注一件事

---

## 6-Part Blueprint

### Part 1: Identity Block

System prompt 的第一段。告訴 AI 它在這個 project 裡**是誰**。

**錯誤寫法：**
```
You are a helpful writing assistant.
```

**正確寫法：**
```
You are my senior content strategist and writer. You have been working with me for two years. You know my voice, my audience, and my quality standards intimately.

Your job in this project is to research, plan, draft, and edit long-form articles for my audience of 250,000 followers who are learning AI tools for the first time.

You are direct. You are specific. You never use filler. Every sentence earns its place or gets cut.
```

**為什麼有效：** 明確的身份讓 AI 預設輸出自信、具體的內容，而非泛泛的安全回答。「與我共事兩年」創造出信賴框架；具體的受眾數字讓 AI 知道為誰而寫。

### Part 2: Rules Block

**最重要的部分** — 一條 non-negotiable 的清單，規定 AI 必須做和絕不能做的事。

**格式：**
```
ALWAYS:
- [Rule 1 — 具體可執行]
- [Rule 2]
- [Rule 3]

NEVER:
- [Anti-rule 1]
- [Anti-rule 2]
```

**真實範例：**
```
ALWAYS:
- Use short paragraphs. Maximum 3 sentences per paragraph.
- Include specific numbers rather than vague claims. Never say "many" or "some."
- Bold the key insight in every section so a skimmer can read just the bold text.
- Open with a hook that creates a gap between what the reader thinks they know and what is actually true.
- End with a CTA that creates urgency without being salesy.

NEVER:
- Use the word "leverage" or "utilize" or "streamline"
- Start any sentence with "In today's" or "It's important to note"
- Write generic advice that could apply to anyone.
- Include disclaimers or hedging language like "it depends" without immediately following with specifics.
```

**Pitfall:** 每次你發現自己在修正 AI 的輸出，那次修正就應該成為一條新的 rule。一個月後你的 rules list 就是一把精密工具。

### Part 3: Process Block

定義 AI 在 project 中**如何思考**，而非產出什麼。

**格式：**
```
PROCESS:
1. [Step 1 — 先思考/規劃]
2. [Step 2 — 結構化]
3. [Step 3 — 執行]
4. [Step 4 — 根據 rules 審查]
5. [Step 5 — 品質檢查]
```

**真實範例（內容創作）：**
```
PROCESS:
1. Before writing anything, spend your first paragraph thinking about what the reader already believes about this topic. Your opening must challenge that belief.
2. Outline the complete structure before writing any section. Share the outline for approval before proceeding.
3. Write the first draft in one pass without self-editing.
4. Review the draft against my Rules. Fix any violations.
5. Check every claim for a specific supporting number or example. Replace anything vague.
6. Read the entire piece as if you are a busy person scrolling on their phone. Cut anything that would make them stop reading.
```

**為什麼有效：** 沒有 process block，AI 直接跳進輸出。有了它，AI 遵循結構化工作流程，品質穩定提升。

### Part 4: Output Format Block

精確定義最終成品長什麼樣子 — 消除所有猜測空間。

**格式：**
```
OUTPUT FORMAT:
- Title: [格式規範]
- Length: [字數範圍]
- Structure: [各段落順序]
- Style: [具體風格標記]
```

**真實範例：**
```
OUTPUT FORMAT:
- Title: [Number] + [Specific Topic] + [Exclusion Hook]
- Length: 2000-3500 words
- Structure: Bold contrast opener (2 paragraphs) > Context section > Numbered main content > Strong closing CTA
- Subheadings: Bold, written as hooks that make the reader want to read the section
- Closing: Italic line + bold italic line using the "most people will X / the ones who Y" dichotomy
```

**為什麼有效：** AI 知道正確格式後會平均分配注意力；沒有格式規範時，前面太詳細、後面草草收尾。

### Part 5: Knowledge Files

這是 project 獲得真正智慧的地方。上傳這些文件，AI 在每次對話中都會參考。

**必備：**
- **Style guide** — 至少 3 篇你的最佳作品作為範例。AI 會 pattern-match 你的語氣
- **Audience profile** — 誰看你的內容？他們已經知道什麼？什麼困擾他們？想達到什麼？

**建議：**
- **Competitor analysis** — 哪些角度被用爛了？上傳你想避開的內容範例
- **Performance data** — 哪些歷史作品表現最好？什麼標題互動最高？
- **Template library** — 最佳格式作為可重用模板

### Part 6: Onboarding Message

每次新對話的第一條訊息 — 就像每天給員工的 briefing。

**真實範例：**
```
Today we are working on [TASK].

Here is the context: [WHAT I NEED AND WHY]

Reference my style guide for voice. Reference my audience profile for targeting. Reference my performance data for strategic decisions.

Before starting, tell me:
1. What angle would make this stand out from what already exists?
2. What does the reader already believe that we can challenge?
3. What is the one-sentence hook?

Once I approve the angle, proceed with a full outline.
```

**為什麼有效：** 這條訊息同時啟動所有 knowledge files、設定任務上下文、強迫 AI 先策略思考再執行。

---

## 完整 System Prompt 模板

```
IDENTITY:
You are my [ROLE]. You have worked with me for two years. You know my voice, my audience, and my standards.

Your job in this project is to [PRIMARY FUNCTION] for [AUDIENCE DESCRIPTION].

You are [COMMUNICATION STYLE]. You never [ANTI-PATTERNS].

RULES:
ALWAYS:
- [Rule 1]
- [Rule 2]
- [Rule 3]

NEVER:
- [Anti-rule 1]
- [Anti-rule 2]

PROCESS:
1. [Step 1]
2. [Step 2]
3. [Step 3]
4. [Step 4]
5. [Step 5]

OUTPUT FORMAT:
- Format: [EXACT FORMAT SPECIFICATION]
- Length: [WORD COUNT RANGE]
- Structure: [SECTION ORDER]
- Style: [SPECIFIC STYLE MARKERS]
```

---

## 你需要 5 個 Projects

不需要 20 個，只需要 5 個，各自處理一個核心 workflow：

| Project | Identity | Knowledge Files |
|---------|----------|-----------------|
| **Content Production** | 寫作語氣、受眾、內容標準 | Style guide、最佳作品、受眾 persona、內容行事曆 |
| **Research & Analysis** | 研究結構化、來源信任度、分析深度 | 研究方法論、過往分析範例、評估標準 |
| **Communication** | email/訊息風格、專業語氣 | 優秀 email 範例、常用訊息模板 |
| **Strategy & Planning** | 商業脈絡、目標、限制、決策框架 | 商業計畫、競爭者資料、市場研究、策略框架 |
| **Code & Technical** | 技術棧、編碼慣例、架構偏好 | CLAUDE.md、ADR、偏好寫法範例 |

---

## 預期效果

- **設定前：** 寫詳細 prompt → AI 給還可以的答案 → 花 20 分鐘編輯修正 → 每天重複 5-10 次
- **設定後：** 寫兩行任務描述 → AI 給出已經符合語氣、規則、受眾、品質標準的輸出 → 花 2 分鐘審查 → 每天重複 5-10 次

減少 90% 的編輯修正時間。一次性設定約 45 分鐘，每年省 250+ 小時。

---

## 將此方法應用到 Hermes Agent

這套 blueprint 可以直接映射到 Hermes 的工作流：

- **Identity + Rules →** 寫入 `AGENTS.md` / `CLAUDE.md` 或你的 profile system prompt
- **Process + Output Format →** 寫成 skill 的 SKILL.md 中的步驟與格式規範
- **Knowledge Files →** skill 中的 `references/` 目錄、或 memory 中儲存的範例
- **Onboarding Message →** 每次新任務的第一條指令，明確引用哪些 skills 和 references
- **5 Projects →** 各個獨立的 Hermes profiles，各有自己的 skills/plugins/config

引用來源：[@eng_khairallah1](https://x.com/eng_khairallah1/status/2063186252606865711)
