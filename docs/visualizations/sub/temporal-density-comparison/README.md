# Temporal Density Comparison

Status: draft

![Temporal density comparison](../../assets/diagrams/temporal-density-comparison.svg)

This diagram explains the Ontoverse concept of **temporal density** by comparing two historical trajectories across the same **frontal-time interval**.

## What the Diagram Shows

Both trajectories are bounded by the same two ruby frontal-time planes. This means they are evaluated across the same frontal-time interval.

The upper trajectory has **low temporal density**:

- fewer event-nodes;
- longer gaps between significant transitions;
- fewer local branch opportunities.

The lower trajectory has **high temporal density**:

- more event-nodes;
- shorter gaps between significant transitions;
- more local branch opportunities.

## Interpretation

In Ontoverse, local time is not treated only as an external coordinate. It is associated with the accumulation of significant event-nodes along a trajectory.

The conceptual expression is:

```text
temporal density ~ event-nodes / frontal-time interval
```

This is not yet a physical equation. It is a visual and conceptual definition that requires future formalization.

## No Future-Side Content

The trajectories stop at the right frontal-time plane.

This is intentional: the plane represents the current present boundary in the diagram. Nodes and realized paths beyond that plane would imply future events that have not occurred inside the shown model slice.

## Documentation Role

Use this visualization when explaining:

- frontal time;
- local time;
- temporal density;
- event-node accumulation;
- why different histories may experience different amounts of change across the same frontal-time interval.
