---
name: scientific-figure-style
description: Create or restyle editable scientific figures, workflow diagrams, method architectures, result graphics, and research visuals for papers, presentations, or reports.
---

# Scientific Figure Style

Use this project style for scientific and technical figures unless the user explicitly requests another visual style. User instructions always override aesthetic defaults. Keep the scientific-accuracy, editability, legibility, and no-clipping requirements unless the user explicitly changes those requirements too.

## Intended outcome

Create restrained, publication-friendly figures that look deliberately designed by a researcher or scientific illustrator:

- White canvas, strong deep-blue headings, black-gray body text.
- Thin blue outlines, modest rounded corners, pale-blue support panels, restrained blue-green accents.
- Clear reading order, visible grouping, consistent arrows, generous whitespace, and grid alignment.
- Native editable vectors and text whenever the output format supports them.
- No generic AI-poster appearance, excessive decoration, or visual effects that compete with the scientific message.

Apply this style to scientific-paper workflows, method and system architectures, data-processing pipelines, knowledge graphs, experimental designs, result figures, composite figures, PPT illustrations, and report graphics. Do not impose it on unrelated branding, web UI, decorative illustration, or photo-generation tasks.

## Priority order

1. Preserve the user's content, requested format, language, dimensions, and explicit style references.
2. Preserve data integrity and scientific meaning.
3. Make the source editable and the exported result readable.
4. Apply this visual system.
5. Add polish only when it does not weaken clarity or accuracy.

If a user supplies a different style, theme, journal template, brand palette, or slide master, follow it instead of this palette and layout language. Use this skill only to fill unspecified choices and to retain technical quality.

## Build workflow

1. Extract the scientific story before drawing: entities, stages, inputs, transformations, outputs, comparisons, feedback, and evidence.
2. Verify the intended relation for every connector. Distinguish sequence, data flow, control flow, hierarchy, dependency, comparison, feedback, and association.
3. Select the smallest layout template that expresses the story without decorative complexity.
4. Establish a grid, margins, module sizes, title hierarchy, and connector routes before adding detail.
5. Build with native text, shapes, lines, tables, and charts. Recreate raster references as editable vectors when practical; do not simply place a screenshot when the user asks for editable output.
6. Add color only after the grayscale hierarchy works. Use accent colors to encode meaning, not to fill empty space.
7. Render or export a preview and inspect it at both normal size and thumbnail size. Fix overflow, collisions, awkward routes, inconsistent spacing, and unreadable text before delivery.
8. Deliver the editable source first, plus a preview or publication export when requested or useful.

## Visual system

### Canvas and hierarchy

- Default to a white background `#FFFFFF`.
- Use near-white neutral panels `#F7F9FC` only to separate large regions.
- Make one dominant title level, one module-heading level, and one body-text level. Avoid more than three visible text levels in one figure.
- Prefer a single obvious reading direction: left-to-right for pipelines and comparisons; top-to-bottom for staged processing or layered systems.
- Make the main path visually strongest. Place supporting dictionaries, controls, evidence, or examples above, below, or to the side with lighter treatment.

### Color palette

Use the following as defaults, not as a quota:

| Role | HEX | Use |
| --- | --- | --- |
| Deep blue | `#0B4F9C` | Figure title, major section titles, key labels |
| Primary blue | `#1E64B7` | Borders, arrows, active steps, table rules |
| Mid blue | `#5B8FD9` | Secondary emphasis, selected data series |
| Pale blue | `#EAF3FF` | Support panels, grouped backgrounds |
| Soft blue | `#D8E8F8` | Header bands, subtle callouts |
| Teal | `#2A9D8F` | One complementary category or successful outcome |
| Soft teal | `#BFE3DC` | Teal background tint |
| Main text | `#20242B` | Body text and labels |
| Secondary text | `#5E6872` | Notes, sources, secondary annotations |
| Neutral line | `#CBD5E1` | Light dividers, non-primary structure |

Use deep blue, primary blue, and neutrals for most of the figure. Teal should normally occupy less visual area than blue. Use orange `#D98324` only for a scientifically meaningful warning or exception and red `#C43D4B` only for errors, exclusions, or negative states. Do not use rainbow palettes unless the data semantics require them. Keep text/background contrast suitable for projection and print.

### Typography

- Use clean sans-serif fonts. Preferred Chinese fonts: Microsoft YaHei, Source Han Sans SC, or Noto Sans CJK SC. Preferred Latin fonts: Arial, Aptos, Helvetica, or an available metrically similar sans serif.
- Use one family per language when possible and no more than two families in a figure.
- Use bold or semibold for titles; use regular weight for body text. Do not simulate hierarchy with multiple decorative fonts.
- PPT or 16:9 figure guideline: main title 24–32 pt, section title 18–24 pt, module title 16–20 pt, body 13–18 pt, note/source 10–12 pt.
- Paper guideline at final print size: figure title 10–12 pt when included, panel or section title 9–11 pt, labels 7.5–9.5 pt, notes no smaller than 7 pt.
- Use line spacing around 1.1–1.25 and keep 4–10 pt internal separation between title and body.
- Prefer short noun phrases and parallel grammar. Wrap intentionally at semantic boundaries. Increase the box size before reducing font size.
- Keep all text live and editable. Check font substitution and final glyph rendering, especially for mixed Chinese, Latin text, symbols, subscripts, and Greek letters.

