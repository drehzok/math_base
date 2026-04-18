---
subject: topology
---
# Serre Fibration
**Prerequisites:** [[Homotopy Group]]

## Definitions
A map $p: E \to B$ is a **Serre fibration** if it satisfies the homotopy lifting property for CW complexes. That is, every diagram:
$$ X \times \{0\} \to E $$
$$ \downarrow \quad \swarrow \quad \downarrow p $$
$$ X \times I \to B $$
has a lifting that makes the triangles commute.

## Theorems
For a Serre fibration $p: E \to B$, if $b \in B$ and $F = p^{-1}(b)$, there exists a Long Exact Sequence (LES) of homotopy groups:
$$ \dots \to \pi_n(F, x) \to \pi_n(E, x) \to \pi_n(B, x) \to \pi_{n-1}(F, x) \to \dots $$

## Examples
- Fibre bundles
- Covering spaces
- Hopf map $S^{2n+1} \to \mathbb{CP}^n$ with fibre $S^1$.

## Sources
- [[01-raw-sources/topology2/week1.pdf]]