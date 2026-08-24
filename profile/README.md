# Willow · Memory

### Agent memory that doesn't rot — local-first, human-governed, manifest-authorized.

> The machine proposes; you ratify. Memory lives on hardware you control, in formats you can read and delete, exposed through tools that ask permission before they write.

Willow is the **platform seat** for the fleet: persistent memory (SOIL store + Postgres knowledge base), sandboxed task execution (Kart), Grove messaging, and an MCP server any agent client can attach to. Every tool call is authorized through filesystem manifests — no ACL database, no external auth service.

Nothing here phones home. Nothing here trains on your corpus. The record is yours to keep, export, and delete.

---

## What's inside

| | |
|---|---|
| **[willow-mcp](https://github.com/willow-memory/willow-mcp)** | The shipped MCP hub — SOIL, KB, Kart, Grove, governance tools. `pip install willow-mcp` |
| **[kartikeya](https://github.com/willow-memory/kartikeya)** | Standalone bwrap-sandboxed task queue + worker (Kart extracted) |
| **[willow-gate](https://github.com/willow-memory/willow-gate)** | Manifest and auth gate for the platform bundle |
| **[Willow](https://github.com/willow-memory/Willow)** | Fleet constitution — registry, envelopes, governance proposals |
| **[safe-app-willow-grove](https://github.com/willow-memory/safe-app-willow-grove)** | Grove fleet bus (Heimdallr seat) |
| **[corpus-lens](https://github.com/willow-memory/corpus-lens)** | Local-first process lens over your own human+agent corpus |

---

## The promise

- **Local-first.** Postgres and SQLite on your machine; cloud optional.
- **Human-governed.** Writes are gated; sessions expire; attestations are explicit.
- **Durable.** Hash-chained ledgers, schema maps, and receipts — decay surfaces loudly.

**Tools, not traps.**

---

## Part of something larger

Willow is the **Willow · Memory** face of **[Die-Namic-Systems](https://github.com/Die-Namic-Systems)** — verification at the center ([Nestor](https://github.com/Die-Namic-Systems/Nestor)), with sibling faces for learning ([hornbook-knowledge](https://github.com/hornbook-knowledge)), public data ([almanac-data](https://github.com/almanac-data)), household affairs ([homestead-affairs](https://github.com/homestead-affairs)), craft ([forge-play](https://github.com/forge-play)), and programs ([terpsi-programs](https://github.com/terpsi-programs)).

---

## Licensing

Apache-2.0 for platform code unless a repository states otherwise. Each LICENSE file is authoritative.

---

<sub>Memory that knows when it's slipping. ΔΣ = 42.</sub>
