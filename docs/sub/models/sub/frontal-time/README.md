# Frontal Time Model

Status: draft

The Frontal Time Model introduces a distinction between a global ordering parameter and locally experienced time.

![Temporal density comparison](../../../visualizations/assets/default/diagrams/temporal-density-comparison.svg)

## Frontal Time

Frontal time is a proposed global ordering parameter `F` for the unfolding of history-space.

The current Ontoverse interpretation is stronger than a single moving timestamp. A frontal-time value corresponds to a **global cross-section of history-space**: a snapshot of branch states that are simultaneously admissible at the same global ordering value.

Ontoverse calls this a **frontal-time slice** and writes it conceptually as `S(F)`.

```text
frontal-time value F
-> global slice S(F)
-> current branch states across history-space at F
```

In the strongest current interpretation, `S(F)` contains all branch states that are simultaneously admissible at that ordering value. Ontoverse does not yet formally distinguish whether every admissible branch state should be called physically realized, possible, or actualized in some more precise sense. That ontological distinction remains an open problem.

The phrase **all at once** therefore means all branch-local states across one shared frontal-time slice. It does not mean that an ordinary local observer experiences all branches or all frontal-time values simultaneously.

The current maximum `F_max` is the greatest frontal-time value for which the model treats a global slice as actualized. States at larger frontal-time values are not yet ordinary realized history, although the structure of admissible continuations may constrain which present states can belong to globally self-consistent histories.

Frontal time may be visualized as a wavefront or plane moving through history-space. The image is metaphorical: frontal time is not yet defined as a physical field, metric, foliation, or measurable quantity.

## Frontal-Time Slices and the Unfolding of Time

The progression of frontal-time slices provides a possible Ontoverse interpretation of how realized time is created or unfolded.

Conceptually:

```text
S(F0)
-> S(F1)
-> S(F2)
-> S(F3)
-> ...
```

Each slice is a new global snapshot of the history-space state at a later frontal-time value.

The labels `F0`, `F1`, and so on are sampled conceptual labels. They do not currently imply that frontal time is fundamentally discrete. A future formalization may instead use a continuous parameter and infinitesimal or finite intervals `dF` and `ΔF`.

A branch does not need to create a significant event-node at every sampled slice. Its state may persist or evolve below the threshold currently used to identify an event-node.

This gives the model a basic separation:

```text
frontal-time progression
= progression of global history-space slices

local-time accumulation
= accumulation of significant branch-local transitions across those slices
```

## Global Consistency and Admissible Continuations

A purely local rule of the form `previous event-node -> next event-node` is not sufficient for every Ontoverse model.

The stronger working interpretation is that a frontal-time slice must belong to at least one globally self-consistent continuation of the current history-space state.

Conceptually:

```text
current slice S(F)
+ current causal structure
+ admissible continuation space
+ global consistency constraints
-> later admissible slice or slices
```

The continuation space is not treated as already realized ordinary future history. It represents the possible complete continuations against which the consistency of a current branch state can be evaluated.

This makes frontal-time actualization an **all-state consistency problem** rather than a reaction to one isolated trigger node.

Several mutually incompatible continuations may remain self-consistent. In that case the model can retain them as different history-space branches. Global consistency therefore does not by itself imply one deterministic future.

This structure is conceptually similar to an all-at-once or boundary-consistency view, but Ontoverse has not yet defined the mathematical rule that would perform such filtering.

See [`closed-time-loop`](../closed-time-loop/) for the case where a later departure and an earlier reintegration belong to the same globally self-consistent history.

## Observer Access Across a Global Slice

A global frontal-time slice may contain states from many mutually incompatible histories.

An observer does not experience that complete slice directly. The observer has access only to the branch-local states, records, and interactions compatible with the observer's own historical trajectory.

```text
global S(F)
= many branch-local states at the same F

local observer
= access to one compatible historical trajectory through those slices
```

