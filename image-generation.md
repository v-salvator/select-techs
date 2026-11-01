# Image generation

Image models, prompts, skills, and tools you can generate with. Designs with no reusable prompt go in [Design references](design-references.md).

[← Back to index](README.md)

<!-- Add entries below using the format in _template.md. Newest first. -->

### [Long-exposure light trail silhouette prompt](https://www.threads.com/@bibanskiy/post/DfM8BNhiL68)
`status: watching` · `tags: prompt, portrait, silhouette, long-exposure, cinematic, film, identity-reference` · added 2026-11

A long prompt by Denis Bibanskih (@bibanskiy) that turns an uploaded photo of a person into a dark silhouette standing in shallow water, with a ribbon of glowing light curving around them, mountains behind, and an analog film look.
**Why I care:** It works like a shot brief, with separate sections for composition, light, water, sky, camera, and film. The key rule is that the world blurs while the figure stays still, and that contrast is what makes the image work.
**Notes:** Upload a clear photo of the person first, since the prompt relies on it for identity. Only use photos of yourself or someone who agreed to it. The post doesn't say which image model it was made for. The prompt asks for gold, but the examples came out closer to rose copper, so expect some drift in color. The full prompt is in the second post of the thread (in English).

<p>
  <img src="assets/image-generation/light-trail-silhouette-1.webp" width="190" alt="Silhouette in water with a curved light trail, example 1">
  <img src="assets/image-generation/light-trail-silhouette-2.webp" width="190" alt="Silhouette in water with a curved light trail, example 2">
</p>

<sub>AI-generated examples from @bibanskiy's post.</sub>

### [Motion Haze portrait prompts](https://www.threads.com/@ecolab_studio/post/DfMFpmhEexo)
`status: watching` · `tags: prompt, midjourney, portrait, motion-blur, cinematic, editorial` · added 2026-11

A set of Midjourney portrait prompts by Eco Lab | Studio (@ecolab_studio) built around long-exposure blur: heads smeared into ghostly trails, faces half lost in haze, and sharp figures against streaks of city light.
**Why I care:** Each prompt spells out exactly what stays sharp and what blurs, instead of just asking for "motion blur". Most of the mood comes from that split, plus huge negative space and a restrained palette.
**Notes:** Three prompts are printed on the carousel images, so swipe through the post to read them. They use `--ar 4:5`, and two also set `--v 8.2`, `--hd`, `--stylize` at 300 to 350, and several `--sref` codes, which do a lot of the styling. The last slide says to comment to get all the prompts, so the post may not show every one. Reuse the structure with your own subject rather than the age and appearance details written into them.

<p>
  <img src="assets/image-generation/motion-haze-1.webp" width="155" alt="Motion Haze portrait example 1">
  <img src="assets/image-generation/motion-haze-2.webp" width="155" alt="Motion Haze portrait example 2">
  <img src="assets/image-generation/motion-haze-3.webp" width="155" alt="Motion Haze portrait example 3">
  <img src="assets/image-generation/motion-haze-4.webp" width="155" alt="Motion Haze portrait example 4">
  <img src="assets/image-generation/motion-haze-5.webp" width="155" alt="Motion Haze portrait example 5">
</p>

<sub>AI-generated examples from @ecolab_studio's post, using the slides without text.</sub>

### [Taiwan vintage engraving poster prompt](https://www.threads.com/@jerry6151/post/DfLi2OdmGHm)
`status: watching` · `tags: prompt, poster, travel, vintage, engraving, taiwan, reusable-template` · added 2026-11

A template prompt by @jerry6151 for a series of vintage travel posters of Taiwan: fine engraved line art of a landmark in muted greens on aged ivory paper, with coordinates, a small red seal, and magazine-style type.
**Why I care:** It's a ready-made poster set for Taiwan, with labels in both Chinese and English. The fixed palette, layout, and series tagline keep every poster matching, so it's a good example of how to build a consistent series with one prompt.
**Notes:** Fill in the city, the landmark, and their English names. The series text is hard-coded to Taiwan, so change those lines to use it for other places. The post doesn't say which image model it was made for. Check the coordinates and Chinese text in each result, since AI can get small details wrong. The full prompt is in the second post of the thread (in Traditional Chinese).

