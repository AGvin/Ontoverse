# History-Space Model

Status: draft

The History-Space Model asks a simple structural question:

> How many separate histories do we actually need to represent **right now**?

Ontoverse does not assume that every complete possible future must already exist as a permanently separate timeline from the beginning. Histories that still require the same modeled physical state, records, and causal description may remain represented together and separate only when a real distinction is required.

That produces the current **history bundle** model: a branching set of currently distinguishable Historical Strands progressing in the same frontal-time direction.

![Isometric history-space diagram](../../../visualizations/assets/default/diagrams/isometric-history-space.svg)

## Translations

- English
- [Українська](./l10n/uk_UA/)

## The Cable Analogy

A useful first image is an indefinitely multi-strand cable moving in one direction:

```text
                         increasing frontal time F
                                  ->

history bundle    ================================
                   \==== strand/class B =========>
                    \=== strand/class C =========>
                         \== strand/class D ======>
```

The important twist is that the cable is **not fully separated in advance**.

One visible strand may represent a whole **History Equivalence Class** containing many admissible complete histories that are still indistinguishable at the current model resolution.

```text
one represented history class
           |
           |  still state-equivalent
           |
           +------ first required distinction
                  /                     \
             class A                 class B
```

The cable language is only an intuition. Ontoverse does not currently claim that history-space is mathematically a fiber bundle or that reality literally stores timelines as data structures.

## A Concrete Example

Imagine two admissible complete histories that are identical until tomorrow afternoon.

In one, a coin lands heads. In the other, it lands tails.

If nothing before the toss requires a different physical or record state, Ontoverse does not need two separately represented strands today merely because the futures eventually differ.

Conceptually:

```text
today
one shared history class
        |
        |
   tomorrow: coin toss
       /            \
    heads          tails
```

The two complete continuations are different, but the model keeps them compressed while their current state descriptions remain equivalent.

The coin example is deliberately simple. Real physical distinctions would involve the complete relevant state, not one isolated classical variable.

## History Equivalence Class

At a frontal-time slice `S(F)`, two admissible complete histories may belong to the same **History Equivalence Class** when they require the same modeled current physical state, records, and causal description at that slice.

Conceptually:

```text
H1 ~F H2

means:
H1 and H2 do not yet require separate current state descriptions at F
```

A represented Historical Strand can therefore stand for the whole class rather than one fully enumerated future.

The underlying continuation space may still be enormous or infinite. The compression is only in how many distinctions must be represented explicitly **at the current slice**.

## Historical Strand

A **Historical Strand** is the visible or working representation of one currently distinguishable history class across frontal-time slices.

It should not automatically be read as one universe that has been independently separate from every other possibility since the beginning.

```text
one Historical Strand
= one currently distinguishable history class
= potentially many still-equivalent complete continuations
```

As frontal time advances, the strand can remain single or split into child strands when its admissible members require different current states.

## Frontal-Time Slices

History-space is globally ordered by frontal time.

At one frontal-time value `F`, the current bundle is sampled by a **Frontal-Time Slice** `S(F)`:

```text
S(F)
= current states of the distinguishable history classes at global ordering value F
```

A single slice can intersect many strands at once.

```text
Historical Strand A  --------|-------->
Historical Strand B  --------|-------->
Historical Strand C  --------|-------->
                            S(F)
```

An ordinary observer does not experience this whole cross-section. Observer access remains constrained to states, records, and interactions compatible with the observer's own strand.

## Event-Node

An Event-Node is a significant transition point in a Historical Strand.

Depending on the level of description, a node may represent a quantum, causal, informational, or observational transition.

A strand does not need a significant node at every sampled frontal-time slice. Its state may persist or evolve below the threshold represented by an Event-Node.

The significance criterion remains open and must eventually be defined mathematically if Temporal Density is to become more than a visualization concept.

## Divergence Node

A **Divergence Node** is the earliest significant location where one previously represented history class can no longer share one current state description.

The intended reading is not:

```text
Divergence Node
-> creates every future universe from nothing
```

It is:

```text
previously equivalent admissible histories
-> first required physical / record / causal distinction
-> class split
-> separately represented child strands
```

This makes divergence about **distinguishability**, not metaphysical creation.

## Minimal Distinguishability Principle

The current working rule is:

> Keep admissible histories represented together while their current modeled states are equivalent; split them only when global consistency requires different current states.

Conceptually:

```text
current class C(F)
+ admissible complete continuations
+ global consistency constraints
-> same class, if current descriptions remain equivalent
-> child classes, if distinct descriptions are required
```

This is the **Minimal Distinguishability Principle**.

It does not prove that nature literally compresses timelines. It says that Ontoverse does not need to posit more explicit current history structure than the model can justify.