This preserves the distinction between a global ordering structure and locally experienced history.

## Local Time

Local time is the time experienced along a particular historical trajectory.

The working intuition is that experienced time corresponds not merely to an external coordinate, but to the accumulation of significant physical transitions as successive frontal-time slices are crossed.

In informal terms:

```text
local time ~ accumulated significant event-nodes
```

## Temporal Density

Temporal density is the proposed number of significant event-nodes per unit of frontal time.

Under the slice interpretation, temporal density can also be read as the **branch-specific frequency of significant transitions across a shared frontal-time interval**.

For example:

```text
sampled frontal-time slices: F0  F1  F2  F3  F4  F5  F6
high-density branch:         *   *   *   *   *   *   *
low-density branch:          *   .   .   *   .   .   *

* = significant event-node
. = no significant event-node at that sampled slice
```

Both branches are ordered by the same frontal-time progression. The high-density branch accumulates significant transitions more frequently, while the low-density branch remains locally stable across more of the same frontal-time interval.

The conceptual expression remains:

```text
temporal density ~ event-nodes / frontal-time interval
```

Under the current local-time hypothesis, higher temporal density means more accumulated local time over the same `ΔF`, while lower temporal density means less accumulated local time over that interval.

This is a conceptual expression, not a defined physical equation.

Temporal density may be uneven across history-space. Some regions or trajectories may be sparse, others dense, and others mixed or clustered.

See also:

- [`temporal-density-comparison`](../../../visualizations/sub/temporal-density-comparison/);
- [`history-space-density-regions`](../../../visualizations/sub/history-space-density-regions/);
- [`uneven-temporal-density`](../../../visualizations/sub/uneven-temporal-density/).

## Temporal Density vs Causal Processing Density

**Temporal density** and **causal processing density** are not the same quantity.

Temporal density describes the realized frequency of significant event-nodes along a branch relative to frontal time.

Causal processing density is a separate speculative concept for the amount of local state coordination, constraint, interaction bookkeeping, or physical processing load that must be maintained in a region relative to the global frontal-time ordering.

The current gravity interpretation may therefore be expressed cautiously as:

```text
higher causal processing load per frontal-time slice
-> lower effective rate of significant branch-local transitions
-> lower temporal density
-> slower local-time accumulation relative to F
```

This relation is speculative. It is introduced to keep the gravity interpretation logically distinct from the definition of temporal density; it is not a derived physical law.

## Quantum Transition Rate Conjecture

Status: conjecture

The quantum transition rate conjecture refines the earlier Planck-action wording.

The established physics background is that Planck's constant has the dimensions of action, and since the 2019 SI revision its numerical value is fixed exactly as:

```text
h = 6.62607015 x 10^-34 J s
```

Planck's constant, or the reduced Planck constant `hbar`, is not treated here as a direct measure of temporal density. It is better understood as part of the quantum scale that relates action, energy, frequency, phase, and quantum-state evolution.

The Ontoverse conjecture is different:

```text
The density of significant event-nodes along a branch may depend on an effective quantum transition rate relative to frontal time.
```

In this model, the primary candidate quantity is not `h` by itself, but an effective transition-rate parameter:

```text
Gamma_eff = effective rate of significant quantum transitions per unit of frontal time
```

This parameter is conceptual. It is not currently a measured physical constant or a defined equation.

A possible physical inspiration is that quantum-state evolution is controlled by the relation between the system's effective Hamiltonian scale and `hbar`:

```text
quantum-state evolution rate ~ H_eff / hbar_eff
```

For transition-like event-nodes, the effective rate may also depend on interaction strength, coupling between states, density of available final states, decoherence-related processes, and other branch-specific physical structure.

In Ontoverse terms:

```text
frontal time = shared ordering of global slices
Gamma_eff = effective significant-transition rate
Gamma_eff -> event-node frequency across slices
event-node frequency -> temporal density
temporal density -> local-time accumulation
```

