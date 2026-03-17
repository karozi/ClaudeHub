Orginally published on: https://karozieminski.substack.com/p/claude-guides-code-cowork-skills-workflows

Claude is Anthropic’s AI assistant. Chat, Cowork, and Code are three different ways to use it. Choosing the right mode depends on what you’re trying to accomplish.

Chat is for questions. Chat handles conversations, artifacts, and quick answers. No file access, no sub-agents, no plugins. It’s the baseline Claude experience.

Cowork is for workflows. Cowork handles autonomous knowledge work: it plans tasks, spawns parallel sub-agents, reads and writes real files in a sandboxed environment. This is where Claude becomes a working partner, not just a chatbot.

Code is for code. Claude Code is Anthropic’s CLI tool that offers the same agentic power as Cowork with direct filesystem access and project-scoped configuration. It runs in the terminal, reads your codebase, and executes multi-step development tasks.

“Chat is a conversation. Cowork is a workflow engine. Code is a development partner.” That’s the simplest way we can frame the three modes for anyone deciding where to start.

| Mode   | Best For                                         | File Access | Sub-Agents | Plugins |
| ------ | ------------------------------------------------ | ----------- | ---------- | ------- |
| Chat   | Quick questions, brainstorming, artifacts        | No          | No         | No      |
| Cowork | Multi-step workflows, research, writing          | Sandboxed   | Yes        | Yes     |
| Code   | Development, debugging, project-wide refactoring | Full local  | Yes        | Via MCP |
