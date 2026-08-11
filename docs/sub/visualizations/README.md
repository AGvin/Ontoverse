# Ontoverse Visualizations

Status: draft

This section contains visual explanations of the Ontoverse conceptual framework.

The diagrams are part of the documentation, not decorative assets. They should remain synchronized with the terminology used in the framework, models, and glossary.

## Visualization Set

- [`temporal-density-comparison/`](./sub/temporal-density-comparison/) — compares low and high temporal density across the same frontal-time interval.
- [`convergent-channel/`](./sub/convergent-channel/) — shows distinct historical origins narrowing into a compatibility channel and convergent channel at the current frontal-time frontier.
- [`history-space-density-regions/`](./sub/history-space-density-regions/) — shows sparse, medium, and high temporal-density regions inside history-space.
- [`uneven-temporal-density/`](./sub/uneven-temporal-density/) — compares several representative density patterns across history-space.
- [`isometric-history-space/`](./sub/isometric-history-space/) — shows a volumetric, tree-like history-space projection with branching strings approaching the current frontal-time frontier.
- [`closed-time-loop/`](./sub/closed-time-loop/) — shows past-directed travel as a globally self-consistent oval loop relative to a retrospective frontal-time reference slice, without the time-travel event itself creating a branch.

## Shared Visual Rules

### Frontal-time plane modes

The ruby **frontal time plane** represents a frontal-time slice `S(F)`.

A visualization must make clear which of two roles the visible plane is using.

**Current frontier — `S(F_max)`**

The plane represents the latest actualized global slice in the shown model state.

```text
realized history -> S(F_max)
```

In this mode:

- realized event-nodes, trajectories, and channels normally terminate at the plane;
- content beyond it must be explicitly marked as hypothetical, potential, inaccessible, or otherwise not-yet-realized;
- the plane should visually read as the present frontier of the diagram.

**Retrospective reference slice — `S(F_ref)`**

The plane represents an earlier selected global slice inside a larger already-described causal structure.

```text
already-described history
------ S(F_ref) ------
continues within the same retrospective view
```

In this mode:

- already-described realized structure may appear on both sides of the plane;
- crossing the plane does not mean crossing beyond the current `F_max` frontier;
- the diagram must explicitly identify the plane as a reference slice rather than the current frontier.

The Closed Time Loop visualization uses this second mode.

### Density must be visually encoded

When a diagram explains temporal density, the density difference must be visible through event-node frequency or spacing over the same frontal-time interval:

- sparse regions use fewer significant nodes and longer gaps;
- dense regions use more significant nodes and shorter gaps;
- burst regions use local clusters of nodes;
- mixed regions combine sparse and dense areas.

A branch does not need to show a significant event-node at every sampled frontal-time slice.

### Temporal and processing density are distinct

Do not use **temporal density** as a synonym for **causal processing density**.

- temporal density = frequency of significant event-nodes per frontal-time interval;
- causal processing density = speculative local state-coordination or processing load relative to frontal-time slices.

If a gravity-related diagram uses causal processing density, its labels and captions must not imply that more temporal event-nodes directly mean slower local time.

### Images are versioned documentation

If terminology, formulas, node names, model structure, or captions change, update the related diagram and its documentation together.

## Approved Visual Language

Ontoverse visualizations use:

- dark navy or black backgrounds;
- cyan, blue, violet, magenta, and white trajectories;
- ruby-red frontal time axes or planes;
- glowing event-nodes;
- dotted potential branches;
- concise scientific labels.
