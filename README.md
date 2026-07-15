# Notion Plugin for Claude Code

This repository provides an official Claude Code plugin that bundles:

- **Notion Skills** (from the Notion Cookbook) that teach Claude how to work intelligently inside your Notion workspace  
- The **[Notion MCP Server](https://developers.notion.com/docs/mcp)**, which enables Claude to securely search, read, and update your Notion content  
- A curated set of **Slash Commands** that make common Notion workflows fast and natural  
- **Kingdom OS Skills** that install a full personal operating system inside Claude, combining Kingdom leadership principles with Second Brain methodology
- **Estica Learner Centre MFR** skills and commands for monthly financial operational close

This plugin allows Claude Code users to install everything — Skills + MCP server — with **one click**.

---

## Features

### Notion Skills
Includes all four high-quality Skills from the Notion Cookbook:

- **Knowledge Capture**
- **Meeting Intelligence**
- **Research Documentation**
- **Spec to Implementation**

These instructions teach Claude how to structure, write, summarize, capture, and maintain content in your Notion workspace.

### Integrated Notion MCP Server
Claude Code automatically connects to Notion's hosted MCP server at:

```
https://mcp.notion.com/mcp
```

This provides Claude with tools to:

- Search your workspace  
- Retrieve pages & databases  
- Create and update pages  
- Append notes or blocks  
- Insert database rows  
- Work with properties safely  

### Notion Slash Commands  

| Command | Description |
|--------|-------------|
| `/Notion:search` | Search your entire Notion workspace |
| `/Notion:create-page` | Create a new page under a given parent |
| `/Notion:database-query` | Query a database by name or ID |
| `/Notion:create-task` | Create a task in a Tasks-style database |
| `/Notion:create-database-row` | Insert a row in any database |
| `/Notion:find` | Quick title-based search for pages/databases |
| `/Notion:tasks:setup` | Set up a Notion task board for tracking |
| `/Notion:tasks:build <url>` | Build a task from a Notion page URL |
| `/Notion:tasks:plan <url>` | Make a plan for a task from a Notion page URL |
| `/Notion:tasks:explain-diff` | Generate a Notion doc explaining code changes |

---

## Kingdom OS Second Brain

The Kingdom OS extension installs a full personal and professional operating system inside Claude, combining Kingdom leadership architecture with Second Brain CODE/PARA methodology.

**Core principle**: Order precedes multiplication. Structure precedes the supernatural.

### Kingdom OS Skills

| Skill | Description |
|---|---|
| `kingdom-os-framework` | Nine Kingdom domains, four-layer OS, CODE/PARA, Goshen Principle, domain scoring |
| `kingdom-os-daily-rhythm` | Morning activation, midday alignment, evening debrief protocols |
| `kingdom-os-review-rhythms` | Weekly, monthly, quarterly, and annual review cadences |
| `kingdom-os-mfr` | Estica Learner Centre Monthly Financial Review — all 4 phases, 11 tasks, due 7th of each month |

### Kingdom OS Commands

| Command | Description |
|---|---|
| `/KingdomOS:morning` | Run morning activation — scripture, declaration, top 3 actions, family presence |
| `/KingdomOS:evening` | Run evening debrief — win, obedience step, inbox-zero, scores |
| `/KingdomOS:weekly-review` | Weekly strategic review across all 7 domains |
| `/KingdomOS:log-scripture` | Log scripture + revelation + obedience step to Notion |
| `/KingdomOS:add-project` | Add a Kingdom project to the Projects Board |
| `/KingdomOS:domain-score` | Score a Kingdom domain with RAG and next order step |
| `/KingdomOS:habit-check` | Check in on 66-day habit formation tracker |
| `/KingdomOS:declaration` | Record daily declaration consistency |

### MFR Commands (Estica Learner Centre)

| Command | Description |
|---|---|
| `/KingdomOS:mfr-run` | Walk through the full monthly financial close — all 4 phases, log to Notion |
| `/KingdomOS:mfr-aging` | Run Phase 2 only — aging report, critical defaulters, reminders |
| `/KingdomOS:mfr-close` | Execute sign-off and archival after all phases are confirmed complete |

### Nine Kingdom Domains

1. Spiritual Formation
2. Business & Stewardship
3. Family & Marriage
4. Health & Energy
5. Ministry & Calling
6. Finances & Generosity
7. Leadership & Team
8. Learning & Wisdom
9. Community & Brotherhood

All Kingdom OS commands read from and write to your Notion workspace using the same Notion MCP server — no additional setup required.

---

## Installation (Claude Code)

### 1. Add this plugin's marketplace
In Claude Code, run:

```bash
/plugin marketplace add makenotion/claude-code-notion-plugin
```

### 2. Install the plugin

```bash
/plugin install notion-workspace-plugin@notion-plugin-marketplace
```

### 3. Restart Claude Code  
This ensures the MCP server starts correctly.

---

## Authentication

The Notion MCP server supports **OAuth**!

---

## Credits

- **Notion Skills** by Notion
- **MCP Server** by Notion  
- **Plugin Specification** by Anthropic
- **Kingdom OS Framework** based on Order of Kings and Second Brain methodologies
- **MFR Framework** based on Estica Learner Centre Operational Control Framework MFR-2026-V1
