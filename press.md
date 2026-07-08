# Press Kit

## Product

Tree Ring Memory

## Category

Developer tool, AI agent infrastructure, local-first memory lifecycle.

## Boilerplate

Tree Ring Memory is a framework-agnostic memory lifecycle layer for AI agents. It provides a Rust-native CLI, local SQLite/FTS storage, scoped recall, audit, consolidation, explicit forgetting, source-linked evidence, DOX/Revolve adapters, framework discovery, and a Ratatui terminal console.

## What It Solves

Agent memory often fails in one of two ways: it forgets useful lessons too quickly, or it hoards raw transcripts until recall becomes noisy and unsafe. Tree Ring Memory treats memory as a lifecycle. Fresh context stays detailed, older learning compresses, negative lessons remain visible as scars, durable truths become heartwood, and future hypotheses stay as seeds.

## Launch Links

- Website: <https://terminallylazy.github.io/Tree-Ring-Memory/>
- GitHub: <https://github.com/TerminallyLazy/Tree-Ring-Memory>
- Release: <https://github.com/TerminallyLazy/Tree-Ring-Memory/releases/tag/v0.11.0>
- Feedback thread: <https://github.com/TerminallyLazy/Tree-Ring-Memory/issues/26>
- Discussion: <https://github.com/TerminallyLazy/Tree-Ring-Memory/discussions/27>
- Agent skill listing: <https://agent-skills.md/skills/TerminallyLazy/tree-ring-memory-skill/tree-ring-memory>

## Headline Options

- Tree Ring Memory launches local-first memory lifecycle tooling for AI agents
- A Rust CLI for AI agent memory that ages, audits, and forgets
- Tree Ring Memory turns agent memory from transcript storage into lifecycle infrastructure

## Short Pitch

Tree Ring Memory is a local-first Rust CLI for AI agent memory. It lets agents record durable lessons, recall scoped project context, attach evidence, audit sensitive or stale records, consolidate older memory, and forget explicitly without sending memory to a hosted service.

## Longer Pitch

Tree Ring Memory gives AI agents an inspectable memory substrate that can live beside any framework. The current public runtime is Rust-native and stores data locally in SQLite/FTS. Operators can capture decisions, lessons, warnings, preferences, and evidence; recall them with project and tag filters; audit or redact sensitive records; consolidate older memory deterministically; sync from DOX and Revolve sources; and review the store through a terminal UI.

## FAQ

### Is this a vector database?

No. Tree Ring Memory is a memory lifecycle and policy layer: capture, scope, age, consolidate, audit, recall, and forget. Vector search can become an adapter, but it is not the memory policy.

### Is this an agent framework?

No. It is framework-agnostic infrastructure intended to sit beside agent frameworks and coding-agent workflows.

### Is this hosted?

No. The public runtime is local-first. It does not require a cloud service.

### What is protocol-preview status?

The CLI and core concepts are usable, but deeper first-class adapters for more agent harnesses are still being shaped through feedback.

### Why tree rings?

The model gives memory an intuitive lifecycle: active cambium, older rings, scars, durable heartwood, and seeds for future work.

## Quotes

> Agent memory should not be a transcript landfill. It should age, compress, keep the scars that matter, and let operators forget.

> Tree Ring Memory is deliberately framework-agnostic: the memory substrate should be portable across agents, not trapped inside one harness.

## Contact

Use the launch feedback issue for public questions and integration requests:
<https://github.com/TerminallyLazy/Tree-Ring-Memory/issues/26>
