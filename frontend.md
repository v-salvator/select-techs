# Front-end

UI frameworks, component libraries, styling, and build tools.

[← Back to index](README.md)

<!-- Add entries below using the format in _template.md. Newest first. -->

### [Astryx](https://github.com/meta/astryx)
`status: watching` · `tags: design-system, react, stylex, themes, cli, agent-ready, meta` · added 2026-11

Meta's open-source React design system (npm `@astryxdesign/core`): themable components with dark mode, ready-made themes, page templates, and a CLI for docs, scaffolding, `init` into AGENTS.md/CLAUDE.md, and `swizzle` to eject component source. Authored with StyleX; consumers can override with Tailwind, CSS modules, or plain CSS. Official docs at [astryx.atmeta.com](https://astryx.atmeta.com/).
**Why I care:** A full Meta-backed system aimed at both humans and coding agents — CLI/docs designed so assistants use the same component references. Useful when building internal tools or agent-assisted UI without inventing a kit from scratch.
**Notes:** MIT (Copyright Meta Platforms, Inc.). Currently in Beta; requires React 19+. Discovered via [無聊就學SI Lab | Boring Traveler (@akiraxtwo)](https://www.threads.com/@akiraxtwo/post/DffW6-5AfzD). Not tested.

### [Popmotion](https://github.com/Popmotion/popmotion)
`status: watching` · `tags: animation, springs, keyframes, physics, motion` · added 2026-11

Animation library for springs, keyframes, and physics-based motion. Powers Framer Motion under the hood.
**Why I care:** Low-level animation primitives when you need more control than a high-level library provides.
**Notes:** MIT. From [@e1genqq's library list](https://x.com/e1genqq/status/2119162629910331460). Not tested.

### [anime.js](https://github.com/juliangarnier/anime)
`status: watching` · `tags: animation, timelines, easing, svg, css` · added 2026-11

JavaScript animation engine with timelines, easing, and staggering. Works on CSS, SVG, DOM attributes, and JS objects.
**Why I care:** Lightweight timeline-based animation when you don't need a full motion library.
**Notes:** MIT. From [@e1genqq's library list](https://x.com/e1genqq/status/2119162629910331460). Not tested.

### [Vivus](https://github.com/maxwellito/vivus)
`status: watching` · `tags: svg, animation, drawing, stroke` · added 2026-11

SVG drawing animation library. Animates stroke paths to create a "being drawn" effect.
**Why I care:** One-trick pony but does it well. Good for logo reveals or line-art animations.
**Notes:** MIT. From [@e1genqq's library list](https://x.com/e1genqq/status/2119162629910331460). Not tested.

### [Fabric.js](https://github.com/fabricjs/fabric.js)
`status: watching` · `tags: canvas, svg, editor, drawing, interactive` · added 2026-11

Canvas library with SVG-to-canvas parsing. Provides object model, interactivity, and serialization for building editors.
**Why I care:** The primitives for building a canvas-based editor without starting from scratch.
**Notes:** MIT. From [@e1genqq's library list](https://x.com/e1genqq/status/2119162629910331460). Not tested.

### [Rough.js](https://github.com/rough-stuff/rough)
`status: watching` · `tags: graphics, hand-drawn, sketchy, svg, canvas` · added 2026-11

Creates graphics with a hand-drawn, sketchy appearance. Works with canvas and SVG.
**Why I care:** Instant whiteboard/napkin aesthetic without drawing by hand.
**Notes:** MIT. From [@e1genqq's library list](https://x.com/e1genqq/status/2119162629910331460). Not tested.

### [howler.js](https://github.com/goldfire/howler.js)
`status: watching` · `tags: audio, playback, web-audio, sprites, cross-browser` · added 2026-11

JavaScript audio library for the modern web. Handles playback, sprites, spatial audio, and cross-browser quirks.
**Why I care:** Audio in browsers is still messy; howler abstracts the pain.
**Notes:** MIT. From [@e1genqq's library list](https://x.com/e1genqq/status/2119162629910331460). Not tested.

### [glslCanvas](https://github.com/patriciogonzalezvivo/glslCanvas)
`status: watching` · `tags: glsl, shaders, webgl, preview, live-coding` · added 2026-11

Simple tool to load GLSL shaders on HTML Canvas using WebGL. Good for shader previews and live coding.
**Why I care:** Quick way to test shaders without a full 3D setup.
**Notes:** MIT. From [@e1genqq's library list](https://x.com/e1genqq/status/2119162629910331460). Not tested.

### [Scrolltide](https://www.scrolltide.co/)
`status: watching` · `tags: prompts, templates, 3d, scroll-driven, cinematic, ai-builder` · added 2026-11

Cinematic website prompts and templates for 3D/scroll-driven sites. Browse pre-built sections, copy prompts into AI builders (Claude, Cursor, Lovable), or use their components directly.
**Why I care:** Similar to Jiro but focused on immersive, scroll-driven experiences rather than general landing pages. Useful when vibe-coding sites that need depth and motion.
**Notes:** Free and paid tiers. From [Aman Singh (@amananimates)](https://x.com/amananimates/status/2119127905666314632), co-founder of Scrolltide. [Author continuation](https://x.com/amananimates/status/2119128340149969008) promotes companion Claude/Cursor prompts. No public repo or declared license verified. Not tested.

### [Scroll Shaders](https://scrollshaders.com/)
`status: watching` · `tags: shaders, webgl, components, react, looping, backgrounds` · added 2026-11

Seamless-loop WebGL shaders and components. Copy React/HTML code or download MP4. Designed for scroll-triggered or looping background effects.
**Why I care:** Ready-made shader effects that can drop into a project without writing GLSL from scratch. The MP4 option is useful for non-WebGL contexts or video backgrounds.
**Notes:** Free and paid tiers. From Scrolltide team. No public repo or declared license verified. Not tested.

### [Refero Styles](https://styles.refero.design/)
`status: watching` · `tags: design-systems, ai-readable, styles, typography, colors, reference` · added 2026-11

A library of real website design styles (typography, colors, spacing) with AI-readable DESIGN.md files. Browse sites, then feed the style doc to an AI builder to match the look.
**Why I care:** Bridges the gap between "I like this site's style" and getting an AI to reproduce it. The DESIGN.md format is purpose-built for agent consumption.
**Notes:** Part of the Refero suite. From Scrolltide team. No public repo or declared license verified. Not tested.

### [Jiro](https://jiro.build/)
`status: watching` · `tags: prompts, landing-page, templates, ai-builder, mcp` · added 2026-11

A design prompt library for landing pages: browse templates and sections, copy the prompt, paste into AI builders like Bolt.new, Lovable, v0, Replit, or Cursor. Also offers an MCP endpoint (`mcp.jiro.build`) so AI tools can pull prompts directly.
**Why I care:** Shortcuts the "blank page" problem when vibe-coding landing pages. The prompts are tuned for specific AI builders, so output should be closer to the preview than a generic description.
**Notes:** Freemium; some templates require a paid plan. Site advertises 1,454+ sections/templates. No public repo or declared license. Not tested.

### [PulsoIcon](https://github.com/CityPulso/PulsoIcon)
`status: watching` · `tags: icons, animation, react, vue, svelte, compose, swiftui, lucide` · added 2026-11

Animated icon library with 9,955 icons, each with hand-written motion that plays on hover or focus. Drop-in replacement for lucide-react (same component names and props). Also supports Vue, Svelte, Jetpack Compose (Android), and SwiftUI (iOS/macOS). Tree-shakeable; respects reduced motion.
**Why I care:** Micro-animations that ship with the icon instead of needing custom work per icon. The lucide-react compatibility means switching is a one-line import change.
**Notes:** ISC license; includes icons built on Lucide (ISC), Tabler (MIT), Iconoir (MIT), Phosphor (MIT), and brand logos drawn after Simple Icons (CC0). Brand logos remain trademarks of their owners. Not tested. Docs: <https://pulsoicon.com/docs>. Playground: <https://pulsoicon.com/playground>.

### [apple-design (emilkowalski/skills)](https://github.com/emilkowalski/skills/tree/main/skills/apple-design)
`status: watching` · `tags: agent-skill, animation, springs, gestures, interaction-design, typography, a11y, drawer, sheet, drag, swipe` · added 2026-10 · updated 2026-11

An agent skill that adapts Apple's interface and fluid-motion principles, mainly WWDC 2018's *Designing Fluid Interfaces*, for the web: CSS, Pointer Events, `requestAnimationFrame`, and spring libraries like Motion/Framer Motion. It covers instant response on press, 1:1 drag tracking, interruptible animations, springs instead of fixed durations, carrying the drag's speed into the animation, momentum, rubber-banding, translucent materials, reduced motion, and typography.
**Why I care:** Agents have weak taste in motion. This gives them concrete rules and numbers so drawers, sheets, and swipe interactions feel native instead of "fine". For example: default springs to damping `1.0`, add bounce (~`0.8`) only after a flick, and always animate from the current on-screen value.
**Notes:** Part of Emil Kowalski's skills collection (ex-Vercel/Linear, creator of Sonner/[Vaul](https://vaul.emilkowal.ski/)), MIT. Install the whole set with `npx skills@latest add emilkowalski/skills`. Newly announced [`/gestures`](https://github.com/emilkowalski/skills/blob/main/skills/gestures/SKILL.md) skill ([Nov 2026](https://x.com/emilkowalski/status/2119406396160540738)) covers drag, swipe, and sheet interactions: 1:1 finger tracking via motion values (not React state), springs seeded with release velocity, rubber-banding, distance-or-velocity dismissal thresholds, and when to use Vaul instead of hand-rolling. Related skills: `emil-design-eng` (the main one), `animate`, `review-animations`, `animation-performance`, `pick-ui-library`. Not tested.
