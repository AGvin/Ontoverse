# History-Space Density Regions

Status: draft

![History-space density regions](../../assets/default/diagrams/history-space-density-regions.svg)

This diagram shows how **temporal density** may vary across Historical Strands and regions of the Ontoverse history bundle.

## Translations

- English
- [Українська](./l10n/uk_UA/)

## What the Diagram Shows

The diagram compares representative strands with different significant-transition frequencies:

- **low temporal density** — sparse significant event-nodes across frontal-time intervals;
- **medium temporal density** — a moderate frequency of significant event-nodes;
- **high temporal density** — frequent significant event-nodes and closely spaced transitions;
- **burst density** — a local concentration of significant transitions.

All visible strands terminate at the ruby current frontal-time frontier `S(F_max)`.

## History-Bundle Interpretation

A frontal-time value represents a global history-bundle slice `S(F)`.

The same slice can therefore intersect many currently distinguishable strands whose local histories have accumulated different numbers of significant event-nodes.

```text
same global ΔF
-> sparse strand: fewer significant transitions
-> dense strand: more significant transitions
```

A strand does not need to contain a significant event-node at every sampled frontal-time slice.

If several admissible complete histories remain state-equivalent, they may still be represented by one Historical Strand and therefore share one density description until a required class split.

## Interpretation

Ontoverse treats temporal density as a strand- or region-local property, not a uniform property of the whole history bundle.

The same global frontal-time progression can coexist with different amounts of local-time accumulation.

Temporal density is distinct from Causal Processing Density. This visualization encodes **frequency of significant event-nodes**, not speculative processing load.

## Current Frontier

No event-nodes are shown beyond the frontal-time plane because it represents `S(F_max)` in this visualization.

## Documentation Role

Use this visualization when explaining:

- the history bundle;
- global frontal-time slices;
- non-uniform temporal density;
- strand-specific significant-transition frequency;
- the difference between frontal time and locally accumulated time.
