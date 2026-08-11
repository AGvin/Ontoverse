# Ontoverse Visualizations

Status: draft

This section contains visual explanations of the Ontoverse conceptual framework.

The diagrams are versioned documentation and must remain synchronized with the framework, models, glossary, and one another.

## Translations

- English
- [Українська](./l10n/uk_UA/)

## Visualization Set

- [`isometric-history-space/`](./sub/isometric-history-space/) — shows the current **history bundle** as a volumetric set of represented historical strands, with compressed shared classes and explicit class splitting at first required distinctions.
- [`temporal-density-comparison/`](./sub/temporal-density-comparison/) — compares low and high temporal density across the same frontal-time interval.
- [`history-space-density-regions/`](./sub/history-space-density-regions/) — shows sparse, medium, high, and burst temporal-density patterns across represented strands.
- [`uneven-temporal-density/`](./sub/uneven-temporal-density/) — compares several representative significant-transition patterns across history-space.
- [`convergent-channel/`](./sub/convergent-channel/) — shows globally distinct historical strands becoming locally equivalent in a shared compatibility channel without erasing their distinct pasts.
- [`closed-time-loop/`](./sub/closed-time-loop/) — shows a loop-compatible history-class split at reintegration and a later departure closing the same isolated past-directed loop.

## Shared Visual Rules

### Historical strands represent current classes

A visible ordinary history line should normally be read as a **Historical Strand**: the representation of one currently distinguishable History Equivalence Class.

Do not imply that every dotted possibility must already be a fully instantiated independent timeline from the earliest visible state.

A visualization may show several admissible continuations inside one compressed history class until a current state distinction requires explicit separation.

```text
one represented strand
-> still-equivalent admissible continuations
-> divergence only at first required state distinction
```

### Divergence means first required distinction

A **Divergence Node** should mark the earliest significant location where one previously represented class needs incompatible current state descriptions.

Do not use a divergence symbol merely because a causal path leaves an ordinary strand geometrically.

For example, a Closed Time Loop departure is not a divergence node. The loop-compatible and loop-free histories may instead split at reintegration if that is where their states first differ.

### Potential branches are compressed possibilities

A dotted **Potential Branch** represents an admissible continuation that is not yet shown as a separately realized historical strand in the current visual slice.

Potential branches may therefore visually emerge from a represented class before a later explicit divergence is shown, but captions must distinguish:

- admissible continuation structure;
- currently distinguishable historical strands;
- realized or actualized current state.

### Frontal-time plane modes

The ruby **Frontal Time Plane** represents a frontal-time slice `S(F)` across the history bundle.

A visualization must make clear which of two roles the visible plane uses.

**Current frontier — `S(F_max)`**

The plane represents the latest actualized global slice in the shown model state.

```text
represented history bundle -> S(F_max)
```

In this mode:

- realized historical strands normally terminate at the plane;
- future-side content must be explicitly marked as hypothetical, potential, inaccessible, or otherwise not-yet-actualized;
- the plane should visually read as a global cross-section of all shown strands, not as a timestamp belonging to one line.

**Retrospective reference slice — `S(F_ref)`**

The plane represents an earlier selected global slice inside already described history.

```text
already-described causal structure
------ S(F_ref) ------
continues within the same retrospective view
```

In this mode:

- already-described realized structure may appear on both sides of the plane;
- crossing the plane does not mean crossing beyond the current `F_max` frontier;
- the owning page must identify the plane as a reference slice.

### Temporal density must be visually encoded

When a diagram explains temporal density, the difference must be visible through significant event-node frequency or spacing over the same frontal-time interval:

- sparse: fewer significant nodes and longer gaps;
- dense: more significant nodes and shorter gaps;
- burst: a local cluster of significant nodes;
- mixed: non-uniform combinations.

A historical strand does not need a significant event-node at every sampled frontal-time slice.

### Temporal density and causal processing density are distinct

Do not use **Temporal Density** as a synonym for **Causal Processing Density**.

```text
temporal density
= significant event-node frequency / frontal-time interval

causal processing density
= speculative local state-coordination or processing load
```

Gravity-related diagrams must not imply that simply drawing more temporal event-nodes means slower local time.

### Convergence does not erase historical multiplicity

When several strands visually approach or share one compatibility channel, the diagram must not imply that their complete histories have been deleted or made globally identical.

Preferred reading:

```text
globally distinct strands
-> locally equivalent accessible states
-> shared compatibility channel
```

### Closed-loop geometry is not an ordinary branch

The isolated past-directed transit in a Closed Time Loop is not an ordinary forward historical strand.

If a loop visualization also shows a history-class split, the split should occur at the first required state distinction — normally reintegration in the minimal case — while the future departure is shown as loop closure rather than branch creation.

### Images are versioned documentation

If terminology, formulas, node meanings, model structure, or captions change, update the related diagram and its documentation together.

## Approved Visual Language

Ontoverse visualizations use:

- dark navy or black backgrounds;
- cyan, blue, violet, magenta, white, and occasional gold trajectories;
- ruby-red frontal-time axes or planes;
- glowing event-nodes;
- dotted potential continuations when useful;
- clean technical labels;
- clear visual distinction between ordinary historical strands, potential continuations, compatibility channels, and isolated causal-transit paths.
