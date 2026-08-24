# XXD Panel 047 | Isometric Impasto Micro-Landscape Production Prompt

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Process only the source photograph explicitly supplied for this fresh task. Privately lock identity, structure, pose, direction, action, function, opening, relation, emotional implication, and source colour. Preserve at least three source-specific cues and never borrow from another input, old output, or sample.

## Aesthetic transformation

Rebuild the recognisable subject as a refined volumetric isometric miniature that truly stands, grows, lands, reflects, or passes through a source-derived impasto theme field. Thick palette-knife paint becomes water, ground, road, grass, light, shoreline, or shadow rather than a rectangular backdrop.

Use this causal sequence: lock identity, volume, direction, and landing point → preserve three cues → rebuild one refined isometric miniature → derive one thematic spatial slice from source content → turn impasto into water, ground, road, grass, light, shore, or shadow → create real contact, embedding, crossing, reflection, ripple, cast shadow, or edge escape → keep warm-white paper breathing space → align copy to perspective and paint edge.

## Hard visual requirements

- Preserve at least three cues across silhouette, proportion, axis, direction, opening, structure, action, material, landing point, or relation.
- Build one refined isometric miniature with clear volume, stable contact, front-back relation, sculptural structure, and a unified oblique axis; it is not a flat illustration or generic toy model.
- Derive one thematic impasto field from source content and make it a spatial slice—water, ground, road, grass, light, shore, shadow, or another supported environment—not a rectangle or decorative colour swatch.
- The miniature must physically land, embed, cross, extend, reflect, ripple, cast a shadow, or escape the paint edge. Thick palette-knife ridges, piled pigment, raised edges, and hand strokes connect 2D paint to 3D form.
- Use the source's brightest spirited colours, clarified for life and purity, with abundant clean warm white and a small sunlit accent; reject grey dirt, Morandi dulling, fluorescence, and cheap candy colour.
- Keep one visual centre, diagonal depth, stable gravity, source-directed placement, and large whitespace; any cloud, sun, plant, wave, or natural motif remains low weight.

## Copy and locale

Obey the resolved automatic, exact-user, or text-free copy mode and target locale. Use one concise subject, place, emotion, or symbolic title plus only necessary subtitle, supplied number, or micro-note. Align native type with isometric direction, impasto edge, perspective route, or warm-white field; it must echo the space rather than float as a separate headline. Preserve exact user wording verbatim. In text-free mode render no letters, numbers, captions, labels, or pseudo-text.

## Mode and acceptance


Reject: flat pasted illustration, rectangular colour swatch, miniature disconnected from paint, plastic CGI, toy-model display, generic diorama, grey or Morandi palette, fluorescent or candy colour, excessive secondary scenery, unstable floating subject, template micro-landscape. Also reject logos, watermarks, swatches, UI, device mockups, unsupported facts, fake foreign text, and unreadable copy.

If any hard condition fails, correct the generated bitmap. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, 3D code, or a post-composited type overlay.
