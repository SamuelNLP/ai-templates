# AI Templates

Opinionated instruction templates for:

- OpenCode (via `.ai/`)
- JetBrains AI Assistant (via `.aiassistant/`)

## What's Included

- OpenCode instructions: `.ai/opencode.md`
- JetBrains rules: `.aiassistant/rules/`
- Example OpenCode config: `opencode.json`

## Usage

OpenCode:

1. Copy `.ai/opencode.md` into your repo.
2. Point your OpenCode config at it (example):

```json
{
  "instructions": [".ai/opencode.md"]
}
```

JetBrains AI Assistant:

1. Copy `.aiassistant/` into your repo root.
2. Add/edit rules in `.aiassistant/rules/*.md`.

## License

MIT (see `LICENSE`).
