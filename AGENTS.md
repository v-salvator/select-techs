# Agent instructions

Rules for AI agents contributing to this repo. Human contributors should follow the same conventions.

## Image-generation entries

Entries in `image-generation.md` and `design-references.md` **must** include example images.

### Source fidelity

- Use **original images from the source post** in their **original order**.
- Include `min(original_count, 5)` images — all images up to five; for carousels with more than five, use the first five unless the user specifies otherwise.
- **Faithful content:** preserve prompt overlays, UI chrome, and other context visible in the original; do not crop art out of its surrounding frame unless the template already does (e.g., "cropped to the generated half" entries).
- Do **not** substitute your own generated samples, reply images, or images from other posts.
- Do **not** invent or fabricate missing images.

### Access and licensing

- If you cannot access a source image, note the access failure honestly in the entry rather than omitting the image silently.
- Respect **actual explicit copying restrictions** stated by the creator. Absence of an express license is not itself an express prohibition, but if the source states images may not be copied, link to the source instead and note why no local copy is included.

### Thumbnails and markup

- Save images in the matching `assets/` subfolder (e.g., `assets/image-generation/`).
- Resize to small thumbnails (~400px wide) as webp.
- Use the existing HTML markup pattern: `<p><img src="..." width="..." alt="..."></p>` followed by `<sub>` caption crediting the creator and linking to the canonical source.
- For real photos of people, crop them out. AI-generated people do not require cropping.

### Migration and validation

- Do **not** bulk-migrate or remove images from historical entries that predate these rules.
- A linter cannot verify original carousel count or order; these rules are for agent judgment, not automated enforcement.