### Shapes, borders, and grouping

- Use rectangular or modestly rounded containers. Default corner radius should feel restrained: roughly 6–12 pt in PPT or 1–2% of figure width.
- Use thin strokes: about 1.25–1.75 pt for PPT and 0.8–1.2 pt at paper scale.
- Use solid blue outlines for primary modules. Use pale-blue fills for secondary modules. Reserve full deep-blue fills for a small number of anchors, final outputs, or high-priority labels; use white text on those fills.
- Use dashed blue or gray outlines for conceptual groups, optional stages, examples, or scope boundaries. Use one dash pattern consistently, such as 4:3 or its visual equivalent.
- Avoid double borders, heavy shadows, bevels, gloss, glass effects, and ornamental frames.
- Tables should use thin rules, a clear blue header, and minimal internal grid lines. Avoid dense spreadsheet styling.

### Grid, alignment, and whitespace

- Use an 8 pt design unit where the format permits. Build gaps and padding from consistent multiples rather than ad hoc spacing.
- Keep outer margins near 5–7% of the canvas width/height. Increase margins for journal figures with captions outside the artwork.
- Use 16–24 pt internal padding in PPT-sized modules, 24–40 pt between major modules, and visibly larger gaps between groups than within groups.
- Align module edges, centers, baselines, and repeated labels. Repeated nodes should have equal dimensions unless a deliberate hierarchy requires otherwise.
- Keep whitespace as structure. Do not enlarge icons or add decoration merely to occupy empty areas.
- Prefer two or three columns over many small scattered boxes. Avoid orphan labels and uneven visual weight.

### Arrows and logic

- Use orthogonal connectors for structured pipelines and architectures; use straight connectors when the path is simple and unobstructed.
- Default arrow stroke: primary blue or dark gray, about 1.2–1.8 pt in PPT. Use modest arrowheads and consistent end spacing.
- Route connectors behind nodes and text. Avoid line crossings; if one is unavoidable, use a bridge or reroute the layout.
- Label a connector only when the relation is not obvious. Place labels close to the relevant segment without touching the line.
- Use solid arrows for main flow, dashed arrows for optional/indirect relationships, and a clear return arrow for feedback loops.
- Never use a causal arrow for a merely associated relationship. Do not reverse input/output direction, hierarchy, or temporal order for layout convenience.

### Icons and illustrations

- Use icons only when they speed recognition or reduce text. A text label alone is preferable when an icon adds ambiguity.
- Prefer simple monoline or flat two-color vector icons that share one stroke weight and visual family.
- Keep icons subordinate to the scientific content; use them at a consistent size and align them to the same optical center.
- Do not use emoji, glossy clip art, photorealistic stock images, 3D objects, glowing neural networks, decorative molecules, or unrelated laboratory imagery.
- Do not invent biological structures or apparatus details. If a domain-specific symbol might be scientifically ambiguous, label it or omit it.

## Layout templates

Choose one primary template and adapt it to the content.

### Linear workflow

Use for preprocessing, analysis, annotation, modeling, and export sequences.

- Arrange 3–7 major stages on one horizontal or vertical axis.
- Put inputs at the start and deliverables at the end.
- Place quality control, dictionaries, or external knowledge as smaller support modules adjacent to the stage they affect.
- If there are more than seven stages, group them into phases instead of shrinking everything.

### Layered architecture

Use for data, services, algorithms, applications, or governance stacks.

- Use broad horizontal bands or aligned vertical layers.
- Show dependency direction consistently.
- Use a pale-blue shared background or dashed group for a common platform; reserve deep blue for the core or output layer.
- Avoid pseudo-3D stacks and perspective.

### Input–process–output

Use for method summaries and compact paper figures.

- Left: sources or raw data.
- Center: transformations, models, or quality control.
- Right: outputs, results, or users.
- Make the center visually dominant only when the method—not the dataset—is the paper's contribution.

### Comparison or evidence matrix

Use for baselines, conditions, databases, model capabilities, or before/after states.

- Use aligned columns, shared row labels, and one consistent comparison axis.
- Highlight no more than one preferred option per comparison unless the data require multiple emphasis states.
- Keep numbers, units, decimal precision, and missing-value notation consistent.

### Feedback or iterative system

Use for curation loops, active learning, quality review, or human-in-the-loop workflows.

