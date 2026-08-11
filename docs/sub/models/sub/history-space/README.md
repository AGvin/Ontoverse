# History-Space Model

Status: draft

The History-Space Model describes reality as a structured space of admissible histories ordered by frontal time.

The current Ontoverse model does **not** require every complete possible history to be represented as a permanently separate timeline from the beginning. Histories that still require the same modeled physical and record state may remain represented together and become separate only when a real distinction is required.

This produces a **history bundle**: a branching set of currently distinguishable history strands progressing in the same frontal-time direction.

![Isometric history-space diagram](../../../visualizations/assets/default/diagrams/isometric-history-space.svg)

## Core Intuition

A useful visual analogy is an indefinitely multi-strand cable moving in one global direction.

```text
                         increasing frontal time F
                                  ->

history bundle    ================================
                   \==== strand/class B =========>
                    \=== strand/class C =========>
                         \== strand/class D ======>
```

The analogy has an important refinement: the model does not need to draw one separate strand for every complete future continuation in advance.

Instead, one currently represented strand may stand for a **history equivalence class** containing many admissible complete histories that are still indistinguishable at the current model resolution.

```text
one represented history class
           |
           |  still state-equivalent
           |
           +------ first required distinction
                  /                     \
             class A                 class B
```

The cable/bundle language is conceptual. Ontoverse does not currently claim that history-space is mathematically a fiber bundle or that reality literally stores timelines as data structures.

## History Equivalence Class

At a frontal-time slice `S(F)`, two admissible complete histories may be treated as members of the same **history equivalence class** when they require the same modeled branch-local physical state, records, and causal description up to that slice.

Conceptually:

```text
H1 ~F H2

means:
H1 and H2 are not yet distinguishable by the modeled state at frontal-time value F
```

A represented history strand can therefore stand for the whole equivalence class rather than for one fully enumerated future.

This is a **compression principle for the conceptual model**, not a claim about the computational implementation of the universe.

The underlying set of admissible complete continuations may still be extremely large or infinite. The reduction is in how many distinctions must be represented explicitly at a given frontal-time slice.

## Historical Strand

A **historical strand** is the visible or working representation of one currently distinguishable history class across frontal-time slices.

A strand should not automatically be interpreted as one eternally separate universe that had to exist independently from the earliest modeled state.

Instead:

```text
one strand
= one currently distinguishable historical state class
= potentially many still-equivalent complete continuations
```

As frontal time advances, a strand may remain single or split into child strands when its admissible members require different physical states.

## Frontal-Time Slices

History-space is globally ordered by frontal time.

At a frontal-time value `F`, the model represents a cross-section of the current history bundle as a **frontal-time slice** `S(F)`.

```text
S(F)
= current states of the distinguishable history classes at global ordering value F
```

A single slice may therefore intersect many strands at once.

```text
history strand A  --------|-------->
history strand B  --------|-------->
history strand C  --------|-------->
                         S(F)
```

An ordinary observer does not experience this whole cross-section. Observer access remains constrained to states, records, and interactions compatible with the observer's own strand.

## Event-Node

An event-node is a significant transition point in a historical strand.

A node may represent a quantum, causal, informational, or observational transition depending on the level of description.

A strand does not need to contain a significant event-node at every sampled frontal-time slice. Its state may persist or evolve below the threshold represented by an event-node.

A rigorous significance criterion remains open.

## Divergence Node

A **divergence node** is the earliest significant location at which one previously represented history class must separate into multiple incompatible state descriptions.

The current interpretation is therefore not:

```text
divergence node
-> creates every future universe from nothing
```

It is closer to:

```text
previously equivalent admissible histories
-> first required physical or record distinction
-> history-class split
-> separately represented child strands
```

The downstream continuations may have existed as admissible possibilities before the split, but they did not require separate represented strands while they were state-equivalent under the model.

This distinction becomes important for past-directed travel.

## Time-Travel-Induced Class Split

Suppose one admissible complete continuation contains a Closed Time Loop and another does not.

If both continuations require the same state before the traveler's reintegration, they may remain represented by one history class until the reintegration event `R`.

At `R`, the loop-containing continuation now contains the traveler, the traveler's memories and records, and the immediate physical consequences of arrival. The loop-free continuation does not.

The history class must therefore split there:

```text
shared history class
-------------------R-------------------->
                    |\
                    | \  loop-free strand
                    |
                    +---- loop-compatible strand ---- D
                          ^                             |
                          +------ past transit ---------+
```

In the minimal case, `R` is the first required distinction and therefore the divergence location between the loop-compatible and loop-free history classes.

The later departure `D` does **not** create that branch retroactively. `D` closes the causal loop inside the already loop-compatible strand.

If the complete loop requires an earlier physical distinction for some other reason, the class split must occur at that earlier first distinction instead. Reintegration is therefore the usual simple case, not an unconditional universal rule.

