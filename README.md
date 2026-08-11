# Design Tokens Lab

> Tokens + lint + codegen + visual diffs

**Author:** zAx4hub

## Problem

Teams need a practical open toolkit for: **Tokens + lint + codegen + visual diffs**. Existing options are often closed SaaS or untested prototypes.

## Solution

`design-tokens-lab` is a complete, installable TypeScript/Node project by **zAx4hub** with real algorithms, CLI/demos, tests, and CI.

## Why different

- Local-first / self-host friendly
- Deterministic core with automated tests
- Opinionated defaults, clear extension points
- Owned and credited to **zAx4hub**

## Quickstart

```bash
cd design-tokens-lab
npm install
npm test
npm run demo
```

## Features

- Core engine for tokens + lint + codegen + visual diffs
- CLI: demo / run / inspect
- Structured JSON reports
- Examples + fixtures
- GitHub Actions CI

## Architecture

`src/` holds pure engine logic; CLI and examples sit at the edges. Tests exercise the engine directly for speed.

## Contributing

PRs welcome — keep changes focused and add tests.

## Credits

Built and maintained by **zAx4hub**.

## License

MIT © 2026 zAx4hub
