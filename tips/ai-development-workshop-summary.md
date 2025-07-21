# AI Development Workshop Summary (for Technical Team)

*Workshop taught by **John Lindquist** of Egghead.io on **Friday, July 18th**.*

---

## 🧠 Agent Workflow Philosophy

- **Limit sessions to 3–5 commit-worthy steps**
  → Then start a new chat. Keeps agents sharp and focused.
- **Have the agent ask *you* questions**
  → Prompt it to ask 3 clarifying questions to externalize your thinking.
- **Use a “search report” pattern**
  → Run `@web` to gather public context before coding.

---

## 🤖 Claude Code vs. Cursor

| Use Case                            | Cursor            | Claude Code     |
|------------------------------------|-------------------|-----------------|
| Iterative, hands-on coding         | ✅ Yes            | 🚫 No           |
| "Set it and forget it" automation  | 🚫 No             | ✅ Yes          |

---

## 🧰 Tooling & MCP Ecosystem

### Agent Tools & MCPs

| Tool / MCP               | Purpose                                       |
|--------------------------|-----------------------------------------------|
| **Warp**                 | Agentic terminal for interactive shell work   |
| **Superwhisper**         | High-accuracy voice-to-text input             |
| **supermemory.ai**       | Long-term memory store for agents             |
| **deepwiki mcp**         | Contextual graph (Devin-style) for projects   |
| **grep mcp**             | GitHub/Vercel code search wrapper             |
| **basic-memory**         | Wraps Markdown/Obsidian notes into memory     |
| **n8n.io**               | Workflow automation via agents (low-code)     |

> ✅ Create project-specific MCPs for your CLI workflows.

---

## 🛠 VS Code Productivity Boosters

- **🔍 VSCode Search Editor** – *#1 thing to master*. Enables multi-file editing.
- **📄 `advanced-new-file` extension** – Fast file creation with nested paths.
  → [Install here](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)

---

## 📏 Agent Rule Design

- **Start with no rules.**
- Add rules *reactively*, as the agent fails—not preemptively.

---

## 🎥 Video Prompting for AI Studio

- Use **CleanShot** to record video demos
- Upload to **Google AI Studio** for multimodal prompting

---

### 🔑 Final Tip
> “**Learn the VS Code Search Editor—everything else is an accelerant.**”

---

Let me know if you want a quick pairing session on Cursor, Warp, or setting up custom MCPs.