## Minimal Distinguishability Principle

The current working model uses a **minimal distinguishability principle**:

> Keep admissible histories represented together while their modeled current states are equivalent; split them only when global consistency requires different current physical or record states.

Conceptually:

```text
current history class C(F)
+ admissible complete continuations
+ global consistency constraints
-> same class, if current state descriptions remain equivalent
-> child classes, if distinct current state descriptions are required
```

This avoids requiring Ontoverse to model an independently instantiated strand for every conceivable future continuation at every earlier slice.

It does not prove that nature performs literal compression, nor does it establish the cardinality of history-space.

## Global Consistency

A branch state is treated as admissible only if it can belong to at least one globally self-consistent complete continuation.

The consistency condition can therefore constrain when a history class must split.

```text
current class
+ causal structure
+ admissible continuation space
+ global consistency constraints
-> one still-equivalent class
   or
-> several distinguishable child classes
```

Several mutually incompatible but individually self-consistent child classes may remain admissible. Global consistency therefore does not imply one deterministic future.

See [`closed-time-loop`](../closed-time-loop/) for the case in which a later departure constrains an earlier reintegration state inside one loop-compatible strand.

## Compatibility Channel

A compatibility channel is a shared access structure where only mutually compatible states, records, and observers can interact.

A channel can be shared by more than one globally distinct history class when their locally accessible states are equivalent under the chosen description.

## Convergent Channel

A convergent channel is a compatibility channel entered by more than one globally distinct historical strand.

Convergence does **not** reverse a previous global class split or erase historical multiplicity.

A safer interpretation is:

```text
globally distinct strands remain distinct
+
locally accessible states become equivalent
-> shared compatibility channel
```

The channel may therefore visually compress several strands into one locally shared route while retaining the fact that several historical origins are represented.

See [`convergent-channel`](../../../visualizations/sub/convergent-channel/) for the visual explanation.

## Observer Access

An observer does not access every strand in the history bundle.

The observer can interact only with states, records, and other observers compatible with the observer's own local history.

```text
global history bundle
= many distinguishable history classes

observer experience
= one compatible strand through successive frontal-time slices
```

A local compatibility channel may temporarily make states from several globally distinct strands observationally equivalent without making their full histories identical.

## Temporal Density in the Bundle

Temporal density remains branch-local even though frontal time is global.

Across the same frontal-time interval, one strand may accumulate significant event-nodes frequently while another persists across more slices without a significant transition.

```text
sampled slices:       F0  F1  F2  F3  F4  F5
high-density strand:  *   *   *   *   *   *
low-density strand:   *   .   .   *   .   *
```

This is compatible with the history-bundle model because different strands can have different local transition rates while sharing the same global ordering direction.

See [`frontal-time`](../frontal-time/) for the detailed temporal-density model.

## Frontal-Time Boundary and Reference Slices

The current maximum frontal-time value `F_max` represents the latest actualized global slice in the current model.

When a diagram shows `S(F_max)`, the ruby frontal-time plane is the **current frontier** and realized strands normally terminate there.

A retrospective causal-structure diagram may instead show an earlier selected slice `S(F_ref)` inside already described history. Realized structure may then appear on both sides because the plane is a reference cross-section, not the current maximum.

## Relation to Existing Concepts

The history-class compression idea should be compared with existing mathematical and physical concepts rather than assumed to be novel or equivalent to them.

Potential comparison targets include:

- equivalence classes and quotient constructions;
- branching-time and possible-world semantics;
- consistent or decoherent histories;
- coarse-graining;
- state-space representations;
- tree and directed-acyclic-graph models;
- bundle-like mathematical structures;
- global boundary-condition formulations.

The current Ontoverse use of **history bundle** is a visual and structural analogy, not a claim of formal equivalence to a mathematical fiber bundle.

## Open Problems

- Define `history-space` mathematically.
- Define the equivalence relation `~F` precisely.
- Specify which physical, informational, or observer-relative properties determine whether two histories are state-equivalent.
- Determine whether global history classes only refine/split with increasing frontal time or whether a stronger global recompression operation is meaningful.
- Distinguish global historical equivalence from local observer-level equivalence in convergent channels.
- Define a divergence node rigorously as the earliest required state distinction.
- Determine whether the minimal distinguishability principle is an ontology, a representational compression, or only a visualization rule.
- Determine how probabilities or measures over the still-compressed continuation space should be represented.
- Formalize how global consistency constraints induce history-class splits.
- Determine how time-travel loops affect class structure when reintegration lies arbitrarily far in the past.
- Clarify whether the bundle analogy maps usefully to existing bundle, sheaf, branching-process, or quotient-space mathematics.
- Define event-node criteria rigorously.
- Clarify how temporal density is measured on a strand whose represented equivalence class later splits.
