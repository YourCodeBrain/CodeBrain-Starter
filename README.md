---
title: "CodeBrainStarter"
updated: 2025-09-18
---

[← Back to Dashboard](../000-Dashboard.md)

# [CodeBrain Starter](https://www.yourcodebrain.com/starter) (Gemini Edition)

A lightweight vault structure to capture work, projects, and reviews using the Gemini CLI. It mirrors the core CodeBrain layout without the proprietary automations found in the Pro Kit.

## What’s inside

```
CodeBrainStarter/
├─ 0-Inbox/
├─ 1-Projects/
├─ 2-Clients/
├─ 3-Daily/
├─ 4-Resources/
├─ 5-Reviews/
├─ Archives/
├─ Templates/ (empty – add your own)
├─ GEMINI.md
└─ README.md
```

- **GEMINI.md** – System instructions you can reference in Gemini CLI sessions.
- **0-5 folders** – Opinionated structure for capture, project work, client management, and reviews.
- **Templates/** – left empty so you can drop personal prompts/snippets.
- **Archives/** – park completed work here to keep the main folders lean.

## Getting started

1. Clone or download this repository.
   ```bash
   git clone https://github.com/SLBergeron/CodeBrain-Starter.git
   ```
2. Install the [Gemini CLI](https://ai.google.dev/gemini-api/docs/quickstart?hl=en#command_line).
3. Point your CLI to this folder and run commands:
  ```bash
  gemini summary 1-Projects/sample-project.md
  gemini rewrite 0-Inbox/meeting-notes.md --style="concise"
  ```
4. Move files from `0-Inbox` into their long-term home (Projects, Clients, etc.) after processing.
5. Update `GEMINI.md` to reflect your personal preferences.

## Why Gemini?

- Free quota (~60 requests/min, ~1,000/day on model 2.5 Pro).
- Fast for summarizing, rewriting, and querying your notes.
- No setup required beyond the CLI.

When you’re ready for automations, Planning mode, and Rube MCP workflows, upgrade to the [[CodeBrain Pro Kit](https://www.yourcodebrain.com/)](https://www.yourcodebrain.com/). It includes:
- Claude Code workflows + Planning mode scripts
- Rube MCP pipelines for Drive
- Premium templates, dashboards, and community support (7-day trial included)

## License

Released under the MIT License – see `LICENSE`.

## Questions & support

- Open an issue or discussion in this repo.
- Join the [CodeBrain Community](https://www.yourcodebrain.com/) (trial included with your CodeBrain purchase) for office hours, walkthroughs, and advanced templates.
