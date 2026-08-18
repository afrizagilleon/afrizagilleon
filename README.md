## Afriza Gilleon Ginting

I build execution infrastructure for AI agents — the layer between a model and
the systems it is supposed to operate.

Software engineering student at Telkom University. Available for freelance work
in automation, MCP tooling, and browser automation.

---

### What I'm building

**[zaatool](https://github.com/afrizagilleon/zaatool)** — Notebook-first workflow
orchestration for humans and AI agents.
Workflows are ordered cells sharing one scope, not node graphs. One notebook
definition becomes three things at once: a UI page, an HTTP endpoint, and a tool
an agent can call. Exposes 13 MCP tools, with etag-guarded cell edits so two
writers cannot silently overwrite each other.
`React 19` `Express 5` `PostgreSQL` `MCP`

**[rewind-bench](https://github.com/afrizagilleon/rewind-bench)** — A benchmark
separating repairs that passed from repairs that held up.
Bugs are injected by AST mutation; every accepted repair is re-run against a
hidden second dataset. Repairs that only match the observed data are flagged as
lucky passes. It found that **7% of accepted repairs from the best-equipped agent
were fake** — they matched recorded output and broke on new inputs. 297 recorded
episodes; every number regenerates from committed data with no inference spend.
`TypeScript` `AST (Acorn)` `Vitest` `MCP`
[Read the report →](https://afrizagilleon.github.io/rewind-bench/)

**[nb-steprunner](https://github.com/afrizagilleon/nb-steprunner)** — Any web page,
as a Jupyter-style notebook.
Write and run JavaScript cells against the live DOM with shared state. Checkpoints
survive page reloads, so a long automation resumes from its last successful step
instead of starting over. Reaches into cross-origin iframes, and runs on sites
whose Content-Security-Policy blocks eval.
`Preact` `Vite` `CodeMirror 6`

---

### How I work

I document what my tools cannot do as carefully as what they can. On rewind-bench
my preferred approach won 30/30 against 28/30 — while burning 3.7x more tokens,
so I reported both numbers. I would rather you plan around a real limit than
discover it in production.

---

**Certified:** IBM RAG and Agentic AI · Google IT Automation with Python (2026)
**Reach me:** [LinkedIn](https://www.linkedin.com/in/afrizagilleon/) · afriza.gilleon@gmail.com
