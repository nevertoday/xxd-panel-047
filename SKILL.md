---
name: xxd-panel-047
description: "Create XXD Panel 047 artwork from supplied photos in four combinable modes: photo above/refined isometric miniature standing in a source-derived impasto spatial field on real paper below, photo left/design right, design alone, or a four-device wallpaper pack with independent or anchor-linked continuity. Use for the exact 047 style; reject flat pasted illustration, rectangular colour swatch, miniature disconnected from paint, plastic CGI, toy-model display, generic diorama, grey or Morandi palette, fluorescent or candy colour, excessive secondary scenery, unstable floating subject, template micro-landscape."
---

# XXD Panel 047 · 厚涂色域轴测微景观

Rebuild the recognisable subject as a refined volumetric isometric miniature that truly stands, grows, lands, reflects, or passes through a source-derived impasto theme field. Thick palette-knife paint becomes water, ground, road, grass, light, shoreline, or shadow rather than a rectangular backdrop.

Operational rules follow the shared XXD Panel workflow contract: four combinable modes; source-adaptive ordinary canvases; exact 50/50 paired geometry; linked or independent four-device wallpapers; copy and locale preflight; fresh generation jobs; privacy-preserving raster generation; and one fresh task directory per source and mode. Style-specific sections refine aesthetics and copy but never override this contract.

## Non-negotiable contract

- One source may use one or more selected modes. Each selected ordinary mode (`top-bottom`, `left-right`, `design-only`) produces one PNG; `wallpaper-pack` produces four separate PNGs. Selecting all four modes produces seven final files per source. Never combine them into a grid, contact sheet, overview, or mockup.
- Resolve a non-empty ordered set of modes. Accept one choice, multiple choices separated by `+`, Chinese/English commas or whitespace, natural-language names, or `全部` / `all`; deduplicate and execute in menu order 1→4.
- If `wallpaper-pack` is selected, resolve `linked` or `independent`. A linked pack approves one iPad anchor by default, then every other device references the original source plus that same anchor. An independent pack gives every device only the original. Never crop one wallpaper into another and never chain derivatives.
- Paired modes split exactly 50/50. `design-only` and every wallpaper show no source photo, seam, or reserved photographic panel.
- Exact user pixels win, then explicit ratio/destination. Otherwise adapt losslessly: `top-bottom` = `W×2H`, `left-right` = `2W×H`, `design-only` = `W×H`. The archived 3:4 canvas is not a silent default.
- Keep visible photography faithful: restrained editorial grading and necessary environmental extension only; never stretch, distort, repaint, replace, or structurally alter the source.
- Preserve at least three source-specific identity, structure, pose, direction, action, function, opening, colour, distance, or relation cues in every transformed frame.
- Copy has no silent default. Before generation resolve `自动文案`, `自定义文案`, or `无文字`; automatic and custom modes also require target language or locale. Preserve exact user copy verbatim.
- Render no logo, watermark, signature, colour swatch, UI, device mockup, decorative pseudo-text, or unrelated prose.

## Aesthetic motive lock

Every transformed frame must visibly follow this source-bound chain:

**lock identity, volume, direction, and landing point → preserve three cues → rebuild one refined isometric miniature → derive one thematic spatial slice from source content → turn impasto into water, ground, road, grass, light, shore, or shadow → create real contact, embedding, crossing, reflection, ripple, cast shadow, or edge escape → keep warm-white paper breathing space → align copy to perspective and paint edge**.

Reject the result as generic if an unrelated photograph could replace the source without materially changing recognition, construction, placement, material, colour relation, whitespace, or copy. The operative exclusions are: flat pasted illustration, rectangular colour swatch, miniature disconnected from paint, plastic CGI, toy-model display, generic diorama, grey or Morandi palette, fluorescent or candy colour, excessive secondary scenery, unstable floating subject, template micro-landscape.

## 047 visual system

- Preserve at least three cues across silhouette, proportion, axis, direction, opening, structure, action, material, landing point, or relation.
- Build one refined isometric miniature with clear volume, stable contact, front-back relation, sculptural structure, and a unified oblique axis; it is not a flat illustration or generic toy model.
- Derive one thematic impasto field from source content and make it a spatial slice—water, ground, road, grass, light, shore, shadow, or another supported environment—not a rectangle or decorative colour swatch.
- The miniature must physically land, embed, cross, extend, reflect, ripple, cast a shadow, or escape the paint edge. Thick palette-knife ridges, piled pigment, raised edges, and hand strokes connect 2D paint to 3D form.
- Use the source's brightest spirited colours, clarified for life and purity, with abundant clean warm white and a small sunlit accent; reject grey dirt, Morandi dulling, fluorescence, and cheap candy colour.
- Keep one visual centre, diagonal depth, stable gravity, source-directed placement, and large whitespace; any cloud, sun, plant, wave, or natural motif remains low weight.

## Copy belongs to the image language

Use one concise subject, place, emotion, or symbolic title plus only necessary subtitle, supplied number, or micro-note. Align native type with isometric direction, impasto edge, perspective route, or warm-white field; it must echo the space rather than float as a separate headline.

Copy must pass the unrelated-image swap test. Preserve exact supplied wording verbatim; refine only an explicitly editable direction while protecting audience, purpose, mandatory words, tone, implication, and semantic line breaks.

Resolve locale independently from command language:

```text
target market or audience > requested output language > direction language; if none is explicit, ask before generation
```

