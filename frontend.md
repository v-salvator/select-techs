# Front-end

UI frameworks, component libraries, styling, and build tools.

[← Back to index](README.md)

<!-- Add entries below using the format in _template.md. Newest first. -->

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
`status: watching` · `tags: agent-skill, animation, springs, gestures, interaction-design, typography, a11y` · added 2026-10

An agent skill that adapts Apple's interface and fluid-motion principles, mainly WWDC 2018's *Designing Fluid Interfaces*, for the web: CSS, Pointer Events, `requestAnimationFrame`, and spring libraries like Motion/Framer Motion. It covers instant response on press, 1:1 drag tracking, interruptible animations, springs instead of fixed durations, carrying the drag's speed into the animation, momentum, rubber-banding, translucent materials, reduced motion, and typography.
**Why I care:** Agents have weak taste in motion. This gives them concrete rules and numbers so drawers, sheets, and swipe interactions feel native instead of "fine". For example: default springs to damping `1.0`, add bounce (~`0.8`) only after a flick, and always animate from the current on-screen value.
**Notes:** Part of Emil Kowalski's skills collection (ex-Vercel/Linear, creator of Sonner), MIT, ~50k stars. Install the whole set with `npx skills@latest add emilkowalski/skills`. Related skills in the same repo worth a look: `emil-design-eng` (the main one), `animate`, `review-animations`, `animation-performance`, and `pick-ui-library`.
