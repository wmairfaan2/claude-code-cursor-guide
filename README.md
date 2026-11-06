# Claude Code in Cursor: Beginner Guide

> A step-by-step study guide for beginners learning to code with [Claude Code](https://code.claude.com/docs) inside the [Cursor](https://cursor.com) editor.

## 📄 Read the guide

**[Claude-Code-in-Cursor-Beginner-Guide.pdf](docs/Claude-Code-in-Cursor-Beginner-Guide.pdf)** (12 pages)

Work through the lessons in order. Each one ends with a checklist so you can track your progress.

| # | Lesson | You'll learn |
|---|--------|--------------|
| 1 | Key ideas | What Cursor, Claude Code, CLAUDE.md, subagents and skills are |
| 2 | Install everything | Installing the Claude Code CLI and the Cursor extension on Windows |
| 3 | Connect to Cursor | Using `claude` in the terminal, `/ide`, and the chat panel |
| 4 | Organize your project | Folder layout, `CLAUDE.md`, settings, what to commit |
| 5 | Talk to Claude | Good prompts, `@file`, `!command`, modes (Shift+Tab), stopping with Esc |
| 6 | Slash commands | The commands to learn first: `/init`, `/clear`, `/plan`, `/diff`, `/code-review`, `/rewind`… |
| 7 | Review & undo | Accepting or rejecting diffs, `/rewind`, using git as a safety net |
| 8 | Subagents | Creating helper agents in `.claude/agents/` |
| 9 | Custom commands | Making your own `/commands` with skills |
| 10 | Daily workflow | Explore → plan → code → review → commit |

It ends with a cheat sheet, practice exercises and links to the official docs.

## What's in this repo

```text
├── docs/
│   └── Claude-Code-in-Cursor-Beginner-Guide.pdf   # The study guide
├── .claude/
│   └── agents/
│       └── researcher.md                          # Example subagent (read-only researcher)
├── CLAUDE.md                                      # Project notes Claude Code reads each session
└── README.md                                      # This file
```

## Try the example subagent

Clone the repo, open it in Cursor, and start Claude Code in the terminal:

```bash
git clone https://github.com/wmairfaan2/claude-code-cursor-guide.git
cd claude-code-cursor-guide
claude
```

Then ask: *"Use the researcher agent to explain how CLAUDE.md works."*

## A note on accuracy

The guide was researched from the official Claude Code and Cursor docs in November 2026. Both tools update often, so if something looks different, check `/help` and `claude --version`, or the [official docs](https://code.claude.com/docs).

## License

No license has been chosen yet, so all rights are reserved by default.

## Contact

Maintainer: [wmairfaan2](https://github.com/wmairfaan2)