Use native wording, rhetoric, punctuation, spacing, shaping, direction, and line breaks. Never infer nationality or audience language from appearance, clothing, scenery, filenames, metadata, or signs.

## Raster generation and privacy

Use the host's built-in bitmap generation capability by default and follow the available `imagegen` skill when exposed. Use one generation call per distinct asset; a wallpaper pack needs four. Style language describes raster appearance only and never authorises SVG, HTML, CSS, Canvas, 3D code, diagrams, or programmatic drawing as the artwork.

If built-in generation is unavailable, use the bundled privacy-safe configured route:

```bash
python3 scripts/configured_imagegen.py probe
python3 scripts/configured_imagegen.py edit --image source.png \
  --prompt-file /private/job-temp/transform-prompt.txt \
  --out /private/job-temp/design.png --size 1536x1024 --quality high
```

Judge readiness by actual bitmap capability, not a provider name or a single environment variable. Never display, log, persist, or report providers, endpoints, headers, credentials, account identifiers, route configuration, prompts, responses, or secrets. The bridge's sanitised status is the entire allowed diagnostic surface. An explicit invocation with source and desired output authorises any already configured authenticated bitmap route available to the session; do not request another confirmation solely because the route changes.

Only report generation unavailable after built-in bitmap capability and the bundled sanitised probe both fail. State the limitation narrowly, never guess its cause, and never substitute code-rendered art.

## Fresh-task and source boundary

Every invocation starts a fresh job unless the user explicitly asks to continue, audit, compare, edit, or reuse a named result. Repeating the same source and settings still requires fresh generation. An old file can never satisfy a new request.

Use only current attachments, explicit paths, or a previously supplied image clearly identified by the user. Never scan Desktop, `~/Desktop/xxd/xxd-panel-047/`, or historical task folders for a substitute.

## Workflow

1. If mode is unresolved, ask in normal multiline text and wait:

   ```text
   请选择一个或多个模式（回复序号；多选可用 +、顿号或逗号）：

   1. 上下双联（完整原图＋同尺寸设计图）
   2. 左右双联（完整原图＋同尺寸设计图）
   3. 纯设计版（沿用原图比例，不显示原照片）
   4. 四端壁纸套装
      手机＋iPad＋电脑＋儿童手表

   前三种不指定尺寸时按原图自适应；也可主动指定尺寸。壁纸可按设备分别给分辨率。
   示例：1｜1+3｜1、2、4｜全部
   ```

2. If wallpaper relationship is unresolved, ask for `1. 连贯套装（原图＋同一批准定调图）` or `2. 四张独立（每张只参考原图）`.
3. Before generation, ask for `1. 自动文案（注明语言／地区）`, `2. 自定义文案（准确文字＋语言／地区）`, or `3. 无文字` when unresolved.
4. Resolve dimensions per mode. For wallpapers ask for labelled custom sizes or the common preset: phone `1440×3200`, iPad `2048×2732`, desktop `3840×2160`, watch `1024×1024`. Exact paired canvases require even split axes; never silently round.
5. View the source and privately lock identity, at least three recognition cues, structure, action, relation, emotional implication, colour logic, copy payload, and target locale. Do not claim unsupported facts.
6. Create a new collision-safe root under `~/Desktop/xxd/xxd-panel-047/`, then one source folder and sibling mode folders. Never overwrite or use an old output as completion evidence.
7. Read `references/xxd-panel-047-prompt.en.md` or `.zh-CN.md`, append the locked source facts, exact copy payload, `OUTPUT MODE`, `FINAL SIZE`, and `DESIGN FRAME`, then generate each distinct design frame separately.
8. For paired modes, generate only the design panel at the planned half-frame size and compose with `scripts/compose_panel.py`. For design-only and wallpapers, generate the whole canvas without the source photo or a seam.
9. Inspect every result at full size. Correct the asset—not only the prompt—until identity, style, copy, locale, raster format, dimensions, and count pass.

## Output structure

```text
~/Desktop/xxd/xxd-panel-047/<fresh-task>/
└── source-01/
    ├── top-bottom/final.png
    ├── left-right/final.png
    ├── design-only/final.png
    └── wallpaper-pack/phone.png · ipad.png · desktop.png · watch.png
```

Create only selected folders. Return direct PNG paths and a concise count summary. Do not create an automatic combined preview.

## Acceptance gate

- Correct fresh source, selected modes, dimensions, file count, and exact 50/50 paired geometry.
- At least three source-specific recognition cues remain; the source-specific chain and every visual-system requirement above are visible.
- Copy is exact, language-native, legible, and structurally integrated; text-free output contains no text or pseudo-text.
- Linked wallpapers share the original source and same approved anchor without derivative chaining; independent wallpapers use only the source.
- Final files are raster PNGs. No SVG/HTML/Canvas/programmatic-art substitute, mockup, overview, UI, watermark, or leaked private route information.

## Override policy

Preserve explicit subject, mode set, output count, exact pixels or ratios, wallpaper relationship, copy mode, exact wording, locale, and intended meaning. User overrides may alter these variables but do not silently authorise abandoning source identity, the 047 aesthetic motive, fresh-task isolation, raster-only output, privacy, or verification. If the user explicitly requests a different aesthetic, acknowledge that it leaves this Skill's style rather than pretending it remains 047.

## References

- Read `references/xxd-panel-047-prompt.en.md` or `references/xxd-panel-047-prompt.zh-CN.md` immediately before generation.
- `references/047-source.md` archives the original style brief and is evidence, not an implicit 3:4 default.