- Keep the main forward path linear.
- Return one clearly labeled feedback arrow along the outside of the layout.
- Distinguish automated and human steps with fill or line style, not with decorative characters.

### Multi-panel result figure

Use for plots, microscopy, tables, and summary diagrams in one scientific figure.

- Build a shared outer grid and label panels A, B, C… consistently.
- Give plots more area than captions or decorative headers.
- Align axes and plot areas where comparisons are intended.
- Put legends close to the data and use one shared legend when valid.
- Use the blue-green palette for categories only when it remains distinguishable in grayscale or with direct labels.

## Result-chart requirements

- Select chart types from the analytical question, not from visual novelty.
- Preserve raw values, units, axes, sample sizes, uncertainty intervals, statistical tests, and significance notation supplied by the user.
- Do not invent values, smooth data without disclosure, truncate axes misleadingly, or use area/volume to encode a one-dimensional value.
- Prefer direct labels and restrained grid lines. Remove chart junk but retain essential scales and reference lines.
- Use consistent category-color mappings across panels and slides.
- When color alone is insufficient, add direct labels, marker shapes, line styles, or patterns.
- Separate observed results from interpretation. A callout may summarize a supported finding but must not overstate causality or certainty.

## Editable-output rules

### PowerPoint

- Build with native PowerPoint text boxes, shapes, lines, tables, and charts wherever possible.
- Group each logical module without flattening the whole slide into one image.
- Keep connector attachment points stable when boxes move.
- Place any unavoidable raster image in its own replaceable layer and retain labels/arrows as editable objects above it.
- Respect the slide master, theme fonts, and user-specified slide size when supplied.

### SVG

- Use real vector paths/shapes and live text unless font portability requires outlined text for the final publication copy.
- Keep a live-text source version when producing an outlined publication version.
- Use explicit viewBox dimensions, consistent strokes, and no clipped filters or off-canvas elements.
- Avoid embedded raster content unless the source data are inherently raster, such as microscopy.

### PDF and raster exports

- Treat PDF, PNG, and TIFF as delivery/export formats, not replacements for the editable source.
- Export at the target physical size. For raster journal output, use the journal-required resolution; otherwise prefer at least 300 dpi for print.
- Compare the export against the editable source to catch font substitution, line-weight changes, clipping, transparency problems, or color shifts.

## Prohibited style patterns

Do not use these unless the user explicitly requests them:

- Heavy or multi-stop gradients.
- 3D perspective, isometric blocks, extruded text, bevels, or faux depth.
- Glow, neon edges, lens flare, glassmorphism, strong drop shadows, or floating cards.
- Oversized decorative icons, generic AI brains, robot imagery, circuit motifs, or abstract swooshes.
- Dense dark backgrounds, cinematic poster lighting, excessive saturated colors, or rainbow category palettes.
- Decorative scientific imagery that implies unsupported mechanisms or results.
- Layouts that resemble a marketing poster more than a scientific figure.

## Scientific-content safeguards

- Preserve terminology, capitalization, gene/protein formatting, abbreviations, symbols, equations, units, and sample identifiers exactly unless the user asks for editing.
- Verify that every stage has the intended inputs and outputs and that branches recombine correctly.
- Do not invent missing methods, metrics, datasets, statistical outcomes, or biological relations. Mark unresolved content as a placeholder or ask when it changes the scientific meaning.
- Keep ontology, taxonomy, controlled vocabulary, and hierarchy relations distinct from statistical similarity or model prediction.
- Show uncertainty, manual review, exceptions, or optional paths when they materially affect interpretation.
- If simplifying a reference figure, preserve its meaning and tell the user about any material omission.

## Pre-delivery checklist

Do not deliver until all applicable checks pass:

- The figure has one obvious reading order and a clear top-level message.
- Scientific entities, labels, values, units, and arrow meanings match the supplied content.
- No text, icon, line, chart, or table is clipped, cropped, or outside the canvas.
- No text overflows its box; no word is broken awkwardly; all symbols and CJK glyphs render correctly.
- The smallest text is readable at final viewing or print size.
- Repeated boxes, gaps, strokes, corner radii, and arrows are consistent.
- Connectors do not cross labels or pass through nodes.
- Blue/teal accents encode meaning consistently and the figure remains understandable in grayscale.
- Titles, body text, and fills have sufficient contrast.
- The source remains editable; the primary figure is not flattened when editability was requested.
- PPT objects are grouped logically and SVG/PDF bounds are correct.
- A rendered/exported preview has been visually inspected at normal size and thumbnail size.
- File names, slide/page dimensions, requested language, and output formats match the user's request.

## Completion report

When delivering a figure, state the editable source format and path, any preview/export paths, the template used, and any scientific-content assumptions or unresolved placeholders. Mention unavoidable raster elements or font substitutions. Keep the report brief unless the user asks for design rationale.
