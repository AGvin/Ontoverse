# Temporal Density Comparison

Status: draft

![Temporal density comparison](../../assets/default/diagrams/temporal-density-comparison.svg)

This diagram explains the Ontoverse concept of **temporal density** by comparing two historical trajectories across the same **frontal-time interval**.

## Translations

- English
- [Українська](./l10n/uk_UA/)

## What the Diagram Shows

Both trajectories are compared over the same interval of global frontal-time ordering and terminate at the same current frontal-time frontier `S(F_max)`.

The upper trajectory has **low temporal density**:

- fewer significant event-nodes over the shared interval;
- longer gaps between significant transitions;
- more of the frontal-time interval without a represented significant node.

The lower trajectory has **high temporal density**:

- more significant event-nodes over the same interval;
- shorter gaps between significant transitions;
- more local-time accumulation under the current Ontoverse hypothesis.

## Slice Interpretation

The Frontal Time Model now treats a frontal-time value as a global history-space slice `S(F)`.

The diagram can therefore be read conceptually as sampling the same progression of global slices for two different branches:

```text
sampled slices:       F0  F1  F2  F3  F4  F5
low-density branch:   *   .   .   *   .   *
high-density branch:  *   *   *   *   *   *
```

The diagram does not claim that frontal time is fundamentally discrete. The sampled-slice representation is only a way to visualize different frequencies of significant transition across the same `ΔF`.

## Interpretation

In Ontoverse, local time is not treated only as an external coordinate. It is associated with the accumulation of significant event-nodes along a trajectory as frontal time progresses globally.

The conceptual expression is:

```text
temporal density ~ event-nodes / frontal-time interval
```

This is not yet a physical equation. It is a visual and conceptual definition that requires future formalization.

Temporal density should not be confused with **causal processing density**, which is a separate speculative concept for local state-coordination or processing load.

## Current Frontier

The trajectories stop at the right ruby plane because it represents the current maximal frontal-time slice `S(F_max)` in this visualization.

Nodes and realized paths beyond that plane would imply later realized structure that is not part of the shown model state.

This is the **current-frontier** use of the frontal time plane, unlike the retrospective reference-slice mode used by the Closed Time Loop visualization.

## Documentation Role

Use this visualization when explaining:

- global frontal-time slices;
- local time;
- temporal density;
- branch-specific event-node frequency;
- event-node accumulation;
- why different histories may accumulate different amounts of local time across the same frontal-time interval.
