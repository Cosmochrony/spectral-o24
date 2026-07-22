This repository contains the source of the **O24 Cosmochrony paper**  
*Observable-Rank Stability under Vertical Non-Injectivity:
Closing the Fibre-Structure Conditionality in the Born–Infeld-to-Cascade Chain*.

**Version 1.2.0.** The verticality lemma and observable-rank stability theorem are unchanged.
The paper now separates their fibre-structure closure from the independent Heisenberg capacity-to-rate step.

This work extends the **spectral admissibility sub-programme** by resolving
the residual fibre-cardinality condition inherited from **O18** after the
closures achieved by **O22** and **O23**:

> Does the admissibility mechanism depend on the cardinality of the fibres
> of the projection $\Pi$, or only on the structure of its image?

## Context

**O21–O23** established that:

- the proposed fibre-level observable is the canonical pair quantity
  $\sigma_{\mathrm{pair}}^{\mathrm{can}}(n)$
- saturation occurs intrinsically on a BFS shell (**O22**, projection locking)
- the threshold value  
  $\Sigma_c(n_3) = 3$  
  is a structural consequence of quaternionic minimality (**O23**)

However:

- **O18** required the strong condition that parity is the *only*
  symmetry of $S_{\mathrm{BI}}$
- this ensured that fibres are minimal: $\{\chi, -\chi\}$
- the fibre-side observable-rank argument still depended on this assumption

This defines the scope of **O24**.

## Core Result

The paper proves that **the size of the fibres is irrelevant to the stated observable-rank result**.

The key mechanism is the **verticality of admissible symmetries**:

- any symmetry preserving Born–Infeld admissibility preserves the admissible sector
- any new direction it generates must lie in this sector
- the admissible neutral traceless sector has **maximal real rank 3** (O23)

Therefore:

- no transversal symmetry is admissible
- all admissible symmetries act **within the fibres of $\Pi$**

Thus:

- fibre cardinality can vary freely
- observable rank is invariant

## Main Structural Results

### 1. Rank–kernel decoupling

*Lemma.* The real rank of  
$\operatorname{Im}\Pi \cap \mathcal{N}_{\mathrm{trl}}$  
is independent of $\ker \Pi$.

Thus:

- enlarging fibres does not change observable directions
- microscopic multiplicity is decoupled from effective structure

### 2. Verticality lemma

*Lemma.* Any $g \in G_{\mathrm{BI}}$ compatible with admissibility either:

- acts within the fibres (vertical), or
- generates a new admissible neutral traceless direction

The second case is impossible:

- admissibility is preserved by $g$
- any generated direction lies in the admissible sector
- O23 proves this sector is **maximal of real rank 3**

Thus all admissible symmetries are vertical.

### 3. Exclusion of transversal actions

Any transversal symmetry would:

- produce a fourth independent admissible direction
- contradict quaternionic maximality

Thus:

- transversal non-injectivity is excluded
- only vertical non-injectivity is compatible with admissibility

### 4. Observable rank stability theorem

*Theorem.*  
The real rank of the admissible neutral traceless observable sector is:

$\dim_{\mathbb{R}}(\operatorname{Im}\Pi \cap \mathcal{N}_{\mathrm{trl}}) = 3$

independently of the cardinality of the fibres of $\Pi$.

### 5. Fibre-structure closure

*Corollary.* The observable-rank condition supporting the fibre-side
$c_{\mathrm{BI}} \to \delta_{\mathrm{pair}}$ segment holds unconditionally with respect to the
fibre structure of $\Pi$, with no assumption on fibre size.

The separate $\delta_{\mathrm{pair}} \to \beta^*$ step is not derived natively on the Heisenberg substrate.
Using $1/(\delta_{\mathrm{pair}}+\tfrac12)$ therefore remains a conditional cross-substrate
phenomenological prescription.

## Foundational Chain from the Substrate

Within the stated Born--Infeld and quaternionic-maximality premises, the fibre-side argument is internal:

Born–Infeld admissibility  
$\to$ admissible sector invariance  
$\to$ quaternionic maximality (O23)  
$\to$ exclusion of transversal directions  
$\to$ verticality of symmetries  
$\to$ rank invariance  
$\to$ fibre-side rank stability

No minimal-cardinality assumption on fibres is required for that result.
The chain does not produce a native pair-capacity growth carrier.

## Mathematical Role of O24

