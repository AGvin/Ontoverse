# Frontal Time Model

Status: draft

The Frontal Time Model separates a global ordering parameter from branch-local experienced time and now treats history-space as a **compressed bundle of currently distinguishable history classes**.

![Temporal density comparison](../../../visualizations/assets/default/diagrams/temporal-density-comparison.svg)

## Frontal Time

Frontal time is a proposed global ordering parameter `F` for the unfolding of history-space.

A value of `F` corresponds to a global cross-section of the current history bundle. Ontoverse calls that cross-section a **frontal-time slice** and writes it conceptually as `S(F)`.

```text
frontal-time value F
-> global slice S(F)
-> current states of all distinguishable history classes at F
```

The phrase **all at once** means all currently distinguishable branch states at one shared global ordering value. It does not mean that one local observer experiences all histories or all frontal-time values simultaneously.

## Frontal-Time Slice as an Actuality Snapshot

The current Ontoverse interpretation treats `S(F)` as an **actuality snapshot of the currently represented history bundle**.

It does not require one fully expanded strand for every complete possible future.

Instead:

```text
S(F)
= states of currently distinguishable history classes
+ compressed admissible continuations still represented inside those classes
```

A class may contain many complete continuations that do not yet require different current physical or record states.

This is a conceptual compression principle. It is not a claim that the universe literally performs data compression.

## Unfolding of Time

The progression of frontal-time slices provides the current Ontoverse picture of how time unfolds globally.

```text
S(F0) -> S(F1) -> S(F2) -> S(F3) -> ...
```

The notation is sampled and does not imply that frontal time is fundamentally discrete.

At each later slice, each represented history class may:

- remain one class if its admissible continuations still require the same current state;
- split into child classes when different current state descriptions become necessary;
- enter a local compatibility channel with globally distinct strands without erasing their historical distinction.

Conceptually:

```text
current class at S(F)
+ admissible complete continuations
+ global consistency constraints
-> keep compressed
   or
-> split at first required state distinction
```

## Minimal Distinguishability Principle

The Frontal Time Model adopts the current working rule:

> Preserve histories in one represented class while their current modeled states are equivalent; separate them only when a physical, record, or causal distinction must already be present at the current slice.

This makes frontal-time evolution a progression of **state distinctions**, not the explicit enumeration of every possible complete timeline.

See [`history-space`](../history-space/) for the history-equivalence-class model.

## Global Consistency

A purely local rule of the form `previous node -> next node` is insufficient for Ontoverse models that contain closed causal constraints.

The stronger working interpretation is:

```text
current slice S(F)
+ current represented history classes
+ admissible continuation space
+ global consistency constraints
-> next consistent bundle state
```

A current state is admissible only if it belongs to at least one globally self-consistent complete continuation.

This does **not** force one deterministic future. Several mutually incompatible complete continuations may remain admissible. They can remain compressed together while current states are equivalent and split when a distinction becomes physically required.

## Branching Under Frontal Time

A divergence node is therefore not best interpreted as the instant when all future worlds are created.

It is the earliest frontal-time location where one represented history class can no longer remain one class.

```text
one history class
-> future-compatible alternatives remain state-equivalent
-> no explicit split yet

later global constraint requires different state
-> divergence node
-> separate child strands
```

A future causal condition can determine that the distinction must already exist at an earlier slice. Past-directed travel is the clearest example.

## Closed Time Loops and Earlier Required Distinctions

Suppose one admissible continuation contains a Closed Time Loop and another does not.

If the loop causes a traveler to reintegrate at `R`, then the loop-containing history already requires a different state at `R`:

```text
before R:
loop-compatible and loop-free continuations may remain one history class

at R:
loop-compatible state = traveler + memories + records + consequences
loop-free state       = no reintegrated traveler

therefore:
class split occurs at R
```

The future departure `D` does not later rewrite `R`.

Instead, the complete loop is one admissible global constraint:

```text
R -> ordinary history -> D -> isolated past transit -> R
```

The frontal-time bundle is already separated as early as required for that structure to remain self-consistent.

If the complete loop requires some earlier difference before reintegration, the split must occur at that earlier first distinction.

## Distant Past-Directed Travel

The distance between reintegration and departure does not create a special logical problem for frontal time.

A loop may in principle connect a much later departure with a very early reintegration because the loop-compatible history class is distinguished at the earliest slice where the returned traveler or another required state difference exists.

```text
early R
-> long branch-local history
-> invention
-> departure D
-> isolated past transit
-> same R
```

The traveler state at `R`, including memories and carried records, is part of that loop-compatible strand from the moment it first becomes distinguishable.

This does not establish that arbitrarily distant physical time travel is possible; physical limits remain open.

## Future-Derived Information

The same structure permits branch-relative future-derived information.

```text
later record
-> past-directed carrier
-> earlier memory or record
-> earlier reaction
-> same self-consistent later record
```

An earlier observer may therefore appear to predict or "see" a future event if a compatible information carrier returns from that future along the same loop-containing strand.

This is not unrestricted knowledge of all future history classes. It is information carried inside one globally constrained continuation.

Bootstrap-information loops remain an open problem.

## Current Frontier and Reference Slices

The current maximum `F_max` is the greatest frontal-time value treated as actualized in the shown model state.

When a diagram shows `S(F_max)`, the ruby frontal-time plane is the **current frontier**:

```text
represented history bundle -> S(F_max)
```

Realized strands normally terminate there.

A retrospective diagram may instead show an earlier reference slice `S(F_ref)` inside already described history. Realized structure may then appear on both sides of the plane because it is not the current maximum.

