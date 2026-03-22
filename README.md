## Aamir Shahzad

Software engineer. I build AI tools and work on retrieval systems, data pipelines, and backend infrastructure.

---

### What I'm Working On

**[mnemonic-ai](https://github.com/Aamirofficiall/mnemonic)** — Persistent memory for AI coding agents.

Most memory tools are glorified vector stores. They work fine for 50 facts, then fall apart — duplicates pile up, stale context poisons results, and everything scores the same. mnemonic-ai takes a different approach: multi-signal search with rank fusion, reinforcement-based memory decay, an auto-extracted knowledge graph, and bi-temporal contradiction handling. All backed by SQLite — no infrastructure to manage.

```
npm install -g mnemonic-ai
```

Works with Claude Code, Cursor, Windsurf, and any MCP-compatible client. 16 CLI commands, 12 MCP tools, Apache-2.0.

---

### Other Work

**[rag-playbook](https://github.com/Aamirofficiall/rag-playbook)** — A benchmarking framework for RAG retrieval patterns. Compare naive, hybrid search, reranking, parent-child, query decomposition, HyDE, self-correcting, and agentic pipelines — with real latency, cost, and relevance numbers. `pip install rag-playbook`

---

### Writing

I write about failure modes in production AI systems and how to fix them — [aamirshahzad.uk/notes](https://aamirshahzad.uk/notes)

- [Which LLM For Which Task (And Why I Didn't Self-Host)](https://aamirshahzad.uk/notes/which-llm-for-which-task)
- [Controlling 20,000 Requests Without Burning Money](https://aamirshahzad.uk/notes/request-cost-control-llm)
- [How Did One Failed Request Turn Into 3,000?](https://aamirshahzad.uk/notes/retry-storms)

---

Python · Django · FastAPI · PostgreSQL · Celery · Redis · AWS · RAG Pipelines · React · TypeScript
