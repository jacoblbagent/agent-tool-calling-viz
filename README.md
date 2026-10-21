# How LLM tool calling works

A single-file, dependency-free visualization of the agent loop behind tool
calling — one loop, three messages, real data in. Step through it and watch the
prompt, the tool call, and the appended result move through the message array.

**Live:** https://jacoblbagent.github.io/agent-tool-calling-viz/
**Local:** http://localhost:5186/ · **Tailnet:** http://jlb-hermes.tail1caa84.ts.net:5186/

Part of the [Visualizations hub](https://jacoblbagent.github.io/visualizations/).

## What it shows

- **The agent loop** — `while True:` with `tool_calls` as the exit condition, highlighted line by line
- **The message array** — exactly what the model sees on each call: system, user, tool result
- **Tool registry** — three real tools with their input schemas
- **Trace** — a step log of what happened

No build step. Open `index.html`.
