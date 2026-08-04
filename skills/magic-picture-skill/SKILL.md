---
name: magic-picture-skill
description: Generate poetic minimal paper-poster prompts and matching images from a theme, sentence, object, mood, article idea, or photo. Produces quiet Japanese/Korean zine-like editorial posters with large negative space, aged paper, experimental typography, restrained color accents, and a generated raster image.
---

# Magic Picture Skill

Turn the user's content into both:

1. a final image-generation prompt; and
2. a generated raster image made from that prompt.

## Mode policy

Use **Standard Mode** for all generation. Compile the user's content into a compact, imageable, high-fidelity prompt. When the user asks for higher quality, make the prompt more concrete rather than longer by default.

## Standard Mode Prompt Compiler

Use only information that can become visible pixels in the final image prompt.

### Visual identity

- poetic minimal paper poster
- huge negative space
- old paper and imperfect printing
- one small image anchor
- sparse serif or typewriter typography
- one clear high-chroma color anchor
- quiet zine/editorial mood

### Non-negotiables

- vertical 3:5 paper canvas
- small visual cluster with substantial surrounding paper
- scanned-paper view and old print defects
- serif, typewriter, or monospaced typography
- one saturated color anchor visible at thumbnail size

### Replaceable variables

- object, photo, cutout, silhouette, or type block
- accent color
- short text line
- date, weather, location, or signature
- position and paper tone

### Do not compile by default

- source paths, metadata notes, sample counts, or analysis scope
- long prose explaining the aesthetic
- sample-specific signatures, dates, captions, or objects
- checklist wording that is not a visible visual constraint

## First-principles prompt fields

Every Standard Mode prompt should answer these questions in this order.

1. **Canvas** — tall vertical 3:5 phone-poster; full-frame aged paper; no border or mockup.
2. **Attention geometry** — 70%–90% plain paper; one cluster occupying about 8%–25%; placed center, upper-middle, lower-middle, lower-left, or upper-right; do not hug edges.
3. **Image anchor** — reduce the user's theme to one object, fragment, photo crop, specimen, cutout, silhouette, old printed illustration, texture window, or small conceptual relation.
4. **Anchor treatment** — use photocopy softness, torn edges, halftone, scanlines, risograph grain, xerox wear, ink bleed, or slight misregistration where appropriate. Do not wash out the chosen color anchor.
5. **Typography system** — small serif/typewriter/monospaced type; one short readable phrase; optional tiny date, location, weather, or signature; semi-legible microtext and fragmented letters may drift, blur, or misregister.
6. **Color logic** — paper tones plus gray/black support one unmistakably high-chroma anchor. The color may be the subject, silhouette, irregular cutout, substantial block, partial-color photo region, or bold fragmented type.
7. **Reproduction texture** — flat orthographic scanned-paper appearance; matte absorbent paper; diffuse light; low-to-medium contrast; no hard shadow or 3D depth.
8. **Emotional temperature** — quiet, poetic, nostalgic, sparse, diary-like, archival, distant, memory-like Japanese/Korean indie zine or minimal editorial.
9. **Hard avoids** — full-bleed scene, commercial headline, product-ad layout, logo/CTA, glossy mockup, clean UI white, cinematic lighting, 3D, neon, cute cartoon, fashion-editorial drama, dense scrapbook, too many colors, or long clean text.

## Standard Color Engine

- Default to one visibly saturated, opaque chromatic ink anchor.
- Use decisive wording such as `fully saturated cobalt-blue risograph ink`, `opaque ultramarine cutout`, `vivid pear-green flat silhouette`, or `clean tomato-red printed block`.
- Keep paper, grayscale photos, microtext, and secondary marks subdued; preserve the saturation of the main anchor even when grain or halftone is present.
- The high-chroma area should occupy roughly 0.8%–2.5% of the entire canvas, or 15%–35% of the visual cluster, and remain visible at thumbnail size.
- Let color carry the subject when possible: a colored tree, fruit, shell, flower, geometric cutout, window, poster fragment, or image panel is stronger than a gray object with a tiny registration tick.
- Use one main high-chroma hue per image. A tiny secondary hue is allowed only when it supports the subject without becoming commercial or colorful.
- Do not use `near-monochrome`, `no strong accent`, `pale accent`, `muted accent`, `faded accent`, or `pastel accent` unless the user explicitly asks for it.
- Do not describe the entire image as low saturation; apply muted grayscale or low contrast only to paper, photographs, and supporting ink.

## Standard Prompt Shape

Write the final prompt as four compact paragraphs:

