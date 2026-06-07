# AI Project Blueprint

**Turn generic AI assistants into customized AI employees.**

A 6-part framework for setting up high-performance AI agent projects — adapted from Khairallah AL-Awady's Claude Projects methodology. Three weeks of testing, 12 rebuilds, one blueprint that consistently produces excellent output with minimal prompting.

> Most people treat AI projects like a folder with a label on it.  
> Experts build customized AI employees — each project tuned so precisely that the AI knows their voice, their standards, their audience, their workflow, and their exact definition of "good output" before they type a single word.

---

## Why Most AI Projects Fail

1. **Vague system prompt** — "You are a helpful assistant" tells the AI nothing it doesn't already know. What it *doesn't* know is your specific voice, audience, formatting rules, quality bar, and the fifteen things you hate seeing in output.
2. **No knowledge files** — A project without reference documents is just a labeled conversation.
3. **One project to rule them all** — "Work Stuff" that handles emails, content, strategy, research, coding, and analysis produces mediocre results across the board. Separate workflows into separate projects.

---

## The 6-Part Blueprint

Every high-performing project has six components. Skip any and output quality drops measurably.

### 1. Identity Block
The first thing in your system prompt. Tells the AI exactly who it is.

**Wrong:** `You are a helpful writing assistant.`

**Right:**
```
You are my senior content strategist and writer. You have been working with me for two years. You know my voice, my audience, and my quality standards intimately.

Your job in this project is to research, plan, draft, and edit long-form articles for my audience of 250,000 followers who are learning AI tools for the first time.

You are direct. You are specific. You never use filler.
```

### 2. Rules Block
The most important part. A non-negotiable list of ALWAYS / NEVER constraints.

```
ALWAYS:
- Use short paragraphs. Max 3 sentences per paragraph.
- Include specific numbers rather than vague claims.
- Bold the key insight in every section.

NEVER:
- Use the word "leverage" or "utilize" or "streamline"
- Start any sentence with "In today's" or "It's important to note"
- Write generic advice that could apply to anyone.
```

**Tip:** Every time you find yourself correcting the AI's output, that correction becomes a new rule.

### 3. Process Block
Defines *how* the AI should think, not what to produce.

```
PROCESS:
1. Before writing, think about what the reader already believes. Your opening must challenge that belief.
2. Outline the complete structure before writing any section.
3. Write the first draft in one pass without self-editing.
4. Review the draft against your Rules. Fix any violations.
5. Check every claim for a specific supporting number or example.
```

### 4. Output Format Block
Eliminates all guessing about what the finished product looks like.

```
OUTPUT FORMAT:
- Title: [Number] + [Specific Topic] + [Exclusion Hook]
- Length: 2000-3500 words
- Structure: Bold contrast opener > Context > Numbered main content > Closing CTA
- Subheadings: Bold, written as hooks
```

### 5. Knowledge Files
Where the project gets its real intelligence.

**Required:**
- **Style guide** — at least 3 examples of your best work for voice pattern-matching
- **Audience profile** — who reads your content, what they know, what frustrates them

**Recommended:**
- Competitor analysis
- Performance data (best-performing pieces)
- Template library (reusable formats)

### 6. Onboarding Message
The first message in every new conversation — the daily briefing for your AI employee.

```
Today we are working on [TASK].

Here is the context: [WHAT I NEED AND WHY]

Reference my style guide for voice. Reference my audience profile for targeting.

Before starting, tell me:
1. What angle would make this stand out?
2. What does the reader already believe that we can challenge?
3. What is the one-sentence hook?
```

---

## Complete System Prompt Template

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
1. [Step 1 - Think/Plan]
2. [Step 2 - Outline/Structure]
3. [Step 3 - Execute]
4. [Step 4 - Review against rules]
5. [Step 5 - Quality check]

OUTPUT FORMAT:
- Format: [EXACT FORMAT SPECIFICATION]
- Length: [WORD COUNT RANGE]
- Structure: [SECTION ORDER]
```

---

## The 5 Projects Everyone Needs

| Project | Focus | Key Knowledge Files |
|---------|-------|-------------------|
| **Content Production** | Writing voice, audience, standards | Style guide, best pieces, persona, content calendar |
| **Research & Analysis** | Research structure, source trust | Research methodology, past analyses, evaluation criteria |
| **Communication** | Email/messaging style, professional tone | Great email examples, message templates |
| **Strategy & Planning** | Business context, goals, constraints | Business plan, competitor data, strategic frameworks |
| **Code & Technical** | Tech stack, coding conventions | CLAUDE.md, ADRs, code examples |

---

## Expected Results

- **Before:** Detailed prompt → decent response → 20 min of editing → repeat 5-10x/day
- **After:** Two-sentence task → output that already matches your voice and standards → 2 min review → repeat 5-10x/day

**90% reduction in editing time.** One-time setup (~45 minutes) saves 250+ hours per year.

---

## Applying to Hermes Agent

This blueprint maps directly to Hermes workflows:

- **Identity + Rules →** `AGENTS.md` / profile system prompt
- **Process + Output Format →** Skill's `SKILL.md` steps and format specs
- **Knowledge Files →** Skill `references/` directory, stored examples in memory
- **Onboarding Message →** First instruction in each new task, referencing relevant skills
- **5 Projects →** Separate Hermes profiles, each with their own skills/config

---

## Credits

Adapted from [@eng_khairallah1](https://x.com/eng_khairallah1)'s viral thread on Claude Projects setup.  
Packaged as a reusable skill for AI agent ecosystems.

## License

MIT
