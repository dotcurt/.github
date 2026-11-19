# .curt

One file, one conversation, kept whole.

.curt is an open, MIT-licensed file format for AI conversations — one
UTF-8 JSON file per conversation, full fidelity, strict whole-file
validation, conformance vectors run in CI. Born in Curtis AI Chat.
Owned by no one.

Site, docs, spec, and the `curt-format` npm package: [dotcurt.org](https://dotcurt.org) · X: [@curtformat](https://x.com/curtformat) · roadmap: [org project #1](https://github.com/orgs/dotcurt/projects/1) · questions: [discussions](https://github.com/dotcurt/dot_curt/discussions)

## Ecosystem

| Repo | What it does |
|---|---|
| [dot_curt](https://github.com/dotcurt/dot_curt) | The spec — TypeScript reference implementation, JSON Schema, conformance vectors |
| [curt-convert](https://github.com/dotcurt/curt-convert) | Claude Code session transcripts → `.curt` |
| [curt-codex](https://github.com/dotcurt/curt-codex) | OpenAI Codex CLI sessions ⇄ `.curt` |
| [curt-openclaw](https://github.com/dotcurt/curt-openclaw) | OpenClaw gateway transcripts → `.curt` |
| [curt-hermes](https://github.com/dotcurt/curt-hermes) | Hermes agent sessions ⇄ `.curt` |
| [curt-openwebui](https://github.com/dotcurt/curt-openwebui) | Open WebUI chats → `.curt` |
| [curt-wildchat](https://github.com/dotcurt/curt-wildchat) | WildChat-1M records → `.curt` |
| [curt-webext](https://github.com/dotcurt/curt-webext) | Export a live ChatGPT/Claude chat from the browser |
| [curt-openwith](https://github.com/dotcurt/curt-openwith) | Double-click any `.curt` — offline viewer for Win/macOS/Linux |
| [curt-vcon](https://github.com/dotcurt/curt-vcon) | `.curt` ⇄ IETF vCon container |
| [langchain-curt](https://github.com/dotcurt/langchain-curt) | LangChain chat loader |
| [curt-busabase](https://github.com/dotcurt/curt-busabase) | Busabase review trails → `.curt` |
| [wranglebot](https://github.com/leverframe/wranglebot) | Deterministic guardrails for coding agents — emits `.curt` decision records |
| [tractum](https://github.com/leverframe/tractum) | Verifiable multi-agent consensus — emits the `consensus-receipt` extension |

The argument for why this layer needs to exist: the preprint, DOI [10.5281/zenodo.23864677](https://doi.org/10.5281/zenodo.23864677).

## License

Everything MIT — spec, reference implementation, schema, fixtures, all of it.