<p>
  <img src="assets/image-generation/taiwan-engraving-1.webp" width="140" alt="Taiwan vintage engraving poster example 1">
  <img src="assets/image-generation/taiwan-engraving-2.webp" width="140" alt="Taiwan vintage engraving poster example 2">
  <img src="assets/image-generation/taiwan-engraving-3.webp" width="140" alt="Taiwan vintage engraving poster example 3">
  <img src="assets/image-generation/taiwan-engraving-4.webp" width="140" alt="Taiwan vintage engraving poster example 4">
</p>

<sub>Examples from @jerry6151's post.</sub>

### [Frosted glass photo poster prompt](https://www.threads.com/@emersonigpost/post/DewTH-Tibw0)
`status: watching` · `tags: prompt, photo-to-poster, frosted-glass, abstract, editorial, pastel` · added 2026-11

A GPT prompt by @emersonigpost that turns each uploaded photo into a 3:4 poster: the original photo on top, and an abstract version below made of translucent frosted-glass layers, soft blur, bright airy colors, and small editorial type.
**Why I care:** It makes everyday photos look like exhibition posters, even dull subjects like a fuel pump or a construction site. The key idea is selective blur: some areas stay sharp and others look like they're behind matte glass, instead of blurring everything.
**Notes:** Copy the prompt and upload photos. It handles several at once and outputs one poster per photo. The author says it works best on photos with lots of edges and shapes, like furniture and windows, and won't help out-of-focus shots. The full prompt is in the second post of the thread (in English).

<p>
  <img src="assets/image-generation/frosted-glass-1.webp" width="155" alt="Frosted glass poster example 1">
  <img src="assets/image-generation/frosted-glass-2.webp" width="155" alt="Frosted glass poster example 2">
  <img src="assets/image-generation/frosted-glass-3.webp" width="155" alt="Frosted glass poster example 3">
  <img src="assets/image-generation/frosted-glass-4.webp" width="155" alt="Frosted glass poster example 4">
  <img src="assets/image-generation/frosted-glass-5.webp" width="155" alt="Frosted glass poster example 5">
</p>

<sub>Examples from @emersonigpost's post, cropped to the generated half. The source photos are from Pexels.</sub>

### [mono-color-skill](https://github.com/yanliudesign/mono-color-skill)
`status: watching` · `tags: agent-skill, claude-code, editorial-design, poster, risograph, halftone, packaging` · added 2026-11

A Claude Code skill by Yan Liu that turns a theme, sentence, object, or photo into a printed-look editorial image: one or two inks on paper, halftone or risograph texture, lots of empty space, and restrained typography. It suits posters, zines, packaging, and portraits.
**Why I care:** It's a full visual system instead of a one-off prompt, with reference files for type, color, and layout, so an agent can keep a consistent style across a whole set. It's also a good model for how to package my own design style as a skill.
**Notes:** Install with `git clone https://github.com/yanliudesign/mono-color-skill.git ~/.claude/skills/mono-color`, then restart Claude Code. It returns the image, the exact prompt, and a short recipe. The code is MIT, but the example images aren't: [ASSET-LICENSE.md](https://github.com/yanliudesign/mono-color-skill/blob/main/ASSET-LICENSE.md) only allows viewing and linking, so they're shown here from the author's repo and not copied. Found via [@prompt_case on Threads](https://www.threads.com/@prompt_case/post/Dcs6FiCHCn3). ~3.5k stars.

<p>
  <img src="https://raw.githubusercontent.com/yanliudesign/mono-color-skill/main/examples/example-cycling.png" width="190" alt="Summer cycling editorial print">
  <img src="https://raw.githubusercontent.com/yanliudesign/mono-color-skill/main/examples/example-zebra.png" width="190" alt="Zebra field-study editorial print">
  <img src="https://raw.githubusercontent.com/yanliudesign/mono-color-skill/main/examples/example-chair.png" width="190" alt="Chair zine editorial print">
</p>

<sub>Images © Yan Liu, loaded directly from the author's repo.</sub>

### [Floating cutaway city poster prompt](https://www.threads.com/@naik_nelofar/post/DdREHihCcVw)
`status: watching` · `tags: prompt, poster, architecture, 3d-style, miniature, reusable-template` · added 2026-11