## Global Consistency

A represented state is admissible only if it can belong to at least one globally self-consistent complete continuation.

That condition can determine when a class must split.

```text
current class
+ causal structure
+ admissible continuation space
+ global consistency constraints
-> one still-equivalent class
   or
-> several distinguishable child classes
```

Several incompatible but individually self-consistent child classes may remain admissible. Global consistency therefore does not imply one deterministic future.

## The Time-Travel Case

Time travel exposes why the distinction between **future possibility** and **current distinguishability** matters.

Suppose one admissible complete continuation contains a Closed Time Loop and another does not.

If both require the same state before the traveler's reintegration, they may remain in one History Equivalence Class until reintegration event `R`.

At `R`, the loop-compatible continuation contains the returned traveler, memories, records, carried objects, and immediate consequences. The loop-free continuation does not.

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

In this minimal case, `R` is the first required distinction and therefore the Divergence Node between the two classes.

The later departure `D` does **not** create that branch retroactively. It closes the causal loop inside the already loop-compatible strand.

If the complete loop requires some earlier physical distinction, the class must split earlier. Reintegration is the simplest case, not a universal law.

See [`closed-time-loop`](../closed-time-loop/) for the full model.

## Compatibility Channel

A **Compatibility Channel** is a shared access structure in which mutually compatible states, records, and observers can interact.

Several globally distinct history classes can share one channel when their locally accessible states are equivalent under the chosen description.

## Convergent Channel

A **Convergent Channel** is a Compatibility Channel entered by more than one globally distinct Historical Strand.

Convergence does not reverse an earlier class split.

```text
globally distinct strands remain distinct
+
locally accessible states become equivalent
-> shared compatibility channel
```

This lets histories become locally indistinguishable without pretending that their different pasts disappeared.

See [`convergent-channel`](../../../visualizations/sub/convergent-channel/) for the visual explanation.

## Observer Access

An observer does not access every strand in the history bundle.

```text
global history bundle
= many distinguishable history classes

observer experience
= one compatible strand through successive frontal-time slices
```

A local Compatibility Channel may temporarily make states from several globally distinct strands observationally equivalent without making their complete histories identical.

## Temporal Density in the Bundle

Frontal time is global, but Temporal Density is strand-local.

Across the same frontal-time interval, one strand may accumulate significant Event-Nodes frequently while another persists across more slices without a significant transition.

```text
sampled slices:       F0  F1  F2  F3  F4  F5
high-density strand:  *   *   *   *   *   *
low-density strand:   *   .   .   *   .   *
```

The strands share one global ordering while accumulating different amounts of significant local change.

See [`frontal-time`](../frontal-time/) for the detailed model.

## Current Frontier and Reference Slices

The current maximum frontal-time value `F_max` represents the latest actualized global slice in the shown model state.

When a diagram shows `S(F_max)`, the ruby Frontal Time Plane is the **current frontier** and realized strands normally terminate there.

A retrospective causal-structure diagram may instead select an earlier slice `S(F_ref)` inside already described history. Realized structure can then appear on both sides because the plane is only a reference cross-section, not the current maximum.

## Relation to Existing Concepts

The compression model should be compared with existing mathematical and physical ideas rather than assumed to be novel or equivalent to them.

Relevant comparison targets include:

- equivalence classes and quotient constructions;
- branching-time and possible-world semantics;
- consistent or decoherent histories;
- coarse-graining;
- state-space representations;
- tree and directed-acyclic-graph models;
- bundle-like and sheaf-like structures;
- global boundary-condition formulations.

The Ontoverse phrase **History Bundle** is currently a structural analogy, not a claim of formal equivalence to a mathematical fiber bundle.

## Open Problems

- Define `history-space` mathematically.
- Define the equivalence relation `~F` precisely.
- Specify which physical, informational, or observer-relative properties determine state equivalence.
- Determine whether global history classes only refine/split with increasing frontal time or whether stronger global recompression has meaning.
- Distinguish global historical equivalence from local observer-level equivalence in Convergent Channels.
- Define a Divergence Node rigorously as the earliest required state distinction.
- Determine whether the Minimal Distinguishability Principle is ontological, representational, or only a visualization rule.
- Determine how probabilities or measures apply to still-compressed continuation space.
- Formalize how global consistency constraints induce history-class splits.
- Determine how time-travel loops affect class structure when reintegration lies arbitrarily far in the past.
- Clarify whether the bundle analogy maps usefully to existing bundle, sheaf, branching-process, or quotient-space mathematics.
- Define Event-Node criteria rigorously.
- Clarify how Temporal Density is measured on a strand whose represented class later splits.