## Observer Access

A global slice may contain many distinguishable history classes.

A local observer accesses only states, records, and interactions compatible with the observer's own historical strand.

```text
global S(F)
= many history-class states

observer experience
= one compatible path through successive slices
```

## Local Time

Local time is the time experienced along one historical strand.

The working intuition is that local time accumulates through significant branch-local physical transitions as frontal time progresses globally.

```text
local time ~ accumulated significant event-nodes
```

## Temporal Density

Temporal density is the proposed frequency of significant event-nodes per frontal-time interval.

```text
sampled slices:       F0  F1  F2  F3  F4  F5  F6
high-density strand:  *   *   *   *   *   *   *
low-density strand:   *   .   .   *   .   .   *
```

Both strands advance through the same global frontal-time ordering. They differ in how frequently significant transitions accumulate.

```text
temporal density ~ significant event-nodes / frontal-time interval
```

Under the current hypothesis, higher temporal density means more local-time accumulation over the same `ΔF`.

A class that later splits may have one shared density description before divergence and separate branch-local density descriptions after divergence.

## Temporal Density vs Causal Processing Density

**Temporal density** and **causal processing density** remain separate concepts.

Temporal density:

```text
frequency of significant branch-local transitions / ΔF
```

Causal processing density:

```text
speculative amount of local state coordination, constraint, interaction bookkeeping,
or physical processing load relative to frontal-time slices
```

The current gravity interpretation explores the conjectural chain:

```text
higher causal processing load
-> lower effective significant-transition rate
-> lower temporal density
-> slower local-time accumulation relative to F
```

This is not established physics.

## Quantum Transition Rate Conjecture

Status: conjecture

The quantum transition rate conjecture proposes an effective transition-rate parameter:

```text
Gamma_eff = effective rate of significant quantum transitions per unit of frontal time
```

The established physics background is that Planck's constant has the dimensions of action and, since the 2019 SI revision, has the exact numerical value:

```text
h = 6.62607015 x 10^-34 J s
```

Ontoverse does not treat `h` or `hbar` as a direct temporal-density measure.

The speculative bridge is instead:

```text
quantum-state dynamics
-> Gamma_eff
-> significant event-node frequency
-> temporal density
-> local-time accumulation
```

A possible physical inspiration is the role of effective Hamiltonian scales relative to `hbar`, together with interaction strength, available states, coupling, decoherence, and other physical structure.

No rigorous mapping has yet been defined.

## Branch Metrics and Local Metric Deviations

Status: working definition

The model may distinguish between an absolute baseline metric, a history-strand baseline metric, and local metric deviations.

### Related Visualizations

![Branch baseline versus local metric deviation](./assets/svg/branch-baseline-vs-local-deviation.svg)

![Mass, time-rate gradient, and gravity](./assets/svg/mass-gravity-time-rate.svg)

![Gravity well interpretation](./assets/svg/gravity-well-interpretation.svg)

![Gravitational wave interpretation](./assets/svg/gravitational-wave-interpretation.svg)

The branch baseline metric represents the average nominal state of one currently distinguishable historical strand. Before a history-class split, descendants may share the same represented baseline. After a split, child strands may develop distinct branch baselines.

```text
history-strand baseline
-> average causal processing density
-> effective transition rate
-> temporal density
-> branch-local time rate
```

## Causal Processing Density and Gravity

Status: interpretive hypothesis

Within Ontoverse, mass-energy concentration may be treated as a marker of increased local state-coordination load.

The current conjectural chain is:

```text
mass-energy concentration
-> causal processing density increases
-> effective significant-transition rate decreases
-> temporal density decreases
-> local time-rate slowdown
-> local time-rate gradient
-> curved possible trajectories
-> gravitational effect
```

The middle steps are speculative Ontoverse components, not established physics.

Gravitational waves are analogously represented as moving metric deviations that can alter causal-processing load and local time-rate gradients temporarily.

## Relation to Existing Concepts

The frontal-time and history-bundle model should be compared with existing ideas including:

- global time parameters and foliations;
- branching-time semantics;
- equivalence classes and quotient-state representations;
- consistent and decoherent histories;
- coarse-graining;
- state-space dynamics;
- global boundary-condition and all-at-once formulations;
- retrocausal descriptions;
- closed timelike curves and self-consistency conditions.

No equivalence is currently claimed.

## Open Problems

- Define mathematically what a frontal-time slice `S(F)` contains.
- Define the current maximum `F_max` rigorously.
- Determine whether frontal time is continuous, discrete, or only an ordering relation.
- Define the history equivalence relation used to compress admissible continuations.
- Formalize how one slice and its continuation space produce the next represented history bundle.
- Formalize the first-required-distinction rule for branch splitting.
- Clarify whether histories only refine/split under frontal-time progression or whether global recompression has physical meaning.
- Clarify whether global consistency preserves many admissible histories, introduces probabilities, or requires another selection rule.
- Relate frontal-time slices to established physical notions of time and causality without assuming equivalence.
- Define what qualifies as a significant event-node.
- Formalize temporal density and its behavior before and after history-class splits.
- Determine whether `Gamma_eff` can be linked to established transition-rate physics.
- Formalize the distinction and possible coupling between causal processing density and temporal density.
- Clarify how local time relates to proper time in relativity.
- Formalize branch baseline metrics and local metric deviations.
- Compare time-loop-induced class splitting with established treatments of closed timelike curves, retrocausality, and global consistency.
