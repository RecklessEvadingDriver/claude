# Claude Code

[![npm](https://img.shields.io/npm/v/@anthropic-ai/claude-code.svg?style=flat-square)](https://www.npmjs.com/package/@anthropic-ai/claude-code)
![Node.js 18+](https://img.shields.io/badge/Node.js-18%2B-brightgreen?style=flat-square)

Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows — all through natural language commands.

**Learn more at [Claude Code Homepage](https://claude.com/product/claude-code)** | [Documentation](https://code.claude.com/docs/en/overview)

## Using Claude Code

Install the published package globally and run it:

```sh
npm install -g @anthropic-ai/claude-code
claude
```

## Development Setup

This repository contains the Claude Code source code. To work with it you need [Bun](https://bun.sh) installed.

### Prerequisites

- [Bun](https://bun.sh) ≥ 1.2.0
- Node.js ≥ 18.0.0 (for publishing / running the compiled output)

### Install dependencies

```sh
bun install
```

### Build

```sh
bun run build
```

This bundles `src/main.tsx` into `cli.js`.

### Type checking

```sh
bun run typecheck
```

### Linting

```sh
bun run lint
```

## Reporting Bugs

Use the `/bug` command to report issues directly within Claude Code, or file a [GitHub issue](https://github.com/anthropics/claude-code/issues).

## License

See [LICENSE.md](LICENSE.md).