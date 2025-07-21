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
| **[Warp](https://www.warp.dev/)**                 | Agentic terminal for interactive shell work   |
| **[Superwhisper](https://superwhisper.com/)**         | High-accuracy voice-to-text input             |
| **[supermemory.ai](https://supermemory.ai/)**       | Long-term memory store for agents             |
| **[deepwiki mcp](https://deepwiki.com/)**         | Contextual graph (Devin-style) for projects   |
| **[grep mcp](https://grep.app/)**             | GitHub/Vercel code search wrapper             |
| **[basic-memory](https://basicmemory.com/)**         | Wraps Markdown/Obsidian notes into memory     |
| **[n8n.io](https://n8n.io/)**               | Workflow automation via agents (low-code)     |

> ✅ Create project-specific MCPs for your CLI workflows.

---

## 🛠 VS Code Productivity Boosters

- **🔍 [VSCode Search Editor](https://code.visualstudio.com/docs/editing/codebasics#_search-editor)** – *#1 thing to master*. Enables multi-file editing.
- **📄 [`advanced-new-file` extension](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)** – Fast file creation with nested paths.
  → [Install here](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)

---

## 📏 Agent Rule Design

- **Start with no rules.**
- Add rules *reactively*, as the agent fails—not preemptively.

---

## 🎥 Video Prompting for AI Studio

- Use **[CleanShot](https://cleanshot.com/)** to record video demos
- Upload to **[Google AI Studio](https://aistudio.google.com/)** for multimodal prompting

---

### 🔑 Final Tip
> “**Learn the VS Code Search Editor—everything else is an accelerant.**”

---

Let me know if you want a quick pairing session on Cursor, Warp, or setting up custom MCPs.