A template prompt by @naik_nelofar for a 4:5 architecture poster: a city built as a floating miniature model, sliced open to show subways, tunnels, and foundations underneath, on an ivory background with faint blueprint lines.
**Why I care:** It looks far more expensive than a normal AI travel image, and the template should work for any city or country. The detailed cross-section makes it good for a poster series or a high-impact social post.
**Notes:** Slots: `[CITY]`, `[COUNTRY]`, `[REGION]`, and the landmark or cultural feature. The post doesn't say which image model it was made for, and these examples have small blueprint labels worth checking for errors, since AI often gets fine text and facts wrong. The prompt is split across the author's replies (in English). Don't miss the last reply, which adds the cutaway effect.

<p>
  <img src="assets/image-generation/floating-city-1.webp" width="190" alt="Floating city poster example 1">
  <img src="assets/image-generation/floating-city-2.webp" width="190" alt="Floating city poster example 2">
  <img src="assets/image-generation/floating-city-3.webp" width="190" alt="Floating city poster example 3">
</p>

<sub>Examples from @naik_nelofar's post.</sub>

### [Macaron candy poster prompt](https://www.threads.com/@ryobiyori/post/DeENInEkwvV)
`status: watching` · `tags: prompt, photo-to-illustration, poster, kawaii, pastel, travel` · added 2026-11

