# Front-end

UI frameworks, component libraries, styling, and build tools.

[← Back to index](README.md)

<!-- Add entries below using the format in _template.md. Newest first. -->

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
