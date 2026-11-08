# 3D rendering

3D engines, WebGL, modeling, and rendering pipelines.

[← Back to index](README.md)

<!-- Add entries below using the format in _template.md. Newest first. -->

### [Three.js](https://github.com/mrdoob/three.js)
`status: watching` · `tags: 3d, webgl, javascript, rendering, scenes` · added 2026-11

JavaScript 3D library. The de facto standard for browser-based 3D.
**Why I care:** If you're doing 3D on the web, you're probably using Three.js or something built on it.
**Notes:** MIT. From [@e1genqq's library list](https://x.com/e1genqq/status/2119162629910331460). Not tested.

### [Threlte](https://github.com/threlte/threlte)
`status: watching` · `tags: 3d, svelte, threejs, declarative, components` · added 2026-11

3D framework for Svelte. Declarative Three.js components with Svelte reactivity.
**Why I care:** If your stack is Svelte, this is the way to add 3D without leaving the component model.
**Notes:** MIT. From [@e1genqq's library list](https://x.com/e1genqq/status/2119162629910331460). Not tested.

### [react-three-rapier](https://github.com/pmndrs/react-three-rapier)
`status: watching` · `tags: physics, react, threejs, rapier, simulation` · added 2026-11

Rapier physics in React. Declarative physics components for react-three-fiber.
**Why I care:** Physics without leaving React's component model. Good for games, simulations, or interactive 3D.
**Notes:** MIT. From [@e1genqq's library list](https://x.com/e1genqq/status/2119162629910331460). Not tested.

### [Mitsuba 3](https://github.com/mitsuba-renderer/mitsuba3)
`status: watching` · `tags: renderer, research, differentiable, python, inverse-rendering` · added 2026-11

Retargetable forward and inverse renderer. Research-grade, supports differentiable rendering for optimization.
**Why I care:** When you need physically accurate rendering or inverse rendering for research/ML.
**Notes:** BSD-3-Clause. From [@e1genqq's library list](https://x.com/e1genqq/status/2119162629910331460). Not tested.

### [three-bvh-csg](https://github.com/gkjohnson/three-bvh-csg)
`status: watching` · `tags: csg, boolean, three.js, modeling, geometry` · added 2026-11

Fast CSG (Constructive Solid Geometry) for Three.js. Boolean operations on meshes: union, subtract, intersect.
**Why I care:** Procedural modeling with boolean ops without leaving the browser.
**Notes:** MIT. From [@e1genqq's library list](https://x.com/e1genqq/status/2119162629910331460). Not tested.

### [OpenColorIO](https://github.com/AcademySoftwareFoundation/OpenColorIO)
`status: watching` · `tags: color-management, vfx, grading, pipeline, aswf` · added 2026-11

Color management framework for visual effects and animation. Industry standard from the Academy Software Foundation.
**Why I care:** Consistent color across applications in a VFX/animation pipeline.
**Notes:** BSD-3-Clause. From [@e1genqq's library list](https://x.com/e1genqq/status/2119162629910331460). Not tested.

### [boba-bar](https://github.com/iamtechartist/boba-bar)
`status: watching` · `tags: threejs, interactive, webgl, 3d-builder, demo` · added 2026-11

A browser-based interactive 3D bubble-tea builder by Zhen Zhu (@zhenzhu600). Customize cup, ice, toppings, and flavors in a playful Three.js scene.
**Why I care:** A polished example of a small interactive 3D configurator that runs entirely in the browser. Good reference for product builders, drink customizers, or any "build your own" UI in WebGL.
**Notes:** [Live demo](https://iamtechartist.github.io/boba-bar/). The author says it was made with "Opus 5.5 and Three.js" (unverified model claim). MIT license, © 2026 Techartist. Found via [Threads post](https://www.threads.com/@zhenzhu600/post/Dfa3Z1rBunr). No thumbnail saved (source is video only).

### [img2threejs](https://github.com/img2threejs/img2threejs)
`status: watching` · `tags: agent-skill, threejs, image-to-3d, procedural, webgl, typescript, claude-code` · added 2026-11

An agent skill that rebuilds the object in one reference image as a code-only Three.js model. Instead of a downloaded mesh, you get a TypeScript `THREE.Group` factory made from primitives, procedural shaders, and generated geometry, with pivots, sockets, and colliders so it's ready to animate.
**Why I care:** It turns image-to-3D from "upload and get a blob" into readable code an agent can keep editing, which suits Web 3D, interactive demos, and product showcases. The agent builds in stages (blockout, structure, form, material, surface, lighting, and so on) and checks each pass with vision review, while Python scripts handle validation to save tokens.
**Notes:** Needs Node 18+, Git, and Python 3.10+. Install with `npx --yes img2threejs@latest install`, check with `npx --yes img2threejs@latest doctor`, then restart the agent. Works with Claude Code, Codex, OpenCode, and Hermes. Live demos with source: <https://img2threejs.io>. Found via [@bing_sunzhi on Threads](https://www.threads.com/@bing_sunzhi/post/DbKxTpWAVgv). Apache-2.0, ~20k stars.
