# 🎯 AI Project Blueprint

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![AI Agent](https://img.shields.io/badge/AI-Agent%20Ready-blue)](https://github.com/lunkerchen/ai-project-blueprint-skill)
[![Hermes](https://img.shields.io/badge/Hermes-Skill-orange)](https://hermes-agent.nousresearch.com)
[![Claude](https://img.shields.io/badge/Claude-Projects-purple)](https://claude.ai)

**Turn generic AI assistants into customized AI employees.** A 6-part framework for setting up high-performance AI agent projects — identity, rules, process, output format, knowledge files, and onboarding ritual.

Adapted from Khairallah AL-Awady's viral Claude Projects methodology. Three weeks of testing, 12 rebuilds, one blueprint that consistently produces excellent output with minimal prompting.

> Most people treat AI projects like a folder with a label on it.  
> Experts build customized AI employees — each project tuned so precisely that the AI knows their voice, their standards, their audience, their workflow, and their exact definition of "good output" before they type a single word.

---

## Why Most AI Projects Fail

| # | Failure Mode | Why It Matters |
|---|-------------|----------------|
| 1 | **Vague system prompt** | "You are a helpful assistant" tells the AI nothing new. What it doesn't know is your specific voice, audience, formatting rules, quality bar, and the fifteen things you hate seeing in output |
| 2 | **No knowledge files** | A project without reference documents is just a labeled conversation. The AI has nothing to calibrate against |
| 3 | **One project to rule them all** | "Work Stuff" handling emails, content, strategy, research, coding, and analysis produces mediocre results across the board. Each project should do one thing extremely well |

---

## The 6-Part Blueprint

Every high-performing project has six components. Skip any and output quality drops measurably.

### 1. Identity Block
The first thing in your system prompt. Tells the AI exactly who it is.

**Wrong:** `You are a helpful writing assistant.`

**Right:**
```text
You are my senior content strategist and writer. You have been working with me for two years. You know my voice, my audience, and my quality standards intimately.

Your job in this project is to research, plan, draft, and edit long-form articles for my audience of 250,000 followers who are learning AI tools for the first time.

You are direct. You are specific. You never use filler.
```

**Why it works:** A clear identity makes the AI default to confident, specific output rather than generic safe answers. "You have been working with me for two years" creates a trust framing. A specific audience number gives the AI a concrete target to write for.

### 2. Rules Block
The most important part. A non-negotiable ALWAYS / NEVER list that constrains the AI into your specific lane.

```text
ALWAYS:
- Use short paragraphs. Max 3 sentences per paragraph.
- Include specific numbers rather than vague claims.
- Bold the key insight in every section.

NEVER:
- Use the word "leverage" or "utilize" or "streamline"
- Start any sentence with "In today's" or "It's important to note"
- Write generic advice that could apply to anyone.
```

**Pro tip:** Every time you find yourself correcting the AI's output, that correction becomes a new rule. After a month, your rules list is a precision instrument.

### 3. Process Block
Defines *how* the AI should think, not what to produce.

```text
PROCESS:
1. Before writing, think about what the reader already believes. Your opening must challenge that belief.
2. Outline the complete structure before writing any section.
3. Write the first draft in one pass without self-editing.
4. Review the draft against your Rules. Fix any violations.
5. Check every claim for a specific supporting number or example.
```

**Why it works:** Without a process block, the AI jumps straight to generating output. With one, it follows a structured workflow that produces consistently higher-quality results.

### 4. Output Format Block
Eliminates all guessing about what the finished product looks like.

```text
OUTPUT FORMAT:
- Title: [Number] + [Specific Topic] + [Exclusion Hook]
- Length: 2000-3500 words
- Structure: Bold contrast opener > Context > Numbered main content > Closing CTA
- Subheadings: Bold, written as hooks
```

**Why it works:** When the AI knows the exact format before it starts, it distributes effort correctly. Without this, it front-loads detail in early sections and rushes the ending.

### 5. Knowledge Files
Where the project gets its real intelligence. These files are referenced in every conversation.

| File | Required? | Purpose |
|------|-----------|---------|
| **Style guide** | ✅ Required | At least 3 examples of your best work — AI pattern-matches your voice |
| **Audience profile** | ✅ Required | Who reads your content, what they know, what frustrates them |
| **Competitor analysis** | 📌 Recommended | What angles are overused, what to avoid |
| **Performance data** | 📌 Recommended | Best-performing pieces, highest-engagement titles |
| **Template library** | 📌 Recommended | Reusable formats for common content types |

### 6. Onboarding Message
The first message in every new conversation — the daily briefing for your AI employee.

```text
Today we are working on [TASK].

Here is the context: [WHAT I NEED AND WHY]

Reference my style guide for voice. Reference my audience profile for targeting.

Before starting, tell me:
1. What angle would make this stand out?
2. What does the reader already believe that we can challenge?
3. What is the one-sentence hook?
```

**Why it works:** This single message activates all five knowledge files, sets task context, and forces strategic thinking before execution.

---

## Complete System Prompt Template

```text
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
1. [Step 1 — Think/Plan]
2. [Step 2 — Outline/Structure]
3. [Step 3 — Execute]
4. [Step 4 — Review against rules]
5. [Step 5 — Quality check]

OUTPUT FORMAT:
- Format: [EXACT FORMAT SPECIFICATION]
- Length: [WORD COUNT RANGE]
- Structure: [SECTION ORDER]
```

---

## The 5 Projects Everyone Needs

| Project | Focus | Key Knowledge Files |
|---------|-------|-------------------|
| **Content Production** | Writing voice, audience, content standards | Style guide, best pieces, persona, content calendar |
| **Research & Analysis** | Research structure, source trust, depth | Research methodology, past analyses, evaluation criteria |
| **Communication** | Email/messaging style, professional tone | Great email examples, message templates |
| **Strategy & Planning** | Business context, goals, constraints | Business plan, competitor data, strategic frameworks |
| **Code & Technical** | Tech stack, coding conventions, architecture | CLAUDE.md, Architecture Decision Records, code examples |

---

## Expected Results

| Before | After |
|--------|-------|
| Write detailed prompt → decent response | Write two-sentence task → output already matches your voice |
| Spend 20 minutes editing every response | Spend 2 minutes reviewing |
| Repeat 5-10 times per day | Repeat 5-10 times per day |
| **~90% of time lost to editing** | **90% reduction in editing time** |

**One-time setup: ~45 minutes. Annual savings: 250+ hours.**

---

## Applying to Different Platforms

### Hermes Agent
- **Identity + Rules →** Write into `AGENTS.md` or profile system prompt
- **Process + Output Format →** Skill's `SKILL.md` steps and format spec
- **Knowledge Files →** Skill `references/` directory, memory-stored examples
- **Onboarding Message →** First instruction when starting a new task
- **5 Projects →** Separate Hermes profiles with their own skills/config

### Claude Projects
- **Identity + Rules + Process + Output Format →** Project system prompt
- **Knowledge Files →** Project knowledge uploads
- **Onboarding Message →** First message in each conversation
- **5 Projects →** 5 separate Claude projects

### Cursor / VS Code / Any AI Chat
- **Identity + Rules →** `.cursorrules` or custom instructions
- **Knowledge Files →** Project `docs/` or reference files
- **Process + Output →** Task prompt prefix pattern

---

## Project Structure

```
ai-project-blueprint-skill/
├── SKILL.md                  # Full Hermes Agent skill definition
├── README.md                 # This file (English)
├── README.zh-TW.md           # Documentation (Traditional Chinese)
├── LICENSE                   # MIT license
└── .gitignore
```

---

## License

MIT — see [LICENSE](LICENSE) for details.

## Credits

Adapted from [@eng_khairallah1](https://x.com/eng_khairallah1/status/2063186252606865711)'s viral thread on Claude Projects setup. Packaged as a reusable skill for AI agent ecosystems.
