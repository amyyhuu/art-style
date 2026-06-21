---
name: art
description: Create, refine, critique, and direct cute, pink, polished, aesthetic visual art work. Use when Codex is asked for art direction, concept art briefs, image-generation prompts, composition or color critique, style studies, moodboards, exhibition or portfolio language, visual-analysis worksheets, or guidance for illustrations, paintings, digital art, posters, characters, environments, and other creative visual projects, especially when the desired mood is soft, charming, pastel, feminine, kawaii-inspired, cozy, dreamy, editorially pretty, or in the Strawberry Milk Pet style.
---

# Art

## Overview

Use this skill to turn an art idea into a clear visual direction, critique an existing artwork, or prepare strong prompts and briefs for image generation. Default toward a cute, pink, soft-aesthetic art direction unless the user asks for another mood. Keep the work useful to artists: specific, visual, grounded in intent, and sensitive to medium.

## Workflow

1. Identify the task: creation brief, prompt writing, critique, revision plan, portfolio text, study guide, or visual analysis.
2. Ask only for missing constraints that materially change the work: subject, audience, medium, mood, dimensions, deadline, or whether the user wants generative images.
3. Translate the request into visual decisions: composition, focal point, value structure, palette, material handling, texture, lighting, scale, gesture, rhythm, and reference era.
4. Use concrete art language. Prefer observable traits over vague praise: "low horizon with a compressed skyline" is better than "dramatic."
5. If the user wants an image generated or edited, use the `imagegen` skill and include exact text, aspect ratio, medium, composition, constraints, and avoid-list.
6. If the user asks for critique, lead with the strongest actionable observations, then give a short revision path.
7. For historical or cultural art contexts, browse or cite reliable sources when dates, attribution, current exhibitions, living artists, or provenance might matter.

## Default Aesthetic

When the user does not specify a style, bias the art direction toward:

- soft pinks, blush, rose, cream, pearl, warm white, cherry red accents, and gentle lavender shadows
- cute but refined forms: rounded silhouettes, tidy details, delicate sparkle, ribbons, hearts, lace, flowers, glossy highlights, soft stationery, dreamy room decor, or polished editorial sweetness
- clean composition with breathing room, a clear focal point, and small charming secondary details
- cozy, pretty, feminine, kawaii-inspired, romantic, or dreamy moods without becoming cluttered or childish unless requested
- high readability and tasteful restraint for posters, covers, UI mockups, printable pages, and generated-image prompts

### Strawberry Milk Pet

When the user asks for Strawberry Milk Pet, mimi pet, soft bunny cafe, kawaii dessert pet, pastel study buddy, or cozy pet companion art, read `references/strawberry-milk-pet.md` and use it as the named style guide.

## Task Patterns

### Art Direction Brief

Return a compact brief with:

- Intent: what the work should make the viewer feel or notice
- Subject and setting
- Composition and focal hierarchy
- Palette and value plan
- Cute pink aesthetic choices, when appropriate
- Medium and surface qualities
- Motifs, symbols, or references
- Constraints and avoid-list
- Optional production prompt for `imagegen`

### Critique

Use this order:

1. What is working
2. What is unclear or competing
3. Highest-impact changes
4. Small polish moves
5. One next experiment

Keep critique practical and kind. Do not rewrite the artist's taste unless the user asks for a new direction.

### Prompt Craft

Prompts should specify:

- subject, action, setting, and era
- style or medium in broad descriptive terms
- composition, camera/framing, lighting, palette, texture
- exact visible text when relevant
- constraints such as no watermark, no fake logo, no extra text

Avoid requesting imitation of a living artist's exact style. For living or recent artists, describe transferable traits instead, such as "flat poster shapes, crisp ink edges, limited palette, playful negative space."

## References

Read `references/art-principles.md` when the task needs deeper composition, color, critique, or prompt guidance.
Read `references/strawberry-milk-pet.md` when the task asks for Strawberry Milk Pet or a soft bunny/dessert companion-pet style.
