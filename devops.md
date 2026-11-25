# DevOps

CI/CD, hosting, containers, infrastructure, and monitoring.

[← Back to index](README.md)

<!-- Add entries below using the format in _template.md. Newest first. -->

### [Vercel Board](https://github.com/vercel/board)
`status: watching` · `tags: agents, collaboration, slack, cli, vercel` · added 2026-11

A message board from Vercel for people and coding agents. The README says it lives in Vercel's API — `vercel link`, with nothing to deploy and no database to keep — or you can run a local board with `npx @vercel/board serve`. It covers channels and threads, task claims with leases, watchers that wake a route when a message arrives, scheduled messages, and two-way sync with Slack, GitHub, and Linear.
**Why I care:** A shared place for humans and locally or remotely running agents to coordinate work, instead of crowding a regular Slack channel or inventing a one-off task file per agent.
**Notes:** Discussed by [Matt Pocock (@mattpocockuk)](https://x.com/mattpocockuk/status/2124797717834543167) (no stills), who is not the project author (his bio says ex-Vercel). In the post he calls the idea "genius" but says most teams should build it from scratch, describes it as "a private Slack workspace for your agents AND developers" that can sync to Slack, and sketches ideas (including an unread-message queue that he says Vercel Board does not do, as far as he knows). [Author continuation](https://x.com/mattpocockuk/status/2124797892808384889): "And yes I am currently burning a bunch of tokens reimplementing this." When asked whether Board can be self-hosted, he replied he thought so but was unsure; the README does document a local board, a Tailscale-shared board, an in-memory board for tests, and a custom backend. Vercel's intro post <https://vercel.com/blog/introducing-vercel-board> (18 Nov 2026; listed authors: Julian Benegas, Nicolás Montone, Malte Ubl, Tom Knickman, Martin Sione, and Bani Singh) calls it an experimental agentic primitive. Install from the README: `npm i @vercel/board`, plus `npx skills add vercel/board --skill board -g` for coding agents; the inspector is `npx vb inspect`. Docs: <https://vercel.com/docs/board>. About 216 GitHub stars as of 2026-11-24 (Asia/Taipei). Apache-2.0 (Copyright 2026 Vercel Inc.), confirmed in the repo `LICENSE`. Not tested.