**O24** performs the final closure of the fibre-level admissibility framework:

- it removes the last conditional hypothesis (O18)
- it replaces fibre minimality with rank invariance
- it establishes verticality as the correct structural condition

More precisely, the paper:

- proves rank–kernel decoupling
- proves verticality of admissible symmetries
- excludes transversal admissible actions via maximality
- establishes observable rank rigidity
- removes dependence on fibre cardinality
- closes the fibre-cardinality conditionality in the $c_{\mathrm{BI}} \to \delta_{\mathrm{pair}}$ segment

## Epistemic Structure of the Paper

### Established input

- fibre structure (**O18**)
- canonical observable (**O19–O21**)
- projection locking (**O22**)
- quaternionic maximality (**O23**)
- Born–Infeld admissibility
- Weil framework

### New results

- rank–kernel decoupling lemma
- verticality lemma
- exclusion of transversal admissible symmetries
- observable rank stability theorem
- fibre-structure closure corollary

### Remaining open problems

- numerical determination of $n_3$
- large-$q$ behaviour
- extension beyond SU(2)-type structures
- dynamical modelling of fluctuations
- full numerical closure of the pipeline
- a native growth process carrying the pair observable

## Interpretation of the Result

The conceptual shift is decisive:

- **O18**: fibres must be minimal
- **O24**: fibres can be arbitrarily large

provided that:

- they act vertically
- they do not increase observable rank

Thus:

- the mechanism depends on **image structure**
- not on **preimage multiplicity**

The key insight is:

> observable physics is controlled by rank, not by microscopic multiplicity.

## Structural Role of O24

**O24** completes the fibre-structure sequence:

- **O18**: fibre structure
- **O19**: canonical normalisation
- **O20**: persistence criterion
- **O21**: intrinsic saturation rank
- **O22**: shell-level locking
- **O23**: threshold dimension
- **O24**: rank stability under non-injectivity

Thus:

- the observable is fixed
- the shell is derived
- the threshold is explained
- the fibre dependence is removed

This closes the dependence on fibre cardinality, not the capacity-to-rate bridge.

## What O24 Adds

- verticality as a structural principle
- rank–kernel decoupling
- exclusion of transversal admissible symmetries
- observable rank rigidity
- independence from fibre cardinality
- theorem-level fibre-structure closure

## Outcome

The spectral admissibility framework is now:

- fibre-level grounded (**O18**)
- amplitude-level canonical (**O19**)
- saturation-level intrinsic (**O21**)
- shell-level derived (**O22**)
- threshold-level explained (**O23**)
- fibre-independent (**O24**)

The admissibility condition is now:

- structural with respect to fibre cardinality
- algebraically constrained
- rank-invariant
- unconditional with respect to the fibre structure of $\Pi$

## Residual Open Problems

### Shell selection

Determine which shell $n_3$ is dynamically selected.

### Large-$q$ regime

Study asymptotic behaviour and scaling.

### Beyond quaternionic structures

Investigate possible higher symmetry frameworks.

### Universality

Test extension beyond SU(2) and Heisenberg graphs.

### Capacity-to-rate bridge

Construct a native growth process carrying the pair observable, or state an explicitly
cross-substrate hypothesis for $\delta_{\mathrm{pair}} \to \beta^*$.

## Status

The programme is now:

- fibre-structure conditionality closed
- independent of fibre assumptions
- explicit about the unresolved native capacity-to-rate step

## Repository Structure

```text
paper/
├── out/      # Compiled O24 PDF
├── tex/      # LaTeX sources
└── README.md
```
# Citation

If you reference this work, please cite:

J. Beau
Observable-Rank Stability under Vertical Non-Injectivity:
Closing the Fibre-Structure Conditionality in the Born–Infeld-to-Cascade Chain
Zenodo, 2026.

# Acknowledgements

Portions of the derivations, conceptual synthesis, structural organisation,
and editorial refinement benefited from iterative interactions with large
language models used as analytical assistants.

All theoretical results, computations, and interpretations remain the sole
responsibility of the author.

# Contributions

This repository is intended as a research reference.

Critical feedback, independent verification, and further analysis of:

- vertical non-injectivity
- observable rank rigidity
- admissible symmetry structures
- fibre-level dynamics
- spectral admissibility

are welcome.

Please open an issue to discuss conceptual points, technical details, or
possible extensions.
