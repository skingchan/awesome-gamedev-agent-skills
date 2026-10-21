# AI Long-Term Tutor · AI-LTS

A cross-domain [Agent Skills](https://agentskills.io/specification) skill for long-term **interactive** teaching, not merely generating study plans. Built from the 2026-10-15 AI-LTS v1.0 teaching framework. The seven example curricula are adaptations of previously planned long-term projects; they are not claims of course completion or private learner transcripts.

## What's in this skill

- `SKILL.md` — trigger metadata, mode routing, and mandatory teaching lifecycle.
- `references/teaching-standard.md` — full practical curriculum/lesson/continuity rules.
- `references/assessment-and-evidence.md` — assessments, five-level mastery rubric, Gate decisions and evidence hygiene.
- `assets/` — copyable project intake, curriculum, lesson and portable snapshot templates.
- `examples/` — seven grounded long-term training designs, each with scope, phases, artifacts, Gate and first diagnostic.

## Install

Copy the **entire folder** `ai-long-term-tutor` (including `assets/`, `references/` and `examples/`) to your agent's skills directory, for example:

- Codex, Gemini CLI, Copilot agent: `~/.agents/skills/ai-long-term-tutor/` or project-local `.agents/skills/ai-long-term-tutor/`
- Claude Code: `~/.claude/skills/ai-long-term-tutor/` or project-local `.claude/skills/ai-long-term-tutor/`
- Cursor: `.cursor/skills/ai-long-term-tutor/` or `.agents/skills/ai-long-term-tutor/`

These are example install locations, not a guarantee that every chat product can automatically load skills. For a general chatbot that does **not** load Agent Skills, paste `SKILL.md` as an instruction and attach the relevant reference/template and one example.

## Use

**New:** "使用 ai-long-term-tutor，为我规划【领域】的长期训练。我的最终能力目标是【目标】，已有基础【背景】。先诊断，再排课并逐课互动。"

**Continue:** "按照 ai-long-term-tutor，读取以下项目状态快照，从尚未完成的一步继续，不要重新排课。"

**Assessment:** "对本模块做独立能力 Gate 测试；先出题，等待我的实际回答，再依据证据判断。"

## Examples

See [examples/README.md](examples/README.md) for the seven programs:
software engineering, mathematics, English, Chinese history, keyboard, internet-business experimentation, and AI indie game development.

## Scope

This skill deliberately lives in the **extras** directory of a game-development skill repository. It is a self-contained, cross-domain add-on and does **not** alter the game's 74-skill router, bundles or engine-specific workflows. Install it separately when you want an AI to tutor rather than build a game for you.

License: the hosting repository's terms apply. Before copying it to a different licensed project, inspect the upstream license.
