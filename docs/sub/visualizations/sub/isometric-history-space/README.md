# Isometric History-Space

Status: draft

![Isometric history-space diagram](../../assets/default/diagrams/isometric-history-space.svg)

This visualization presents history-space as a volumetric structure rather than a flat timeline.

The diagram uses an isometric projection to show several tree-like realized strings moving through the same history-space volume toward the ruby **current frontal-time frontier**.

## Translations

- English
- [Українська](./l10n/uk_UA/)

## Conceptual Reading

- **History-space volume**: the shown box represents a local conceptual region of possible or realized historical structure.
- **Tree-like strings**: colored strings represent historical branches that can split into incompatible child continuations.
- **Event-nodes**: circles mark significant event-nodes. A branch need not contain a significant node at every sampled frontal-time slice.
- **Frontal time plane**: the ruby plane on the right represents the current maximal global slice `S(F_max)` in this visualization.
- **No realized future-side continuation**: realized branches terminate at or before `S(F_max)`.

## Relation to Global Frontal-Time Slices

The plane should be understood as one global cross-section of the volumetric history-space rather than as a timestamp belonging to one branch.

Conceptually:

```text
many branch-local states
-> intersect one shared global slice S(F)
```

The shown rightmost plane is specifically the current frontier `S(F_max)`. Earlier slices are not individually drawn, but each visible historical string can be understood as passing through a progression of such slices before reaching the current frontier.

Different strings may accumulate significant event-nodes at different frequencies across that common progression. This is the volumetric counterpart of non-uniform temporal density.

## Why Isometric Projection

Earlier flat diagrams are useful for comparing density patterns, but they do not clearly show that Ontoverse history-space is intended as a volumetric conceptual structure.

The isometric view makes the following ideas easier to see:

- branches can separate in more than one visual dimension;
- different regions can have different event-node density;
- multiple tree-like structures can approach the same global frontal-time slice;
- compatibility with the frontal boundary does not require all histories to be visually flattened into one line.
