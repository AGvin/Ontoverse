# History-Space Density Regions

Status: draft

![History-space density regions](../../assets/default/diagrams/history-space-density-regions.svg)

This diagram shows how **temporal density** may vary across different regions of history-space.

## Translations

- English
- [Українська](./l10n/uk_UA/)

## What the Diagram Shows

The diagram separates history-space into three conceptual density regions:

- **low temporal density region** — sparse significant event-nodes across frontal-time intervals;
- **medium temporal density region** — a moderate frequency of significant event-nodes;
- **high temporal density region** — frequent significant event-nodes and closely spaced transitions.

All visible trajectories terminate at the ruby current frontal-time frontier `S(F_max)`.

## Global-Slice Interpretation

A frontal-time value represents a global history-space slice `S(F)`.

The same slice may therefore intersect many branches or regions whose local histories have accumulated very different numbers of significant event-nodes.

Conceptually:

```text
same global ΔF
-> sparse region: fewer significant transitions
-> dense region: more significant transitions
```

This is the current meaning of non-uniform temporal density in the diagram.

A branch does not need to contain a significant event-node at every sampled frontal-time slice.

## Interpretation

Ontoverse treats temporal density as a branch- or region-local property, not as a uniform value across the entire history-space.

The same global frontal-time progression can therefore coexist with different amounts of branch-local time accumulation.

Temporal density is distinct from causal processing density. This visualization encodes **frequency of significant event-nodes**, not speculative processing load.

## Current Frontier

No event-nodes are shown beyond the frontal time plane because the ruby plane represents `S(F_max)` in this visualization.

Content beyond it would represent later structure that the current model state does not show as actualized.

## Documentation Role

Use this visualization when explaining:

- global frontal-time slices;
- non-uniform temporal density;
- regions of different significant-transition frequency;
- the difference between frontal time and locally accumulated time;
- history-space as a structured field rather than a single branch.