Under this conjecture, if two branches share the same frontal-time interval but differ in their effective quantum transition rate, they may accumulate different numbers of significant event-nodes.

A branch with higher `Gamma_eff` would contain more significant event-nodes per frontal-time interval and therefore higher temporal density. A branch with lower `Gamma_eff` would contain fewer significant event-nodes per frontal-time interval and therefore lower temporal density.

This gives a conceptual route for interpreting why local time may progress faster in one branch and slower in another while frontal time remains the shared global ordering parameter.

## Branch Metrics and Local Metric Deviations

Status: working definition

The model may distinguish between an absolute baseline metric, a branch baseline metric, and local metric deviations.

### Related Visualizations

The visual explanation is split into smaller SVG diagrams so each image has one primary concept:

![Branch baseline versus local metric deviation](./assets/svg/branch-baseline-vs-local-deviation.svg)

![Mass, time-rate gradient, and gravity](./assets/svg/mass-gravity-time-rate.svg)

![Gravity well interpretation](./assets/svg/gravity-well-interpretation.svg)

![Gravitational wave interpretation](./assets/svg/gravitational-wave-interpretation.svg)

The absolute baseline metric is a shared conceptual zero-point. It represents an abstract reference state with no mass, no gravitational distortion, and no meaningful causal processing density. It is not treated as a living timeline state, because without mass, energy, or state changes, there are no events to actualize.

The branch baseline metric represents the average nominal state of a specific timeline branch. It includes the branch's average mass-energy distribution, average gravitational background, average causal processing density, and default branch time rate.

In this sense, the branch baseline metric defines the temporal character of a branch:

```text
branch baseline metric
-> average causal processing density
-> effective branch transition rate
-> default temporal density
-> default branch time rate
```

Local gravitational effects are then modeled as deviations from the branch baseline metric, not from absolute zero. A planet, star, black hole, dense matter region, low-density region, or gravitational wave may be interpreted as a local metric deviation within the branch.

## Causal Processing Density and Gravity

Status: interpretive hypothesis

Causal processing density is a proposed Ontoverse term for the amount of local state coordination, interaction bookkeeping, constraint, and physical processing load that must be maintained in a region relative to frontal-time slices.

It is intentionally distinct from temporal density, which counts significant event-nodes per frontal-time interval.

In established general relativity, gravity is described through spacetime geometry shaped by mass and energy, not as an ordinary pulling force. The common gravity-well image is therefore only a simplified visualization. The "well" does not represent a literal surface; it represents a change in spacetime geometry and local time rate.

Within the Ontoverse interpretation, mass-energy concentration may be treated as a marker of increased local state-coordination load. The current conjectural bridge is that greater load may reduce the effective rate at which significant branch-local transitions accumulate relative to the same frontal-time progression.

```text
mass-energy concentration
-> causal processing density increase
-> effective significant-transition rate decreases
-> temporal density decreases
-> local time-rate slowdown
-> local time-rate gradient
-> curved possible trajectories
-> gravitational effect
```

The middle steps are speculative model components, not established physics.

In this interpretation, the depth of a gravity-well visualization represents the amount of local time-rate slowdown, while the slope of the well represents the gradient that changes trajectories. Objects do not fall because space is literally pulled downward; they follow paths shaped by uneven local time rates and causal processing density.

Gravitational waves can be described as traveling fluctuations of this structure. They are not permanent hills that push objects like water waves push a surfboard. Instead, they temporarily stretch and compress spatial relations, creating oscillating changes in causal processing density and local time-rate gradients.

```text
gravitational wave
-> moving local metric deviation
-> spatial stretch/compression
-> causal processing density fluctuation
-> effective transition-rate fluctuation
-> local time-rate gradient fluctuation
-> transient trajectory distortion
```

This remains an interpretive model component, not a derived physical theory.

## Relation to the Quantum of Action

