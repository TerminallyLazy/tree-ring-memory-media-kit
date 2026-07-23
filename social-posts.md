# Social Posts

These drafts are for owner-controlled accounts. Disclose affiliation, follow each community's current rules, and do not coordinate voting.

## Hacker News

Title:

```text
Show HN: Tree Ring Memory - memory lifecycle for AI agents
```

URL:

```text
https://terminallylazy.github.io/Tree-Ring-Memory/
```

First comment:

````markdown
Hi HN, I built Tree Ring Memory because most agent memory systems I have used either forget too aggressively or turn into transcript dumps.

The model is deliberately simple:

- fresh work stays detailed
- older learning compresses into rings
- important negative lessons become scars
- durable truths become heartwood
- speculative follow-ups stay as seeds

The public runtime is Rust-native: CLI, SQLite/FTS storage, recall, audit, forgetting, deterministic consolidation, maintenance, DOX/Revolve sync adapters, framework discovery, and a Ratatui terminal console.

It is protocol-preview software, not a hosted service. I am looking for feedback from people building agent workflows: what should a portable, local-first memory layer get right before deeper framework adapters land?

Install:

```bash
curl -fsSL https://raw.githubusercontent.com/TerminallyLazy/Tree-Ring-Memory/main/install.sh | sh
tree-ring init
tree-ring remember "Use project-scoped recall before risky release changes." --event-type lesson --scope project
tree-ring recall "release changes"
```

Repo: https://github.com/TerminallyLazy/Tree-Ring-Memory
Release: https://github.com/TerminallyLazy/Tree-Ring-Memory/releases/tag/v0.13.0
Agent skill listing: https://agent-skills.md/skills/TerminallyLazy/tree-ring-memory-skill/tree-ring-memory
````

## Reddit: r/rust

Title:

```text
I built a Rust-native CLI for local AI agent memory lifecycle
```

Body:

````markdown
I built Tree Ring Memory, a Rust-native local memory lifecycle layer for AI agents.

The Rust workspace owns the public runtime: CLI, SQLite/FTS storage, recall filtering, JSONL import/export, audit, deterministic consolidation, maintenance, DOX/Revolve source adapters, framework discovery, and a Ratatui operator console.

The idea is not "store every chat." It is memory aging:

- fresh task context stays detailed
- older learning compresses into rings
- failures/regressions become scars
- durable facts become heartwood
- future hypotheses stay as seeds

Repo:
https://github.com/TerminallyLazy/Tree-Ring-Memory

Release:
https://github.com/TerminallyLazy/Tree-Ring-Memory/releases/tag/v0.13.0

Install:

```bash
curl -fsSL https://raw.githubusercontent.com/TerminallyLazy/Tree-Ring-Memory/main/install.sh | sh
tree-ring init
tree-ring tui
```

I would value feedback on the Rust CLI/storage shape, the SQLite/FTS approach, and what should stay deterministic versus adapter-driven.
````

## Reddit: r/LocalLLaMA

Title:

```text
Local-first memory lifecycle for AI agents, without transcript dumping
```

Body:

```markdown
I built Tree Ring Memory for local/private agent workflows where "memory" should not mean uploading transcripts or keeping every chat forever.

It is a framework-agnostic Rust CLI with local SQLite/FTS storage. Agents can remember durable lessons, recall project-specific context, record evidence from evaluations, audit sensitive/stale memory, consolidate older records, and forget or redact memory explicitly.

The model is tree-ring based: cambium for fresh active context, rings for compressed older learning, scars for negative lessons, heartwood for durable truths, and seeds for unresolved future ideas.

Repo:
https://github.com/TerminallyLazy/Tree-Ring-Memory

Website:
https://terminallylazy.github.io/Tree-Ring-Memory/

I am looking for feedback from people running local agent stacks: what adapter or workflow would make this useful in your setup?
```

## X / Twitter Thread

1.

```text
Tree Ring Memory is a memory lifecycle layer for AI agents.

Not a vector DB.
Not transcript storage.
Not another agent framework.

It is local-first infrastructure for remembering, recalling, auditing, consolidating, and forgetting.
```

2.

```text
The model is tree-ring based:

cambium = fresh working memory
rings = compressed older learning
scars = negative lessons worth keeping visible
heartwood = durable truths
seeds = unresolved future ideas
```

3.

```text
The public runtime is Rust-native:

- CLI
- SQLite/FTS storage
- scoped recall
- import/export
- audit
- consolidation
- explicit forget/redact
- DOX/Revolve sync adapters
- Ratatui TUI
```

4.

```text
Try it:

curl -fsSL https://raw.githubusercontent.com/TerminallyLazy/Tree-Ring-Memory/main/install.sh | sh
tree-ring init
tree-ring tui

Repo:
https://github.com/TerminallyLazy/Tree-Ring-Memory
```

## Bluesky / Mastodon

```text
I launched Tree Ring Memory: a local-first memory lifecycle layer for AI agents.

It is a Rust CLI with SQLite/FTS recall, audit, consolidation, forgetting, source-linked evidence, DOX/Revolve adapters, and a Ratatui terminal UI.

The goal: useful agent memory without transcript dumping.

https://github.com/TerminallyLazy/Tree-Ring-Memory
```

## LinkedIn

```text
Tree Ring Memory is now public in protocol-preview status.

It is a framework-agnostic, local-first memory lifecycle layer for AI agents: Rust CLI, SQLite/FTS storage, scoped recall, source-linked evidence, audit, consolidation, forgetting, DOX/Revolve adapters, and a terminal UI.

The core idea is simple: agent memory should age. Fresh context stays detailed, older learning compresses, important negative lessons remain visible, durable truths become heartwood, and unresolved ideas stay as seeds.

Launch page:
https://terminallylazy.github.io/Tree-Ring-Memory/

Source:
https://github.com/TerminallyLazy/Tree-Ring-Memory
```

## YouTube

Title:

```text
Tree Ring Memory: local-first memory lifecycle for AI agents
```

Description:

```markdown
Tree Ring Memory is a framework-agnostic, local-first memory lifecycle layer for AI agents.

In this demo: install the Rust CLI, initialize a memory store, write a lesson, recall it, attach evidence, audit memory, and open the Ratatui terminal console.

Website:
https://terminallylazy.github.io/Tree-Ring-Memory/

Source:
https://github.com/TerminallyLazy/Tree-Ring-Memory

Launch feedback:
https://github.com/TerminallyLazy/Tree-Ring-Memory/issues/26
```
