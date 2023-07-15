# TypeScript Starter

Minimal TypeScript project template with Jest testing and VS Code debugging.

## Usage

```bash
npm install
npm run dev          # ts-node-dev with auto-restart and transpile-only
npm run dev:debug    # same but with --inspect on port 4321
npm test             # jest with ts-jest
```

## What's included

- TypeScript 4.8 with ts-node-dev for fast reload
- Jest 29 with ts-jest for TypeScript test support
- VS Code launch config (`launch.json`) that attaches to the debug port
- Entry point at `src/index.ts`, tests in `__tests__/`

## Dependencies

- `typescript`, `ts-node-dev` - development runtime
- `jest`, `ts-jest`, `@types/jest` - testing
