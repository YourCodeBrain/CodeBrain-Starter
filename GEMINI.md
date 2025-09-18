---
role: "Gemini CLI"
owner: "You"
workspace: "[CodeBrain Starter](https://www.yourcodebrain.com/starter)"
---

# Gemini System Guide

Use this file to brief Gemini CLI and Obsidian.

## Folder Overview
- `0-Inbox/` – quick capture, raw ideas, voice transcripts
- `1-Projects/` – active project plans; one file per initiative
- `2-Clients/` – client dossiers + histories
- `3-Daily/` – schedules, logs, end-of-day reflections
- `4-Resources/` – evergreen notes, research, SOPs
- `5-Reviews/` – weekly/quarterly reflections
- `Archives/` – finished or dormant work
- `Templates/` – placeholder for your personal snippets

## Naming & Linking
- Create new files as `YYYY-MM-DD-title.md` or `topic-name.md`.
- MUST Use wiki links (`[[client-acme-overview]]`) so Obsidian autocompletes connections.
- Reference files with relative paths: `[Project Brief](../1-Projects/project-acme.md)`.
- MUST Add YAML headers:
  ```yaml
  ---
  owner: "You"
  status: "active"
  tags: [client, q4]
  ---
  ```

## Gemini CLI usage
- Summaries: `gemini summary 1-Projects/project-acme.md`
- Rewrite: `gemini rewrite 0-Inbox/meeting-notes.md --style="concise"`
- Query: `gemini query "Which notes mention onboarding?"`
- Free tier ≈ 60 requests/min and ~1,000/day on model 2.5 Pro. Pace your commands.

## Working in Obsidian
- Set this folder as an Obsidian vault for local navigation.
- Use the Dashboard (`000-Dashboard.md`) as your home note.
- Enable core plugins you like (backlinks, graph) but the system works without them.

## Manual Workflow
1. Capture into `0-Inbox`.
2. Process and move notes into their long-term folder.
3. Link related notes using wiki links or Markdown relative paths.
4. Run weekly reviews in `5-Reviews` to close loops.

## Upgrading
When you need automations, Planning mode, or Rube MCP workflows, grab the [CodeBrain Pro Kit](https://www.yourcodebrain.com/buy) and join the community (trial included) for deeper support.
