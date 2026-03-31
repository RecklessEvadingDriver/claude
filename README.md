# Claude Code

Claude Code is Anthropic's official CLI for Claude — an AI assistant you can use directly from your terminal.

## Setup

This project requires [Bun](https://bun.sh) (v1.2.0 or later).

### Install dependencies

```bash
bun install
```

### Run

```bash
bun run start
```

### Build

```bash
bun run build
```

### Type-check

```bash
bun run typecheck
```

## Project Structure

All source code lives in the `src/` directory and is written in TypeScript/TSX.

| Path | Description |
|------|-------------|
| `src/main.tsx` | Application entry point |
| `src/entrypoints/` | CLI, MCP, and SDK entrypoints |
| `src/tools/` | Built-in agentic tools |
| `src/commands/` | CLI sub-commands |
| `src/services/` | API clients and background services |
| `src/utils/` | Shared utility helpers |
| `src/components/` | React/Ink UI components |
| `src/screens/` | Full-screen terminal UI views |