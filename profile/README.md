# .curt

**One file, one conversation, kept whole.**

`.curt` is an open, MIT-licensed file format for AI conversations:
one UTF-8 JSON file per conversation — full fidelity, strict
whole-file validation, and executable conformance vectors run in CI.

Born in Curtis AI Chat. Owned by no one.

| | |
|---|---|
| Site | <https://dotcurt.org> |
| Docs | <https://docs.dotcurt.org> |
| X | [@curtformat](https://x.com/curtformat) |
| Roadmap | [dotcurt/projects/1](https://github.com/orgs/dotcurt/projects/1) |
| Spec v1 | [dotcurt/dot_curt · SPEC.md](https://github.com/dotcurt/dot_curt/blob/main/SPEC.md) |
| npm | [`curt-format`](https://www.npmjs.com/package/curt-format) |
| Preprint | DOI [10.5281/zenodo.23864677](https://doi.org/10.5281/zenodo.23864677) |

## The ecosystem

**Reference**

- [`dot_curt`](https://github.com/dotcurt/dot_curt) — spec, TypeScript
  reference implementation, JSON Schema, conformance vectors

**Readers**

- [`curt-openwith`](https://github.com/dotcurt/curt-openwith) —
  double-click any `.curt`; offline viewer for Windows, macOS, Linux
- [`curt-webext`](https://github.com/dotcurt/curt-webext) — export a
  live ChatGPT or Claude chat to `.curt` from the browser

**Converters**

- [`curt-convert`](https://github.com/dotcurt/curt-convert) — Claude
  Code session transcripts (JSONL) → `.curt`
- [`curt-codex`](https://github.com/dotcurt/curt-codex) — OpenAI Codex
  CLI sessions ⇄ `.curt`
- [`curt-openclaw`](https://github.com/dotcurt/curt-openclaw) — OpenClaw
  gateway session transcripts → `.curt`
- [`curt-hermes`](https://github.com/dotcurt/curt-hermes) — Hermes agent
  sessions ⇄ `.curt`
- [`curt-openwebui`](https://github.com/dotcurt/curt-openwebui) —
  Open WebUI chats → `.curt`
- [`curt-wildchat`](https://github.com/dotcurt/curt-wildchat) —
  WildChat-1M records → `.curt`

**Bridges**

- [`curt-vcon`](https://github.com/dotcurt/curt-vcon) — `.curt` ⇄ the
  IETF vCon container
- [`langchain-curt`](https://github.com/dotcurt/langchain-curt) —
  LangChain chat loader
- [`curt-busabase`](https://github.com/dotcurt/curt-busabase) — Busabase
  review trails → `.curt`

## The checkable claims

- spec v1 frozen — version-1 files stay readable forever
- 27 conformance vectors, passing in CI, reproducible from
  [`conformance/`](https://github.com/dotcurt/dot_curt/tree/main/conformance)
- 11 implementations — read, write, or both
- unknown fields survive round-trip; a corrupted file is rejected whole,
  never half-imported
- everything MIT — spec, reference code, schema, fixtures
