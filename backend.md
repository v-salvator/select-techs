# Back-end

Servers, APIs, databases, auth, and queues.

[← Back to index](README.md)

<!-- Add entries below using the format in _template.md. Newest first. -->

### [fast-anything](https://github.com/EL4CTEO/fast-anything)
`status: watching` · `tags: performance, rust, profiling, agent-skill, claude-code, mcp` · added 2026-11

A tool by EL4CTEO that profiles an app, has a coding agent port only the slowest functions to Rust, and enables the port only after replaying recorded calls and confirming the results match and the app is actually faster. The README's tagline is "Don't rewrite it in Rust. Rewrite the 5% that's slow."
**Why I care:** A reversible, proof-gated way to speed up a hot path without rewriting the whole codebase in Rust.
**Notes:** Shared by [明子206 (@mingzi206)](https://x.com/mingzi206/status/2124437302068011026), who is not the repo owner. [Author continuation](https://x.com/mingzi206/status/2124437458821726623) links the repo and install commands. The post has one still (a photo); no local thumbnail was added because this is a software entry. The post says the tool leaves 95% of existing code alone, records 500 real calls, sends the hot functions to Claude Code or Codex to rewrite in Rust, and only ships a port that is 100% consistent and actually faster, with one-click rollback. The README describes recording "up to 500" real calls, plus derived edge cases; nothing is enabled until every case matches (floats within 1e-9) and a correct-but-slower port is also rejected; `enable`/`disable` swaps the Rust in or out, and `FAST_ANYTHING_DISABLE=1` runs the original. `--agent` takes `claude`, `codex`, or any command that reads a prompt on stdin. The post lists Python, TypeScript, Go, PHP, Ruby, Java, and C++; the README's language table also includes Kotlin, C, C#, R, and Node/Bun/Deno, all marked supported. The post cites official scores of Python 4.91s → 42ms (116×), PHP 55×, Go 21×, and TypeScript 20×; the README's Results table reports those same figures (and others) as "real runs on an i5-10500, Windows 11" (C and C++ on a 4-core GitHub Actions Linux runner), to be reproduced from `examples/` — those are the project's numbers, not independently verified. Install from the README: `npm i -g @el4cteo/fast-anything` or `cargo install fast-anything`. Claude Code plugin: `/plugin marketplace add EL4CTEO/fast-anything`. MCP: `claude mcp add fast-anything -- fast-anything mcp`. About 2,959 GitHub stars as of 2026-11-24 (Asia/Taipei). MIT (Copyright 2026 EL4CTEO), confirmed in the repo `LICENSE`. Not tested.

