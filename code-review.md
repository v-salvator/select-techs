# Code review

Review tools, linters, static analysis, and AI reviewers.

[← Back to index](README.md)

<!-- Add entries below using the format in _template.md. Newest first. -->

### [untangle-codebase](https://github.com/caldoai/skills/blob/main/skills/untangle-codebase/SKILL.md)
`status: watching` · `tags: agent-skill, refactoring, code-quality, cleanup, dead-code, abstractions` · added 2026-11

An agent skill by Maze (@mazeincoding) for broad codebase refactoring: leaky abstractions, copy-paste code, temporary workarounds, useless wrappers, coupling, and dead code. Runs as a slash command with optional focus area.
**Why I care:** A structured workflow for the messy "clean this up" task: asks whether to touch comments/tests, inventories problems before changes, redesigns from first principles with a decision log, implements fixes, then rechecks via subagents until no worthwhile issues remain.
**Notes:** Invoked as `/untangle-codebase` or with a focus, e.g. `/untangle-codebase preview changes before applying them`. **Scope warning:** this skill performs extensive refactoring; review all changes before adopting. MIT license, part of [caldoai/skills](https://github.com/caldoai/skills). Found via [X post](https://x.com/mazeincoding/status/2118378945557004477). Not tested.

### [fallow](https://github.com/fallow-rs/fallow)
`status: watching` · `tags: static-analysis, typescript, javascript, dead-code, complexity, duplication, ci, mcp, rust` · added 2026-10

Codebase analysis for TS/JS from one repository graph: health score, complexity hotspots, duplication, architecture boundaries, circular dependencies, design-system/styling drift, and unused files, exports, and dependencies. A single Rust binary built on Oxc, with no config and no TypeScript compiler needed.
**Why I care:** One tool covers what usually takes several (knip-style dead code, jscpd-style duplication, madge-style cycles, complexity), and `fallow audit` only fails a PR on findings the change *introduces*, so it can gate an existing messy codebase. The analysis is deterministic (no AI) and fast: 2.95 s for dead code across the 20k-file Next.js monorepo.
**Notes:** `npx fallow` in the project root. PR gate: `fallow audit --base <ref>` or the GitHub Action `fallow-rs/fallow@v3`. Agents: `npx fallow agent install` (also has MCP, LSP, and a VS Code extension). `npx fallow viz` opens an interactive project map. Docs: <https://docs.fallow.tools>. MIT, ~5k stars.

### [React Doctor](https://www.npmjs.com/package/react-doctor)
`status: watching` · `tags: react, linter, agent-skill, ci, nextjs, react-native, performance, a11y` · added 2026-10

Deterministic checks for React code that report issues in state and effects, performance, architecture, security, accessibility, and maintainability. Works with Next.js, Vite, Astro, TanStack, React Native, and Expo. Its tagline: "Your agent writes bad React. This catches it."
**Why I care:** A guardrail for AI-written React. Install it as a skill so Claude Code, Cursor, or Codex checks and fixes its own React, and run it in CI on PRs.
**Notes:** Scan: `npx react-doctor@latest`. Agent skill: `npx react-doctor@latest install`. CI: `npx react-doctor@latest ci install`. Rules live in `doctor.config.ts`. `npx react-doctor@latest scan http://localhost:3000` records a Chrome performance trace while you use the app. Collects anonymous telemetry; opt out with `--no-telemetry`. Repo: [millionco/react-doctor](https://github.com/millionco/react-doctor), MIT, ~15k stars.
