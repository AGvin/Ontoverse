# Uneven Temporal Density Across History-Space

Status: draft

![Uneven temporal density across history-space](../../assets/default/diagrams/uneven-temporal-density.svg)

This diagram compares several representative temporal-density patterns inside Ontoverse history-space.

## Translations

- English
- [Українська](./l10n/uk_UA/)

## What the Diagram Shows

Each row represents a different pattern of significant event-node frequency before the same ruby current frontal-time frontier `S(F_max)`.

Patterns shown:

- **Sparse** — only a few significant event-nodes across the interval.
- **Sparse to dense** — significant event-nodes become more frequent as frontal time progresses.
- **Dense to sparse** — significant event-nodes are initially frequent and later become more widely spaced.
- **Burst cluster** — significant event-nodes are concentrated in a local interval.
- **Uniform medium** — significant event-nodes occur at a relatively even medium frequency.

## Global-Slice Interpretation

The rows can be read as different branch-local responses across the same sequence of global frontal-time slices.

```text
shared progression: S(F0) -> S(F1) -> ... -> S(F_max)
branch A:           fewer significant transitions
branch B:           more significant transitions
branch C:           transitions concentrated in a burst
```

The visual spacing is a conceptual encoding of **temporal density**, not proof that frontal time itself is discrete.

## Interpretation

The purpose of this diagram is to show that temporal density does not have to be uniform across history-space.

Different trajectories can accumulate different amounts of local time while sharing the same global frontal-time progression.

Temporal density here means significant event-node frequency per frontal-time interval. It is distinct from causal processing density.

## Current Frontier

Every trajectory ends at the frontal time plane because the plane represents `S(F_max)` in this visualization.

The diagram intentionally avoids showing realized branches or event-nodes beyond the current maximal slice.

## Documentation Role

Use this visualization when explaining:

- global frontal-time slices;
- uneven temporal density;
- local time accumulation;
- sparse, dense, and clustered event-node patterns;
- why history-space should be treated as non-uniform rather than evenly gridded.
