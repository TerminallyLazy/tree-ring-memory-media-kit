# Creator Brief

## Demo Angle

Show Tree Ring Memory as the missing local lifecycle layer between "the agent forgot everything" and "the agent kept a transcript dump forever."

## 60-Second Script

Tree Ring Memory is a local-first memory lifecycle layer for AI agents.

It is not a vector database or a hosted memory service. It is a Rust CLI that lets an agent or operator explicitly remember useful lessons, recall scoped project context, attach source-linked evidence, audit sensitive or stale records, consolidate older memories, and forget things on purpose.

The model borrows from tree rings. Fresh context stays detailed. Older learning compresses into rings. Important negative lessons become scars. Durable truths become heartwood. Future ideas stay as seeds.

Install it with one command, initialize a local SQLite store, write a lesson, recall it, and open the terminal UI.

## Demo Commands

```bash
curl -fsSL https://raw.githubusercontent.com/TerminallyLazy/Tree-Ring-Memory/main/install.sh | sh
tree-ring init
tree-ring remember "Use project-scoped recall before risky release changes." \
  --event-type lesson \
  --scope project \
  --project demo-service \
  --tag release
tree-ring recall "release changes" --project demo-service
tree-ring evidence "A test run proved the new workflow fixed stale recall." \
  --outcome promoted \
  --evidence-ref evals/recall/run-042
tree-ring audit --audit-type sensitive
tree-ring tui
```

## B-Roll Checklist

- Installer command.
- `tree-ring init` creating local project memory.
- `tree-ring remember` writing a lesson.
- `tree-ring recall` showing scoped recall.
- `tree-ring evidence` attaching an evaluated outcome.
- `tree-ring audit` showing operator review.
- `tree-ring tui` terminal console.
- Website landing page.
- GitHub release page.
- Agent skill listing.

## Talking Points

- Local-first: no required cloud service.
- Framework-agnostic: not tied to one agent harness.
- Lifecycle model: remember, age, consolidate, audit, forget.
- Transparent storage: local SQLite/FTS.
- Operator control: explicit forget/redact/audit flows.
- Protocol-preview: feedback wanted before deeper adapters land.

## What Not To Claim

- Do not claim Tree Ring Memory is a complete autonomous agent framework.
- Do not claim it replaces vector search in every workflow.
- Do not claim it is production-hardened enterprise software yet.
- Do not claim it automatically makes agent memory safe; the value is lifecycle policy plus operator controls.
