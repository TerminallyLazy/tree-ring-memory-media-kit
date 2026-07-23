# Tree Ring Memory Media Kit

Public launch collateral for [Tree Ring Memory](https://github.com/TerminallyLazy/Tree-Ring-Memory), a framework-agnostic, local-first memory lifecycle layer for AI agents.

This repository is the clean public kit for journalists, newsletter editors, directory maintainers, demo creators, and community moderators. The canonical source code, releases, docs, and feedback thread live in the main project:

- Website: <https://terminallylazy.github.io/Tree-Ring-Memory/>
- Source repo: <https://github.com/TerminallyLazy/Tree-Ring-Memory>
- Release: <https://github.com/TerminallyLazy/Tree-Ring-Memory/releases/tag/v0.13.0>
- Launch feedback: <https://github.com/TerminallyLazy/Tree-Ring-Memory/issues/26>
- Launch discussion: <https://github.com/TerminallyLazy/Tree-Ring-Memory/discussions/27>
- Agent skill listing: <https://agent-skills.md/skills/TerminallyLazy/tree-ring-memory-skill/tree-ring-memory>
- HeyClaude source listing: <https://github.com/JSONbored/awesome-claude/blob/main/content/skills/tree-ring-memory.mdx>

## One-Liner

Tree Ring Memory is a framework-agnostic memory lifecycle layer for AI agents.

## Short Description

Tree Ring Memory helps agents remember useful decisions, warnings, preferences, and lessons without turning memory into transcript dumps. Fresh memory stays detailed, older memory compresses into rings, important scars remain visible, and durable truths become heartwood.

## Proof Points

- Local-first by default; no required cloud service.
- Rust-native public runtime.
- SQLite/FTS storage with scoped recall filtering.
- Explainable recall with ring, scope, confidence, and ranking factors.
- First-class forgetting, redaction, supersession, audit, and maintenance.
- Deterministic consolidation without requiring an LLM.
- Source-linked evidence records for evaluated outcomes.
- DOX and Revolve sync adapters.
- Agent-framework discovery.
- Ratatui terminal operator console.

## Try It

```bash
curl -fsSL https://raw.githubusercontent.com/TerminallyLazy/Tree-Ring-Memory/main/install.sh | sh
tree-ring init
tree-ring remember "Use project-scoped recall before risky release changes." --event-type lesson --scope project
tree-ring recall "release changes"
tree-ring tui
```

## Media Assets

| Asset | Use |
| --- | --- |
| [`assets/tree-ring-memory-logo.png`](assets/tree-ring-memory-logo.png) | Source logo |
| [`assets/tree-ring-memory-banner.png`](assets/tree-ring-memory-banner.png) | Wide brand banner |
| [`assets/open-graph-1200x675.png`](assets/open-graph-1200x675.png) | Link previews and newsletters |
| [`assets/social-square-logo-1080x1080.png`](assets/social-square-logo-1080x1080.png) | Profile images and square cards |
| [`assets/social-square-banner-1080x1080.png`](assets/social-square-banner-1080x1080.png) | Square launch graphic |
| [`assets/x-header-1500x500.png`](assets/x-header-1500x500.png) | X/Twitter header |
| [`assets/reddit-link-card-1600x900.png`](assets/reddit-link-card-1600x900.png) | Reddit/social link card |
| [`assets/youtube-thumbnail-1920x1080.png`](assets/youtube-thumbnail-1920x1080.png) | YouTube thumbnail |
| [`assets/youtube-channel-banner-2560x1440.png`](assets/youtube-channel-banner-2560x1440.png) | YouTube channel banner |
| [`assets/ratatui-tui-screenshot-1200x675.png`](assets/ratatui-tui-screenshot-1200x675.png) | Terminal UI screenshot |

## Launch Copy

- [`press.md`](press.md): press kit, boilerplate, headline options, FAQ.
- [`social-posts.md`](social-posts.md): Hacker News, Reddit, X, Bluesky, Mastodon, LinkedIn, and YouTube copy.
- [`creator-brief.md`](creator-brief.md): demo angle, 60-second script, commands, and B-roll checklist.

## Attribution

Tree Ring Memory is inspired by the spatial project-memory patterns in [DOX](https://github.com/agent0ai/dox) and the evidence-driven improvement loop in [Revolve](https://github.com/agent0ai/revolve), with a deliberate nod to their original creator, [frdel](https://github.com/frdel). Tree Ring Memory is framework-agnostic and does not replace either protocol.

## License

The collateral in this repository is released under the same license as the Tree Ring Memory project. See [`LICENSE`](LICENSE).
