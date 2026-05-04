# agent-creator

A skill for any AI coding tool that turns your scattered skills into agents you can talk to, with almost no input required.

---

## The problem

You have skills. But every time you need one, you have to remember it exists, figure out which one fits, and invoke it manually. The more skills you have, the worse this gets.

## The fix

Wrap your skills in agents. Each agent has a clear identity and knows which skills it can use. Your main conversation detects the right agent automatically. You just talk.

`agent-creator` is the skill that builds those agents for you.

---

## How it works

Just say what you want. The skill reads your project and does the rest.

**Mode 1 — Guided:** Describe what you need in plain language. The skill asks one question at a time and generates a complete agent file when it has enough.

**Mode 2 — Auto:** The skill scans every skill in your project, infers your technical direction and work habits, and proposes 3–5 agent recommendations tailored to your actual setup — each pre-configured with the right skills. You pick from a list. No long descriptions needed.

Either way, the agent file lands in the right directory for your platform and scope, and your config is updated so the main conversation knows when to call it.

---

## Installation

Copy `SKILL.md` into your AI tool's skills directory. Most platforms support both project-level and global placement:

- **Project-level** (current project only): `.your-tool/skills/agent-creator/SKILL.md`
- **Global** (all projects): `~/.your-tool/skills/agent-creator/SKILL.md`

Replace `.your-tool` with the config directory your platform uses — for example `.claude` for Claude Code or `.codex` for Codex. Check your platform's documentation for the exact path.

---

## Usage

Start in your project directory, then say anything like:

```
Help me create an agent
```
```
Build agents from my existing skills
```

The skill activates automatically and takes it from there.

---

## License

MIT
