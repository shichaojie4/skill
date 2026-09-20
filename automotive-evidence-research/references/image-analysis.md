# Engineering Image Analysis

## Classify first

Identify the image as photograph, teardown, cutaway, exploded view, CAD render, patent figure, mechanism diagram, electrical/hydraulic/control schematic, chart, table, production-line image, concept render, or generated illustration.

## Inspect photographs

Analyze visible components, interfaces, fasteners, bearings, seals, gears, housings, connectors, wiring, cooling, sensors, mounting points, packaging, materials, manufacturing clues, service access, and likely assembly sequence.

Trace plausible load, torque, heat, fluid, and signal paths. Cross-check with other views, manuals, patents, and product generations.

## Use explicit observation labels

- **Visible:** directly supported by pixels or legible labels.
- **Inferred:** engineering interpretation supported by visible cues and external evidence.
- **Uncertain:** occluded, low-resolution, perspective-distorted, or version-ambiguous.
- **Not determinable:** the image cannot support the claim.

Do not estimate precise dimensions without scale calibration. Do not infer hidden geometry from superficial resemblance.

## Inspect schematics and charts

Read labels, legends, axes, units, arrows, states, and boundary conditions. Map inputs, actuation, plant, sensing, feedback, and outputs. Verify that figure meaning agrees with nearby text. Flag inconsistent arrows, impossible connections, missing return paths, unlabeled axes, or visually implied precision unsupported by data.

