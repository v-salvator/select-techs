# 3D rendering

3D engines, WebGL, modeling, and rendering pipelines.

[← Back to index](README.md)

<!-- Add entries below using the format in _template.md. Newest first. -->

### [img2threejs](https://github.com/img2threejs/img2threejs)
`status: watching` · `tags: agent-skill, threejs, image-to-3d, procedural, webgl, typescript, claude-code` · added 2026-11

An agent skill that rebuilds the object in one reference image as a code-only Three.js model. Instead of a downloaded mesh, you get a TypeScript `THREE.Group` factory made from primitives, procedural shaders, and generated geometry, with pivots, sockets, and colliders so it's ready to animate.
**Why I care:** It turns image-to-3D from "upload and get a blob" into readable code an agent can keep editing, which suits Web 3D, interactive demos, and product showcases. The agent builds in stages (blockout, structure, form, material, surface, lighting, and so on) and checks each pass with vision review, while Python scripts handle validation to save tokens.
**Notes:** Needs Node 18+, Git, and Python 3.10+. Install with `npx --yes img2threejs@latest install`, check with `npx --yes img2threejs@latest doctor`, then restart the agent. Works with Claude Code, Codex, OpenCode, and Hermes. Live demos with source: <https://img2threejs.io>. Found via [@bing_sunzhi on Threads](https://www.threads.com/@bing_sunzhi/post/DbKxTpWAVgv). Apache-2.0, ~20k stars.
