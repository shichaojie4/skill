# Engineering Diagram Validation

## Build the semantic specification

Before drawing, list components and counts, topology, ports/interfaces, flows and directions, degrees of freedom, constraints, states, labels/units, source-backed facts, inferences, and unknowns. Draw only what the specification permits.

## Mechanical gate

Verify joints and constraints, load/torque path closure, relative motion, section relationships, assembly feasibility, non-interference, front/rear and left/right orientation, and consistency of all repeated components.

## Electrical gate

Verify source, ground, load, switching topology, return paths, isolation, power versus signal lines, voltage/current direction, and impossible short/open states. For H-bridges and PWM drives, show only valid conduction and control relationships.

## Hydraulic and MR gate

Verify pressure chambers, restrictions, valves, flow continuity, return paths, piston/rotor motion, field-active gaps, magnetic path intent, and state-to-force/torque relationship.

## Control gate

Verify sensing, estimation, control, arbitration, drive, plant, feedback, commands, states, outputs, sampling boundaries, safety fallback, and module responsibility. Do not mix requested, estimated, measured, and controlled quantities.

## Data gate

Use traceable data only. Verify axes, units, scales, legends, operating conditions, interpolation, and any normalization. Do not fabricate a plausible curve.

## Release gate

Reject the drawing if any topology, direction, count, label, unit, boundary, or physical principle conflicts with the semantic specification or sources. Mark uncertain elements visually and in the caption.

