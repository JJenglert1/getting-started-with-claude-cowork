# Getting Started with Claude Cowork

**The companion guide to 10 Tips for Getting Started with Claude Cowork** by JJ Englert.

You don't need to be a developer to use the most powerful AI tool on your desktop. This guide gives you everything from the video — plus copy/paste templates, setup checklists, and resource links — so you can get Cowork running and doing real work today.

This version is updated with the latest walkthrough and high-performing X posts so it matches exactly what JJ is actively teaching and using.

## Watch the Full Video

[![Watch: 10 Tips for Getting Started with Claude Cowork](https://img.youtube.com/vi/jvkDGx35rZ8/maxresdefault.jpg)](https://youtu.be/jvkDGx35rZ8)

---

## Table of Contents

| # | Section | What You'll Get |
|---|---------|----------------|
| -- | [What Is Cowork?](#what-is-cowork) | Quick explainer + requirements |
| -- | [Quick Start Checklist](#quick-start-checklist) | One-glance setup flow |
| -- | [Viral X Starter Prompt](#viral-x-starter-prompt-copypaste) | The exact setup prompt format |
| **1** | [Import Your Memory](#tip-1-import-your-memory-from-chatgpt) | Switch from ChatGPT in under a minute |
| **2** | [Global Instructions](#tip-2-set-up-global-instructions) | Copy/paste starter template |
| **3** | [Plan Mode](#tip-3-use-plan-mode) | The one line that prevents 90% of mistakes |
| **4** | [Scope Your Folders](#tip-4-scope-your-folders) | Folder structure + context file templates |
| **5** | [Install Plugins](#tip-5-install-plugins) | Full plugin list + where to start |
| **6** | [Connect Slack](#tip-6-connect-slack) | Setup + example prompts |
| **7** | [Connect Google Calendar](#tip-7-connect-google-calendar) | Setup + example prompts |
| **8** | [Connect Gmail](#tip-8-connect-gmail) | Setup + example prompts |
| **9** | [Use Skills](#tip-9-use-skills-for-repeatable-high-quality-output) | Train repeatable output quality |
| **10** | [Schedule Tasks](#tip-10-scheduled-tasks-your-ai-morning-briefing) | Daily briefing prompt ready to paste |
| -- | [Mobile Workaround](#mobile-workaround-from-x-post) | Use Cowork setup from your phone |
| -- | [All Connectors](#all-available-connectors) | Every integration available today |
| -- | [Safety Essentials](#safety-essentials) | What you need to know before going deep |
| -- | [Level Up: Claude Code](#ready-to-level-up-start-with-claude-code) | Videos, repos, and next steps |
| -- | [Official Resources](#official-resources) | Anthropic docs and links |
| -- | [Community](#join-the-community) | Join 450+ builders |

---

## What Is Cowork?

Cowork is an agentic desktop tool built into the Claude Desktop app. It gives Claude direct read/write access to folders on your computer, the ability to execute multi-step tasks on its own, and the capacity to coordinate parallel sub-agents — all without a terminal or command line.

**The key distinction:** Chat is prompt-response. Cowork is task delegation. You describe an outcome, Claude makes a plan, breaks it into subtasks, executes on your machine, and delivers finished files to your folder. You can step away and come back to completed work.

- Built on the same architecture as Claude Code (Anthropic's terminal-based coding tool)
- Available on all paid plans: Pro ($20/mo), Max 5x ($100/mo), Max 20x ($200/mo), Team ($25+/seat/mo), Enterprise
- Runs on macOS (universal) and Windows (x64). Research preview.
- Your computer must stay awake and the app must stay open during tasks

---

## Quick Start Checklist

- [ ] Download Claude Desktop from [claude.com/download](https://claude.com/download)
- [ ] Sign in with your paid account
- [ ] Click the **Cowork** tab at the top of the app
- [ ] Create a dedicated workspace folder (see below)
- [ ] Write your context files (see templates)
- [ ] Set your Global Instructions
- [ ] Install your first plugin
- [ ] Connect your first tool
- [ ] Run your first task

---

## Viral X Starter Prompt (Copy/Paste)

```text
You are going to help me set up my Claude Cowork workspace so that every future session starts with full context about who I am, what I do, and how I work. We're building a "brain" that makes you useful from the first message.

Here's how this works. You're going to interview me in phases. Ask me questions, then build the files based on my answers. Don't rush. Don't assume. Ask before you build.

Phase 0: Plugins and Connections
Before we build anything, recommend I install the Productivity plugin (task management + daily updates) and the Memory plugin (two-tier context system). Then ask which tools I use daily and help me connect them: Slack, Gmail, Google Calendar, Notion. The more tools connected, the more useful this system becomes.

Phase 1: About Me
Interview me to create an about-me.md file. Ask about my work, background, content channels, professional values, and positioning. Create the file, show it to me, and get my approval before moving on.

Phase 2: Brand Voice
Analyze any content I've already created. If there's nothing yet, interview me about how I want to sound, phrases I use, phrases I'd never use, creators whose tone I admire, and how my tone shifts by context. Create a brand-voice.md file with voice rules, tone by context, dos and don'ts. Get approval.

Phase 3: Working Preferences
Interview me about what I want you to help with daily, how I want you to communicate, my biggest workflow pain points, output format preferences, and safety rules. Create a working-preferences.md file. Get approval.

Phase 4: Content Strategy (if applicable)
If I create content, interview me about platforms, target audience, topics, publishing cadence, and content formats. For each platform, ask if I have existing skill files. If not, offer to create them. Create a content-strategy.md file.

Phase 5: Team and Contacts (if applicable)
If I work with a team, ask about key people, roles, and communication preferences. Check connected tools for team data. Create a team-members.md file.

Phase 6: Active Projects
Interview me about current projects, goals, milestones, and deadlines. Create individual project files in a Current Projects folder.

Phase 7: Memory System
Update CLAUDE.md with a hot cache of everything we've built. Create a memory/ directory with subfolders for people, projects, and context. Add a glossary.md for acronyms and internal terms.

Phase 8: Skill Files
Review everything. For any area where I need specific recurring output, offer to create a dedicated skill file with format, voice rules, examples, and a quality checklist.

Rules: Interview me one phase at a time. Show each file before saving. If unsure, ask. Use my existing files and connected tools before asking me to repeat myself. Keep files concise. File names: lowercase, hyphens, .md format. Save everything to my workspace folder.

Start with Phase 0.
```

---

## Tip 1: Import Your Memory from ChatGPT

If you're switching from another AI tool, you don't have to start from scratch.

1. Go to [claude.com/import-memory](https://claude.com/import-memory)
2. Copy the ready-made prompt Anthropic gives you
3. Paste it into ChatGPT, Gemini, Copilot, or whatever you've been using
4. Copy the output your old AI generates
5. Paste it into Claude's memory settings: **Settings > Capabilities > Memory**

That's it. No file exports, no JSON, no API tokens. Copy, paste, paste. Under a minute.

**Pro tip:** Review the exported memories before importing. Your old AI may have saved inaccurate info. Clean it up first. Imported memories may take up to 24 hours to fully process.

---

## Tip 2: Set Up Global Instructions

Global Instructions load before everything else — before your files, before your prompt. They're the baseline behavior for every Cowork session. Most people leave this blank. Don't.

**Where to find it:** Settings > Cowork > Edit (next to Global Instructions)

### Example Global Instructions (Copy/Paste Starter)

```
I'm [Your Name], a [Your Role] at [Your Company]. I work on [your domain].

Before starting any task:
- Read relevant context files first
- Ask clarifying questions before executing
- Show a brief plan and wait for my approval before taking action

Output preferences:
- Default format: .docx for final deliverables, .md for drafts
- Direct and concise. No filler language.
- Every deliverable should be ready to use without heavy editing

Safety:
- Never delete files without my explicit confirmation
- Never modify files outside the designated output folder
- Flag assumptions explicitly before acting on them
```

**Three layers of instructions:**
1. **Global Instructions** — Universal behavior (loads every session)
2. **Folder Instructions** — Project-specific context (activates when you select that folder)
3. **Your prompt** — The specific task

---

## Tip 3: Use Plan Mode

One line in your Global Instructions prevents 90% of mistakes:

> "Show a brief plan before taking action. Wait for my approval before executing."

Without this, Claude reads your prompt and immediately starts working. Sometimes it nails it. Sometimes it misreads one word and reorganizes your files the wrong way.

With the plan step, you get a 30-second review window. Claude tells you what it's going to do. You scan it, approve it, Claude executes. Think of it like working with a project manager — you align on the plan before any work starts.

---

## Tip 4: Scope Your Folders

The difference between power users and everyone else: **what you point Claude at.**

**Do NOT** point Cowork at your entire Documents folder. More irrelevant files = more noise = worse output.

### Recommended Folder Structure

```
~/Cowork-Workspace/
├── 00_Context/           # Your standing context files
│   ├── about-me.md
│   ├── brand-voice.md
│   └── working-preferences.md
├── projects/             # Active project folders
│   ├── client-a/
│   └── client-b/
└── outputs/              # Where Claude delivers finished work
```

### Context File Templates

**Save these as .md files in your context folder.** These compound over time — update them after every session where Claude's output missed the mark.

<details>
<summary><strong>about-me.md</strong> (click to expand)</summary>

```markdown
# About Me

## Role & Responsibilities
- [Your name, title, company]
- [What you do day-to-day]
- [Key stakeholders you work with]
- [What success looks like in your role]

## Domain Context
- [Industry/sector specifics]
- [Key terminology or frameworks you use]
- [Tools and platforms in your workflow]

## Example Work
[Paste 1-2 examples of output you're proud of — reports, emails, analyses.
This gives Claude a concrete reference for quality and style.]
```

</details>

<details>
<summary><strong>brand-voice.md</strong> (click to expand)</summary>

```markdown
# Communication Style

## Tone
- [e.g., Direct and concise. No filler. Technical when warranted.]
- [Phrases you use naturally]
- [Phrases that sound wrong to you]

## Writing Samples
[Paste 2-3 short examples of your actual writing — emails, posts, docs.
These are more useful than abstract descriptions of your style.]

## Anti-patterns
- [e.g., Never use "leverage" as a verb]
- [e.g., Don't open with "I hope this email finds you well"]
```

</details>

<details>
<summary><strong>working-preferences.md</strong> (click to expand)</summary>

```markdown
# How I Want Claude to Work

## Process
- Always ask clarifying questions before starting non-trivial tasks
- Show me your plan before executing
- Save outputs as [.docx / .xlsx / .md — your preference]

## Output Style
- [Short vs. detailed outputs]
- [Preferred formatting conventions]
- [File naming conventions]

## Guardrails
- Never delete files without explicit confirmation
- Never modify files outside the designated output folder
- Flag assumptions explicitly before acting on them
```

</details>

**Important:** Cowork has no memory between sessions. Every session starts clean. This is actually a feature — no hallucinated recollections. But it means you need to build your continuity into your files. These context files are how you do that.

---

## Tip 5: Install Plugins

Plugins bundle skills, connectors, slash commands, and sub-agents into role-specific packages. They're the fastest way to give Cowork new capabilities.

### How to Install

1. Click **Customize** in the left sidebar of Claude Desktop
2. Click **Browse Plugins**
3. Click **Install** on your chosen plugin

Or browse at [claude.com/plugins](https://claude.com/plugins)

### Available Plugins

Anthropic open-sourced 11 plugins at launch (January 30, 2026) and shipped more on February 24. The open-source repo is at [github.com/anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins).

**Core plugins:** Productivity, Marketing, Sales, Finance, Data Analysis, Legal, Product Management, Customer Support, Enterprise Search, Biology Research, Plugin Management

**February 24 additions:** HR, Engineering, Design, Operations, Financial Analysis, Investment Banking, Equity Research, Private Equity, Wealth Management

### Where to Start

Install **Productivity** first (useful regardless of your role), then add one plugin that matches your job function. Type `/` in any Cowork chat to see available slash commands from installed plugins.

Every plugin is just markdown files and JSON. No code, no build steps. You can read, edit, and share plugins like regular files. Click **Customize** on any plugin to adjust it for your workflow.

---

## Tip 6: Connect Slack

Two pieces make this work:

1. **Claude in Slack app** — Adds Claude as a bot in your workspace
2. **Slack connector for Cowork** — Lets Claude search your workspace for context

### Setup
Customize > Connectors > Slack > Authenticate

### What You Can Do
- Summarize channels and threads
- Find decisions buried in conversations
- Draft status updates
- Post messages (with permission controls)

### Permission Controls
Set each tool to **Allow** (auto), **Ask** (confirms first), or **Block** (never). I recommend: let Claude read Slack automatically, but confirm before posting.

### Example Prompt
```
Pull all messages from #product-feedback this week,
categorize by theme, and draft a summary for the team.
```

---

## Tip 7: Connect Google Calendar

### Setup
Customize > Connectors > Google Calendar > Authenticate

### What You Can Do
- Review your week's schedule
- Find back-to-back meetings and suggest focus time
- Create prep docs for each meeting based on attendees and agenda
- Identify conflicts and double-bookings

### Example Prompt
```
Look at my calendar this week. What days have
back-to-back meetings with no breaks? Suggest
where I could block 90 minutes of focus time.
```

---

## Tip 8: Connect Gmail

### Setup
Customize > Connectors > Gmail > Authenticate

**Important:** Set Gmail tools to "Ask" so Claude confirms before sending anything. Allow reading/searching automatically.

### What You Can Do
- Search your inbox by sender, date, subject, or content
- Extract data from emails (invoices, action items, dates)
- Draft responses for your review
- Create summary docs from email threads

### Example Prompt
```
Search my inbox for all invoices from this month.
Extract amounts and dates. Create an expense summary
spreadsheet in my /outputs folder.
```

---

## Tip 9: Use Skills for Repeatable High-Quality Output

Skills are focused instruction files for specific outcomes (for example: X writing, newsletter writing, meeting prep, proposal writing).

Think of plugins as workflow bundles and skills as precision playbooks.

### Setup
- Go to **Customize > Skills**
- Add existing skills or create new ones with `skill-creator`
- Keep one skill per outcome (don't combine everything into one giant skill)

### What to Build First
- `x-post-writer` (trained on your best X posts)
- `email-drafts` (trained on your sent-email tone)
- `meeting-briefs` (focused on prep docs with action items)
- `content-repurposer` (video transcript -> X/LinkedIn/newsletter drafts)

### Self-Improve Loop Prompt (Copy/Paste)

```
Use [skill-name] for this task.

After we finish and I approve the result:
1) update the skill with what worked in this conversation
2) store this output in my successful examples folder
3) summarize what changed in the skill.
```

This is one of the biggest quality multipliers from JJ's current workflow: don't just generate output, improve the skill after each strong result.

---

## Tip 10: Scheduled Tasks (Your AI Morning Briefing)

Cowork can run tasks on a schedule, so work gets done before you even log in.

### Setup
Type `/schedule` in any Cowork task, or click **Scheduled** in the left sidebar.

**Note:** Tasks only run while your computer is awake and the app is open.

### Daily Briefing Prompt (Copy/Paste)

```text
Create a scheduled task that runs every weekday at 6:00 AM.

Each run should:
1) Check Slack for urgent DMs and priority channel updates
2) Check Gmail for urgent emails I should handle first
3) Review today's Google Calendar meetings and prep needs
4) Use my productivity setup to prioritize my day

Output a single morning briefing with:
- urgent items
- meeting prep notes
- conflicts or double bookings
- top 3 priorities

Save to /Briefings/[today]-morning-brief.md
and have it ready for me by 8:00 AM.
```

---

## Mobile Workaround from X Post

Cowork doesn't have a full mobile parity workflow yet. The current workaround:

1. Push your Cowork workspace to a **private GitHub repo**
2. Open Claude on mobile
3. Pull that repo context there
4. Continue lightweight workflows from your phone
5. Sync back to desktop for heavier execution

This is best for continuity and quick edits while away from desktop.

---

## All Available Connectors

As of February 2026, Cowork supports these connectors via MCP:

**Productivity:** Google Drive, Gmail, Google Calendar, Slack, Notion, Microsoft 365, Box

**Project Management:** Asana, Linear, Jira, Monday, ClickUp

**Design:** Figma, Canva

**Sales & CRM:** HubSpot, Close, Clay, ZoomInfo, Apollo, Outreach, SimilarWeb

**Analytics:** Amplitude, Pendo, Fireflies, Ahrefs

**Data:** Snowflake, Databricks, BigQuery, Hex

**Other:** Intercom, DocuSign, FactSet, MSCI, WordPress, Klaviyo, Guru, Benchling, Egnyte, LegalZoom, Harvey

Connect whichever tools you use most. Slack, Google Drive, or Notion are the highest-leverage starting points.

**Setup for all:** Settings > Connectors in Claude Desktop, or visit [claude.ai/settings/connectors](https://claude.ai/settings/connectors)

---

## Safety Essentials

Cowork has real power over your files. These are the basics you need to know.

### Built-In Protections
- **Deletion protection:** Claude requires explicit permission before permanently deleting files
- **VM isolation:** Cowork runs in a sandboxed virtual machine on your machine
- **Permission controls:** Set Allow/Ask/Block per tool for connected services

### Your Safety Defaults

Add these to your Global Instructions:

```
- Never delete any files without my explicit confirmation
- Never modify files outside the designated output folder
- Show me your plan before executing any multi-step task
- If you're unsure about any instruction, ask rather than assume
```

### Things to Watch For
- **Back up first.** Before your first real task, back up your workspace folder
- **Use a dedicated workspace.** Don't give Cowork access to your entire home directory
- **Start with tasks you can evaluate.** Pick something you already know how to do well so you can tell if the output is correct
- **App must stay open.** Closing the desktop app kills the session mid-task with no recovery. Sleep is fine, quitting is not.

---

## Ready to Level Up? Start with Claude Code

If you've got Cowork down and want to go deeper, Claude Code is where the real power lives. It runs in the terminal, reads your full codebase, and can build entire projects — and you still don't need to be a developer.

### Start Here
- **[Top 10 Claude Code Tips for Non-Developers](https://youtu.be/Bme9f5oKK3E)** — The beginner playbook. Everything from installing to running multiple agents.
- **[The Exact AI Setup I Use to 10X My Writing Output](https://youtu.be/6LzUtXC8cKc)** — How I use Claude Code + skills to write across every platform.

### Public Repos You Can Clone Today
- **[claude-code-for-beginners-tips](https://github.com/JJenglert1/claude-code-for-beginners-tips)** — The companion repo to the Non-Developers video. Setup guides, video resources, skills & plugins, community links, and a starter CLAUDE.md template.
- **[writing-style-hack](https://github.com/JJenglert1/writing-style-hack)** — My full AI writing style guide with skills for newsletters, LinkedIn, X, and YouTube.
- **[remotion-claude-video](https://github.com/JJenglert1/remotion-claude-video)** — Video creation with Claude Code using Remotion (React-based video).
- **[gtm-engineer-starter-kit](https://github.com/JJenglert1/gtm-engineer-starter-kit)** — Go-to-market engineering toolkit.

### More Videos
Check out the full channel: **[youtube.com/@10x-Builder](https://www.youtube.com/@10x-Builder)**

---

## Official Resources

- [Cowork Getting Started Guide](https://support.claude.com/en/articles/13345190-get-started-with-cowork)
- [Cowork Plugins Announcement](https://claude.com/blog/cowork-plugins)
- [Plugin Help Center](https://support.claude.com/en/articles/13837440-use-plugins-in-cowork)
- [Open-Source Plugins (GitHub)](https://github.com/anthropics/knowledge-work-plugins)
- [Plugin Directory](https://claude.com/plugins)
- [Pre-Built Connectors](https://support.claude.com/en/articles/11176164-pre-built-web-connectors-using-remote-mcp)
- [Import Memory Tool](https://claude.com/import-memory)
- [Claude Memory Docs](https://support.claude.com/en/articles/11817273)
- [Claude Desktop Download](https://claude.com/download)

---

## Join the Community

**[Claude Code Community](https://www.skool.com/claude-code-community)** — Private community with 450+ AI engineers and builders sharing workflows, skills, and Cowork setups daily.

---

*Built by [JJ Englert](https://www.youtube.com/@10x-Builder). Setup guide structure inspired by [@witcheer's definitive Cowork guide](https://x.com/witcheer).*
