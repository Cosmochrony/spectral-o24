This repository contains the source of the **O24 Cosmochrony paper**  
*Observable-Rank Stability under Vertical Non-Injectivity:
Closing the Fibre-Structure Conditionality in the Born–Infeld-to-Cascade Chain*.

**Version 1.2.0.** The verticality lemma and observable-rank stability theorem are unchanged.
The paper now separates their fibre-structure closure from the independent Heisenberg capacity-to-rate step.

This work extends the **spectral admissibility sub-programme** by resolving
the residual fibre-cardinality condition inherited from **O18** after the
closure achieved by **O22** and the conditional carrier result of **O23**:

> Does the admissibility mechanism depend on the cardinality of the fibres
> of the projection $\Pi$, or only on the structure of its image?

## Context

**O21–O23** provide the inputs:

- the proposed pair-level observable is the canonical pair quantity
  $\sigma_{\mathrm{pair}}^{\mathrm{can}}(n)$
- saturation occurs intrinsically on a BFS shell (**O22**, projection locking)
- the threshold value  
  $\Sigma_c(n_3) = 3$  
  is a supplied selection rule: **O23** proves (Theorem 3.1) that the traceless sector of a
  supplied spinor carrier $V_\rho \cong \mathbb{C}^2$ is $\mathfrak{su}(2)$, of real dimension
  exactly 3, while the carrier selection and the identification of $\Sigma_c$ with that
  dimension remain open

Moreover:

- the clause that parity is the *only* symmetry of $S_{\mathrm{BI}}$ is part of the open
  fibre-identification problem of **O18** (Problem 2.8, Remark 2.9), not a theorem
- if established, it would make parity fibres minimal: $\{\chi, -\chi\}$
- the fibre-side observable-rank argument depended on this assumption

This defines the scope of **O24**.

## Core Result

The paper proves that **the size of the fibres is irrelevant to the stated observable-rank result**.

The key mechanism is the **verticality of admissible symmetries**:

- any symmetry preserving Born–Infeld admissibility preserves the admissible sector
- any new direction it generates must lie in this sector
- under the supplied spinor carrier of O23, the admissible neutral traceless sector has
  **real rank exactly 3** (O23 Theorem 3.1)

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
- under the supplied carrier, O23 (Theorem 3.1) bounds this sector at **real rank 3**

Thus all admissible symmetries are vertical.

### 3. Exclusion of transversal actions

Any transversal symmetry would:

- produce a fourth independent admissible direction
- contradict the rank-three bound of the supplied carrier (O23 Theorem 3.1)

Thus:

- transversal non-injectivity is excluded
- only vertical non-injectivity is compatible with admissibility

### 4. Observable rank stability theorem

*Theorem.*  
Under the supplied spinor carrier of O23, the real rank of the admissible neutral traceless
observable sector is:

$\dim_{\mathbb{R}}(\operatorname{Im}\Pi \cap \mathcal{N}_{\mathrm{trl}}) = 3$

independently of the cardinality of the fibres of $\Pi$.

### 5. Fibre-structure closure

*Corollary.* The observable-rank condition supporting the fibre-side
$c_{\mathrm{BI}} \to \delta_{\mathrm{pair}}$ segment is insensitive to the
fibre structure of $\Pi$, with no assumption on fibre size; it remains conditional on the
supplied carrier and $\Sigma_c$ identification of O23.

The separate $\delta_{\mathrm{pair}} \to \beta^*$ step is not derived natively on the Heisenberg substrate.
Using $1/(\delta_{\mathrm{pair}}+\tfrac12)$ therefore remains a conditional cross-substrate
phenomenological prescription.

## Foundational Chain from the Substrate

Within the stated Born–Infeld premise and the supplied rank-three carrier of O23,
the fibre-side argument is internal:

Born–Infeld admissibility  
$\to$ admissible sector invariance  
$\to$ rank-three carrier (O23 Theorem 3.1, supplied carrier)  
$\to$ exclusion of transversal directions  
$\to$ verticality of symmetries  
$\to$ rank invariance  
$\to$ fibre-side rank stability

No minimal-cardinality assumption on fibres is required for that result.
The chain does not produce a native pair-capacity growth carrier.

## Mathematical Role of O24

**O24** performs the final closure of the fibre-level admissibility framework:

- it removes the absence-of-further-symmetries clause (part of O18's open Problem 2.8)
- it replaces fibre minimality with rank invariance
- it establishes verticality as the correct structural condition

More precisely, the paper:

- proves rank–kernel decoupling
- proves verticality of admissible symmetries
- excludes transversal admissible actions via the rank-three bound
- establishes observable rank rigidity
- removes dependence on fibre cardinality
- closes the fibre-cardinality conditionality in the $c_{\mathrm{BI}} \to \delta_{\mathrm{pair}}$ segment

## Epistemic Structure of the Paper

### Established input

- Born–Infeld parity equivariance (**O18**; the fibre identification is open there)
- canonical observable (**O19–O21**)
- projection locking (**O22**)
- conditional rank-three carrier (**O23** Theorem 3.1, supplied spinor carrier)
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

- absence-of-further-symmetries clause (O18 Problem 2.8): fibres must be minimal
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

- **O18**: parity equivariance, fibre identification stated as open
- **O19**: canonical normalisation
- **O20**: persistence criterion
- **O21**: intrinsic saturation rank
- **O22**: shell-level locking
- **O23**: conditional threshold dimension (supplied carrier)
- **O24**: rank stability under non-injectivity

Thus:

- the observable is fixed
- the shell is derived
- the threshold is a supplied selection rule with a conditional dimension theorem
- the fibre-cardinality dependence is removed (carrier and fibre hypotheses supplied)

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

- parity-equivariant at the Born–Infeld level (**O18**), with the fibre identification open
- amplitude-level canonical (**O19**)
- saturation-level intrinsic (**O21**)
- shell-level derived (**O22**)
- threshold-level conditional on the supplied carrier (**O23**)
- fibre-cardinality independent (**O24**)

The admissibility condition is now:

- structural with respect to fibre cardinality
- algebraically constrained
- rank-invariant
- insensitive to the fibre structure of $\Pi$ (conditional on the supplied carrier of O23)

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

- fibre-structure conditionality reduced to the supplied carrier and fibre hypotheses
- independent of fibre-cardinality assumptions
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
