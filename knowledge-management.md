# Knowledge management

Note-taking, personal knowledge bases, and tools for organizing information.

[← Back to index](README.md)

<!-- Add entries below using the format in _template.md. Newest first. -->

### [STORM](https://github.com/stanford-oval/storm)
`status: watching` · `tags: knowledge-curation, research, llm, citations, co-storm` · added 2026-11

An open-source LLM knowledge-curation system from the Stanford Open Virtual Assistant Lab (Stanford OVAL) that researches a topic and generates a full-length report with citations. The README expands the name as "Synthesis of Topic Outlines through Retrieval and Multi-perspective Question Asking": a pre-writing stage that collects references and builds an outline through perspective-guided question asking and a simulated conversation with a topic expert, then a writing stage that produces a Wikipedia-like article with citations. Co-STORM, in the same repo, adds a collaborative discourse so a human can observe or steer the discussion.
**Why I care:** A structured research-to-draft pipeline — multi-perspective search, outline, then a cited long draft — rather than a single chat prompt that dumps a report.
**Notes:** Shared by [AI郵報 (@aiposthub)](https://www.threads.com/@aiposthub/post/DgE6S7qAasK) (no stills; the post itself has no GitHub URL). Its article <https://www.aiposthub.com/stanford-storm-ai-wikipedia-research-agent/> and the post's link-card image point to stanford-oval/storm; the article title cites 31,000 stars (3.1万) and the card showed 32k. GitHub showed about 31,933 stars as of 2026-11-23 (Asia/Taipei). In the post, @aiposthub cautions that open source does not mean the cloud models and search APIs are free, and that citations do not mean the content is correct — sources still need human checking. The README does require language-model and search API keys (examples use OpenAI and Bing) and says "the system cannot produce publication-ready articles that often require a significant number of edits." Live preview: <https://storm.genie.stanford.edu/>. Install from the README: `pip install knowledge-storm`. Contact people listed in the README: Yijia Shao and Yucheng Jiang. The README's citations are the NAACL 2024 STORM paper (Shao, Jiang, Kanell, Xu, Khattab, and Lam) and the EMNLP 2024 Co-STORM paper (Jiang, Shao, Ma, Semnani, and Lam). MIT (Copyright 2024 Stanford Open Virtual Assistant Lab), confirmed in the repo `LICENSE`. Not tested.

### [Fabric](https://github.com/danielmiessler/Fabric)
`status: watching` · `tags: ai, prompts, patterns, cli` · added 2026-11

An open-source framework by Daniel Miessler for augmenting humans using AI. The README describes it as a way to create, collect, and organize prompts — which it calls Patterns — by real-world task, and to run them from the command line or in other tools. Examples in the README include extracting the interesting parts of YouTube videos and podcasts, summarizing academic papers, explaining code, and turning bad documentation into usable documentation.
**Why I care:** A single place to keep and run task-specific prompts instead of hunting through one-off chat sessions — closer to a personal pattern library than to another chatbot.
**Notes:** The GitHub description matches the README's "open-source framework for augmenting humans using AI" line. Origin story: <https://danielmiessler.com/p/fabric-origin-story> (the page loaded when checked). One-line install from the README: `curl -fsSL https://raw.githubusercontent.com/danielmiessler/fabric/main/scripts/installer/install.sh | bash`. The README says `fabric` was created by Daniel Miessler in January 2024; primary contributors listed there also include Jonathan Dunn, Scott Behrens, and Andre Guerra. About 44.7k GitHub stars as of 2026-11-23 (Asia/Taipei). GitHub and the README badge label the project MIT; the repo's `LICENSE` file is MIT text with the copyright line "Copyright (c) 2012-2024 Scott Chacon and others." Not the same project as the [Fabric.js](frontend.md#fabricjs) canvas library in frontend.md. Not tested.

### [Flexoki](https://github.com/kepano/flexoki)
`status: watching` · `tags: color-scheme, theme, syntax-highlighting, obsidian` · added 2026-11

An inky color scheme for prose and code, designed for comfortable long-form reading and writing. Ports available for many editors and apps including Obsidian, VS Code, and terminals.
**Why I care:** A cohesive palette that works across writing and coding tools. Pairs well with the Minimal theme for Obsidian.
**Notes:** MIT. Not tested. Docs: <https://stephango.com/flexoki>.

### [Obsidian Minimal](https://github.com/kepano/obsidian-minimal)
`status: watching` · `tags: obsidian, theme, customization` · added 2026-11

A distraction-free and highly customizable theme for Obsidian. Focuses on typography, density, and color scheme options.
**Why I care:** A clean starting point for Obsidian that stays out of the way. The companion Minimal Theme Settings plugin adds toggles for all the options.
**Notes:** MIT. Not tested. Docs: <https://minimal.guide>.

### [40 Questions](https://github.com/kepano/40-questions)
`status: watching` · `tags: reflection, yearly-review, templates, obsidian` · added 2026-11

A set of questions for yearly and decade-end self-reflection: what went well, what didn't, what to change.
**Why I care:** A structured prompt for annual reviews. Can be imported into Obsidian or any note-taking tool.
**Notes:** No declared license. Not tested. Article: <https://stephanango.com/40-questions>.

### [Obsidian Sample Plugin](https://github.com/obsidianmd/obsidian-sample-plugin)
`status: watching` · `tags: obsidian, plugin-development, template, typescript` · added 2026-11

Official template for building Obsidian community plugins. Includes TypeScript build configuration, esbuild setup, and development best practices.
**Why I care:** The starting point if I want to build my own Obsidian plugin. Maintained by the Obsidian team.
**Notes:** 0BSD (permissive). Not tested. Docs: <https://docs.obsidian.md>.

### [Obsidian Releases](https://github.com/obsidianmd/obsidian-releases)
`status: watching` · `tags: obsidian, plugins, themes, registry` · added 2026-11

The official community plugin list, theme list, and release metadata for Obsidian. This is where plugins and themes register to appear in Obsidian's built-in browser.
**Why I care:** The canonical source for discovering Obsidian plugins and themes, and the place to submit my own.
**Notes:** No declared license (registry data). Not tested.

### [JSON Canvas](https://github.com/obsidianmd/jsoncanvas)
`status: watching` · `tags: file-format, canvas, spec, interoperability` · added 2026-11

An open file format for infinite canvas data. Used by Obsidian Canvas and designed for interoperability with other tools.
**Why I care:** An open spec means canvas files aren't locked to one app. Useful if I build tools that read or write canvas data.
**Notes:** MIT. Not tested. Spec: <https://jsoncanvas.org>.

### [Kepano Obsidian Vault](https://github.com/kepano/kepano-obsidian)
`status: watching` · `tags: obsidian, vault-template, note-taking, pkm` · added 2026-11

A personal Obsidian vault template with a bottom-up approach to note-taking and organizing interests. Includes folder structure, templates, and example notes.
**Why I care:** A working example of how to structure an Obsidian vault. Good starting point to adapt rather than building from scratch.
**Notes:** MIT. Not tested. Article: <https://stephango.com/vault>.