A ChatGPT prompt by @ryobiyori that makes a side-by-side image: the real photo on the left, and a cute pastel version on the right, built from rounded color blocks that look like stickers or candy.
**Why I care:** It's a very popular format (about 590k views) that turns ordinary travel photos into something shareable. The rules are precise: only five pastel colors, no sharp corners, white rounded outlines between shapes, and small smiling faces on the sun or clouds.
**Notes:** It tells the model to keep any real sign text exactly as written. The poster title and "RYOBIYORI" branding in the examples aren't in the prompt excerpt I read, so expect to add my own title text. The full prompt is in the author's pinned reply (in Traditional Chinese), and only that reply has it, not the main post. Same author as the [Japan scenery poster style](design-references.md#japan-scenery-poster-style).

<p>
  <img src="assets/image-generation/candy-poster-1.webp" width="140" alt="Macaron candy poster example 1">
  <img src="assets/image-generation/candy-poster-2.webp" width="140" alt="Macaron candy poster example 2">
  <img src="assets/image-generation/candy-poster-3.webp" width="140" alt="Macaron candy poster example 3">
  <img src="assets/image-generation/candy-poster-4.webp" width="140" alt="Macaron candy poster example 4">
</p>

<sub>Examples from @ryobiyori's post, cropped to the generated poster.</sub>

### [Minimalist travel poster prompt](https://www.threads.com/@dreamy.designs.ai/post/DcwUmGuGsxr)
`status: watching` · `tags: prompt, poster, travel, flat-illustration, vintage, reusable-template` · added 2026-11

A short template prompt by @dreamy.designs.ai for vintage-style city posters: bold outlines, flat color, lots of empty space, small human figures for scale, and the place name in uppercase typewriter lettering.
**Why I care:** The easiest prompt here to reuse. Swap the three slots and it should hold for any location, which makes it useful for a matching series.
**Notes:** Slots: `[PLACE]`, `[COLOR_PALETTE]`, and `["PLACE_NAME"]`. Made with GPT Image 2, according to the post's label. The prompt ends with Midjourney-style `--ar 2:3 --raw` flags, which other models may treat as plain text. The full prompt is in the second post of the thread (in English). The third post promotes the author's free PDF of more prompts.

<p>
  <img src="assets/image-generation/travel-poster-1.webp" width="120" alt="Travel poster example 1">
  <img src="assets/image-generation/travel-poster-2.webp" width="120" alt="Travel poster example 2">
  <img src="assets/image-generation/travel-poster-3.webp" width="120" alt="Travel poster example 3">
  <img src="assets/image-generation/travel-poster-4.webp" width="120" alt="Travel poster example 4">
  <img src="assets/image-generation/travel-poster-5.webp" width="120" alt="Travel poster example 5">
</p>

<sub>Examples from @dreamy.designs.ai's post.</sub>

### [Modern Eastern culture poster prompt](https://www.threads.com/@orisynthai/post/DdW5C9wAdn7)
`status: watching` · `tags: prompt, poster, editorial, paper-collage, chinese-typography` · added 2026-11

A fill-in-the-blanks prompt by @orisynthai for cultural event posters in a modern Eastern editorial style. It sets huge torn-paper color fields against one tiny story scene, where people and props take up only about 2 to 5% of the image.
**Why I care:** The results look like real design-studio work, not typical AI posters. It gives clear layout rules: one large color shape that still reads at feed size, a small accent color, restrained serif titles, and asymmetric layouts with lots of white space. Those rules are worth reusing in my own design prompts.
**Notes:** Fill in the eight slots: theme, title, main color, micro-scene, character action, cultural elements, event info, and aspect ratio. The post says it was made with "image-2.5". The full prompt runs across the second and third posts of the thread (written in Simplified Chinese).

<p>
  <img src="assets/image-generation/eastern-poster-1.webp" width="140" alt="Eastern culture poster example 1">
  <img src="assets/image-generation/eastern-poster-2.webp" width="140" alt="Eastern culture poster example 2">
  <img src="assets/image-generation/eastern-poster-3.webp" width="140" alt="Eastern culture poster example 3">
  <img src="assets/image-generation/eastern-poster-4.webp" width="140" alt="Eastern culture poster example 4">
</p>

<sub>Examples from @orisynthai's post.</sub>

### [Hand-drawn manga comparison poster prompt](https://www.threads.com/@jenniferzhao08/post/De8X3P3Dpey)
`status: watching` · `tags: prompt, photo-to-illustration, manga, poster, limited-palette` · added 2026-11

A prompt by @jenniferzhao08 that turns an uploaded photo into a 3:4 before/after image: the untouched photo on top, and a Japanese hand-drawn manga poster of the same subject below. It works for people, animals, objects, and scenery.
**Why I care:** A ready-made format for social posts and thumbnails. It locks the art direction with exact hex colors (ink black, warm red, gray-blue on off-white paper) and tells the model to keep only what's visible in the photo, so results stay consistent.
**Notes:** The poster's big title defaults to the author's own "Jen Style", so swap it for my own text. The post doesn't say which image model it was made for. The full prompt is in the second post of the thread (written in Simplified Chinese).

<p>
  <img src="assets/image-generation/manga-poster-1.webp" width="190" alt="Manga poster example 1">
  <img src="assets/image-generation/manga-poster-2.webp" width="190" alt="Manga poster example 2">
  <img src="assets/image-generation/manga-poster-3.webp" width="190" alt="Manga poster example 3">
  <img src="assets/image-generation/manga-poster-4.webp" width="190" alt="Manga poster example 4">
</p>

<sub>Examples from @jenniferzhao08's post, cropped to the generated result.</sub>

### [Photo to knitted art toy prompt](https://www.threads.com/@ammiamia_/post/De8NpXJG5si)
`status: watching` · `tags: prompt, photo-to-toy, 3d-style, knit, character` · added 2026-11

A prompt by @ammiamia_ that turns a real photo into a 1:1 knitted designer-toy bust: a huge rounded head, tiny features, yarn hair, and a soft felt texture on a white studio background.
**Why I care:** Fun, recognisable avatars or stickers from one photo. The prompt separates the photo (what to draw) from an optional style reference (how to draw it), and it limits the model to what's actually visible, so it doesn't invent extra hands or props.
**Notes:** Attach the photo, plus a white-background toy image as the style reference. Text and logos become unreadable knit patterns. The post doesn't say which image model it was made for. The full prompt is in the second post of the thread (written in Traditional Chinese).

<p>
  <img src="assets/image-generation/knit-toy-1.webp" width="190" alt="Knitted toy example 1">
  <img src="assets/image-generation/knit-toy-2.webp" width="190" alt="Knitted toy example 2">
  <img src="assets/image-generation/knit-toy-3.webp" width="190" alt="Knitted toy example 3">
</p>

<sub>Examples from @ammiamia_'s post, cropped to the generated result.</sub>
