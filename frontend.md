# Front-end

UI frameworks, component libraries, styling, and build tools.

[← Back to index](README.md)

<!-- Add entries below using the format in _template.md. Newest first. -->

### [apple-design (emilkowalski/skills)](https://github.com/emilkowalski/skills/tree/main/skills/apple-design)
`status: watching` · `tags: agent-skill, animation, springs, gestures, interaction-design, typography, a11y` · added 2026-10

An agent skill that adapts Apple's interface and fluid-motion principles, mainly WWDC 2018's *Designing Fluid Interfaces*, for the web: CSS, Pointer Events, `requestAnimationFrame`, and spring libraries like Motion/Framer Motion. It covers instant response on press, 1:1 drag tracking, interruptible animations, springs instead of fixed durations, carrying the drag's speed into the animation, momentum, rubber-banding, translucent materials, reduced motion, and typography.
**Why I care:** Agents have weak taste in motion. This gives them concrete rules and numbers so drawers, sheets, and swipe interactions feel native instead of "fine". For example: default springs to damping `1.0`, add bounce (~`0.8`) only after a flick, and always animate from the current on-screen value.
**Notes:** Part of Emil Kowalski's skills collection (ex-Vercel/Linear, creator of Sonner), MIT, ~50k stars. Install the whole set with `npx skills@latest add emilkowalski/skills`. Related skills in the same repo worth a look: `emil-design-eng` (the main one), `animate`, `review-animations`, `animation-performance`, and `pick-ui-library`.
