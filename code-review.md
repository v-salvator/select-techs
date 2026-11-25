# Code review

Review tools, linters, static analysis, and AI reviewers.

[← Back to index](README.md)

<!-- Add entries below using the format in _template.md. Newest first. -->

### [app-store-compliance](https://github.com/mjmirza/app-store-compliance)
`status: watching` · `tags: agent-skill, app-store, google-play, compliance, mobile, pre-submission` · added 2026-11

An open playbook and pre-submission guard by Mirza Iqbal ([mjmirza](https://github.com/mjmirza)) for App Store and Google Play rejections. The current GitHub description and [docs site](https://mjmirza.github.io/app-store-compliance/) describe 117 documented rejection patterns and fixes, privacy-manifest and Data safety checks, 95 tracked deadlines (EU AI Act, DSA, COPPA, and age laws), and a skill for AI coding agents. Version 2.4.0.
**Why I care:** A check you can run before you submit, aimed at the loop the X post describes — an AI-written prototype in an afternoon, then a week lost to a store rejection. The guard can scan a project once from the command line, or hook into Claude Code, Cursor, Codex, and other agents so it runs before an upload.
**Notes:** Found via [铁锤人 (@lxfater) on X](https://x.com/lxfater/status/2123625468729413925). That post names the project `app-store-compliance`, says it covers 123 rejection pitfalls and had nearly 2,000 GitHub stars, and mentions support for Claude Code, Codex, Cursor, and others. The attached images identify [mjmirza/app-store-compliance](https://github.com/mjmirza/app-store-compliance); the post's t.co link resolves to the first photo, not the repo. The current repo description and docs site say 117 patterns, not 123. About 2.7k GitHub stars as of 2026-11-21 (Asia/Taipei). One-time scan (needs git and bash; the README says nothing is installed and nothing in the app is changed): `git clone https://github.com/mjmirza/app-store-compliance ~/repositories/app-store-compliance` then `bash ~/repositories/app-store-compliance/agent-os/hooks/app-store-compliance-guard.sh "/path/to/your/app"`. To install hooks and the skill: `bash ~/repositories/app-store-compliance/scripts/install.sh --tool all`, or `--tool` with `cursor`, `codex`, and others. The README lists Claude Code, Codex, Gemini CLI, OpenCode, Cursor, GitHub Copilot, Grok, Qwen Code, Kimi Code, Factory Droid, Auggie, and Windsurf. Licensed under the [OpenRoots Agent License 2.3](https://openroots.org/licenses/ora/2.3) (SPDX `LicenseRef-OpenRoots-ORA-2.3`). The repo's NOTICE says it is free for individuals, nonprofits, schools, government bodies, and companies at or below USD 20 million annual gross revenue, with a royalty above that, and that AI training needs a separate Compute licence. Earlier releases keep the terms they shipped with (MIT and CC BY 4.0 before 2026-08-24). Not tested.

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