1. canvas + paper + negative space + cluster size/location
2. subject metaphor + anchor type + anchor treatment
3. typography + accent strategy + print defects
4. flat-scan mood + avoid list

In paragraph three, name the exact high-chroma hue, its material form, and its approximate visual share. Prefer concrete visual instructions over a long style essay.

## Variation Engine

Select one option from each axis before writing the prompt. Change visual grammar between recent outputs, not only the position.

### Layout family

- `center-fragment`: tiny central image or object with surrounding air
- `lower-left-float`: small anchor in the lower-left with lots of empty top space
- `upper-right-block`: small color/photo block in the upper-right with loose text drift
- `dual-panel`: two small overlapping or adjacent panels with a narrow gap
- `irregular-cutout`: torn or organic paper shape carrying image or type
- `type-led`: typography is the main anchor, image is secondary or absent
- `dot-orbit`: dots, letters, or hairlines orbit a small subject
- `single-specimen`: one isolated object or mark with almost no support graphics

### Image anchor

- tiny faded photo
- torn-paper clipping
- flat silhouette
- solid color block
- old printed illustration
- object specimen
- translucent geometric overlay
- abstract texture window

### Typography mode

- fragmented floating letters
- short phrase pressed against image edge
- archive microtext with date/weather
- diagonal scattered words
- low-contrast gray ghost text
- headline-as-object with rough letterpress
- text inside a color block or cutout
- almost textless, only a tiny caption

### Texture mode

- xerox softness
- risograph grain
- letterpress ink bleed
- halftone degradation
- film-grain photo
- scan noise and paper fibers
- aged paper mottling
- soft motion blur on selected text

### Mood mode

- quiet
- summer
- solitude
- childhood
- seaside
- afternoon
- night
- memory
- slight surrealism

## Workflow

1. Use Standard Mode.
2. Parse the user's content for the core subject, mood, exact text, possible visual metaphor, and any reference-image role.
3. For an article or complex idea, extract one central imageable idea rather than illustrating the whole argument.
4. If no image text is supplied, invent one short poetic English or Chinese phrase.
5. Choose a variation recipe: layout, image anchor, typography, texture, mood, and color.
6. If the recipe becomes too dense, simplify typography or color treatment first.
7. Compile the four-paragraph prompt. Specify where the anchor sits, how large it is, how text behaves, what accent appears, and how the printing texture works.
8. Generate the image with the built-in image-generation capability.
9. Inspect at thumbnail scale. If the saturated anchor is missing, washed out, or imperceptible, regenerate once with stronger color wording and a larger colored area.
10. Return the generated image, final prompt, mode, recipe, and one short interpretation note.

## Negative constraints

Always avoid:

- full-bleed subject or scene
- commercial poster headline hierarchy
- product-ad layout, logo lockup, CTA, or brand-campaign feeling
- clean digital UI background
- glossy paper mockup or heavy paper shadow
- 3D rendering, cinematic lighting, hard shadows, depth of field, neon, or cyberpunk
- cute cartoon, kawaii illustration, anime poster, or fashion-editorial drama
- too many objects, stickers, colors, captions, or decorative textures
- high-resolution stock-photo realism
- long, clean, perfectly readable text blocks

## Output format

````markdown
**生成图**

![Magic Picture poster](absolute-image-path-or-rendered-image)

**最终 Prompt**

```text
[final prompt used for image generation]
```

**说明**

- Mode: Standard
- Recipe: [layout / anchor / typography / accent / texture / mood]
- [one short note about the content interpretation]
````

## Quality Gate

Before finalizing, verify:

- Standard Mode and the prompt compiler were used.
- The variation recipe includes layout, anchor, typography, accent, texture, and mood.
- The structure differs materially from recent visible outputs.
- The image remains a sparse vertical paper poster.
- 70%–90% reads as paper and the subject cluster is roughly 8%–25% of the canvas.
- There is one clear visual metaphor rather than a complete illustrated scene.
- The anchor belongs to the paper through clipping, scan, print, or specimen treatment.
- Typography and microtext are compositional elements.
- There is only one restrained accent strategy.
- The high-chroma anchor is clearly visible at thumbnail size and occupies about 0.8%–2.5% of canvas or 15%–35% of the cluster.
- The prompt does not weaken the main accent with pale, muted, faded, pastel, low-saturation, or near-monochrome wording unless the user explicitly requested it.
- The prompt avoids full-bleed, commercial, 3D, neon, cinematic, cartoon, cute, brand, and generic-template aesthetics.
- An image was actually generated.

## Example requests

- `做一张关于雨天的图`
- `标准模式，做一张关于旧书的图`
- `用这张照片做一张同风格 poster`