The physical concept of a quantum of action is established physics. The speculative Ontoverse component is the proposed relation between quantum transition rates, event-node density, and local-time accumulation.

The conjecture should therefore not be stated as:

```text
Planck's constant directly defines temporal density.
```

A more precise formulation is:

```text
Effective quantum-transition dynamics, possibly involving H_eff / hbar_eff and related dimensionless physical relations, may influence event-node density relative to frontal time.
```

This distinction matters because raw changes to a dimensionful constant such as `h` are not necessarily physically meaningful by themselves. A stronger future version of the conjecture should identify dimensionless relations that control effective quantum transition rates.

## Closed Causal Loops

The global-slice interpretation gives the Closed Time Loop model a place inside frontal time without requiring an already-realized history to be rewritten.

A loop-containing branch can be represented as a self-consistent complete continuation whose earlier branch state already includes the reintegrated traveler and whose later state includes the corresponding departure.

A retrospective diagram may therefore show a selected frontal-time slice inside the complete loop. Such a slice is a reference slice, not the current maximal `F_max` frontier.

See [`closed-time-loop`](../closed-time-loop/) for the detailed model.

## Light-Path Analogy

The light-path analogy is an interpretive analogy inspired by explanations of how light can be modeled as exploring many possible paths while the observed contribution behaves as if a particular path or phase-coherent family of paths dominates.

In Ontoverse terms, this analogy suggests a possible way to think about an experienced history:

```text
A lived or observed trajectory may be treated as one compatible path through a wider history-space of potential paths.
```

This is only an analogy. It does not claim that human-scale histories literally behave like light rays, nor that Ontoverse currently derives from optics or path-integral physics.

The analogy is useful because it separates:

- the wider space of possible trajectories;
- the compatible or dominant path that becomes relevant to observation;
- the need to define why one accessible history is experienced rather than another.

## Interpretive Claim

The tentative claim is not:

```text
Planck's constant proves the Ontoverse model.
```

Nor is the global-slice interpretation claimed to be an established physical account of time.

The current tentative claim is:

```text
A shared sequence of global history-space slices may provide a useful conceptual separation between frontal ordering and branch-local time accumulation, while effective quantum-transition dynamics may be a candidate for formalizing how event-node density differs between branches.
```

## Open Problems

- Define mathematically what a frontal-time slice `S(F)` contains.
- Clarify the ontological distinction between admissible, possible, actualized, and realized branch states inside a slice.
- Determine whether frontal time is continuous, discrete, or only an ordering relation.
- Define the current maximal frontal-time value `F_max` rigorously.
- Formalize the rule that maps a global slice and its admissible continuation space to later slices.
- Clarify whether global consistency filtering preserves many admissible branches, implies determinism, or requires another selection rule.
- Relate frontal-time slices to existing physical notions of time, foliation, boundary conditions, and causal structure without assuming equivalence.
- Define what qualifies as a significant event-node.
- Determine whether temporal density can be expressed through an effective transition rate, action, entropy, decoherence rate, information change, or another quantity.
- Clarify whether `event-nodes / frontal-time` can become a rigorous measure.
- Determine whether `Gamma_eff` can be formalized through Hamiltonian evolution, transition rates, decoherence, interaction rates, or only used as a conceptual placeholder.
- Formalize the distinction and possible coupling between causal processing density and temporal density.
- Clarify whether Planck's constant is only background motivation here or whether dimensionless relations involving `hbar` can serve as part of a formal scale relation.
- Clarify how this model relates to proper time in relativity.
- Clarify how branch baseline metrics, local metric deviations, and causal processing density could be compared with spacetime curvature, gravitational time dilation, and stress-energy in established relativity.
- Clarify whether gravitational-wave analogies should be limited to metric fluctuation metaphors or can be mapped to more formal wave-like changes in causal processing density.
- Clarify whether the light-path analogy can be mapped to action principles, path integrals, or only used as a conceptual metaphor.
