---
name: automotive-evidence-research
description: Evidence-led research for automotive, vehicle dynamics, chassis, braking, electrified powertrain, mechatronics, robotics, and Physical AI. Use for technical scans, product or supplier investigations, competitor comparisons, patent and paper research, quantitative claim verification, automotive document review, engineering analysis of product photos or diagrams, selection and citation of public images, and technically accurate redrawing of mechanisms, circuits, hydraulic systems, control architectures, data charts, or vehicle layouts. Supports Chinese, English, and German cross-language retrieval and distinguishes confirmed facts, high-confidence inferences, and unknowns.
---

# Automotive Evidence Research

Produce compact, traceable engineering research. Optimize for factual accuracy, independent corroboration, image understanding, and explicit uncertainty rather than volume of results or generic advice.

## Select the mode

- **Quick verification:** Resolve one narrow fact with 2–5 strong sources.
- **Topic scan:** Map facts, products, competitors, metrics, and evidence gaps.
- **Deep research:** Run multi-pass retrieval, source-independence checks, conflict analysis, visual evidence review, and a claim-evidence matrix.

If the user does not specify a mode, choose the smallest mode that can answer reliably.

## Execute the workflow

1. Convert the request into atomic questions. Define product/version, geography, date, operating condition, metric, and intended evidence threshold.
2. Expand queries across Chinese, English, and German where useful. Include abbreviations, prior names, supplier terminology, and patent language.
3. Route searches toward the strongest likely source types. Read [source-routing.md](references/source-routing.md).
4. Capture atomic claims with source, date, context, and evidence state. Apply [evidence-rules.md](references/evidence-rules.md).
5. For vehicle or component conclusions, apply [automotive-checks.md](references/automotive-checks.md).
6. Inspect relevant photographs and diagrams, not only surrounding text. Read [image-analysis.md](references/image-analysis.md).
7. Cross-check critical claims with independent sources. Trace syndicated reports back to their common origin.
8. Normalize units and preserve test conditions. Do not average conflicting values merely to remove disagreement.
9. Stop when the evidence threshold is met or when further searching only repeats the same source chain. State unresolved gaps.
10. Present findings using the applicable schema in [output-schemas.md](references/output-schemas.md).

## Handle images in research and reports

- Prefer official product images, technical manuals, patents, papers, regulatory material, and reputable teardown sources.
- Distinguish photographs, renders, concepts, prototypes, production parts, and redrawn diagrams.
- Separate what is directly visible from engineering inference and unknown structure.
- Record provenance before inserting an image into a report. Read [image-citation.md](references/image-citation.md).
- Treat public visibility and reuse permission as different questions. Flag uncertain reuse rights.
- Never remove watermarks or present generated imagery as factual product evidence.

## Redraw technical figures safely

1. Write a semantic specification before drawing: components, counts, topology, interfaces, directions, constraints, known facts, inferences, and unknowns.
2. Prefer deterministic vector or code-native methods for precise diagrams and charts. Use generative imagery only for clearly labeled conceptual or photorealistic illustration.
3. Validate engineering logic with [diagram-validation.md](references/diagram-validation.md).
4. Render and inspect the final-size figure against [visual-standard.md](references/visual-standard.md).
5. Reject the figure if it contains a principle error, unsupported internal structure, unreadable labels, overlaps, clipping, malformed geometry, or misleading data.
6. Preserve editable source when practical and label redraws or adaptations in the caption.

## Maintain hard boundaries

- Do not treat a patent filing as proof of production use.
- Do not treat a supplier claim as independent validation.
- Do not infer precise dimensions from an image without a valid scale reference.
- Do not convert absence of public evidence into evidence of absence.
- Do not upload or expose confidential material. Process internal documents locally unless the user explicitly authorizes another path.
- Keep report layout and file-format production in the appropriate document, presentation, spreadsheet, or PDF skill; provide those skills with verified claims, image assets, captions, and provenance.
