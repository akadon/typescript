# TypeScript Starter

Minimal TypeScript project template for quick prototyping.

## Setup

```bash
npm install
```

## Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start with auto-restart on file changes |
| `npm run dev:debug` | Same with debugger on port 4321 |
| `npm test` | Run Jest tests |

## Structure

```
src/index.ts          entry point
__tests__/index.js    test example
.vscode/launch.json   VS Code debug config (attach to ts-node-dev)
```

## Stack

- TypeScript 4.8
- ts-node-dev (fast transpile-only reload)
- Jest 29 + ts-jest
