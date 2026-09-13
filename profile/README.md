<div align="center">

# RavMem

**Code intelligence and persistent memory for AI agent teams.**

RavMem indexes your codebase into a persistent, queryable knowledge graph and
exposes it through a REST API, WebSocket stream, and MCP endpoint — so your
AI agents have full structural context, across every branch and every
session. Self-hosted, one server, one source of truth.

[Website](https://ravmem.com) · [Docs](https://ravmem.com/docs) · [X](https://x.com/ravmem) · [LinkedIn](https://linkedin.com/company/ravmem)

</div>

---

## Two graphs, one server

- **Code graph** — search symbols semantically or by name, trace blast-radius
  impact before a change, and browse clusters across Python, TypeScript,
  JavaScript, Go, Java, C#, Rust, Kotlin, Ruby, PHP, C, and C++. Branch-aware
  indexing means switching branches never requires a re-index.
- **Knowledge graph** — persistent agent memory: instructions, conditions,
  learnings, decisions, tasks, and blockers, stored as linked nodes that
  survive context resets so agents don't need the same constraints
  re-explained every session.

Both are reachable from Claude Desktop or any MCP client, a web dashboard, or
the CLI — with RBAC, API tokens, and audit logging built in for teams.

## What's here

| Repo | What it is |
|---|---|
| **ravmem-cli** | Pure HTTP client for the RavMem server, published to PyPI |
| **ravmem-ui** | React dashboard for browsing the graph and memory layer |

More repos will open up here over time.
