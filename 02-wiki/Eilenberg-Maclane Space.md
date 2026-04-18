---
subject: topology
---
# Eilenberg-Maclane Space
**Prerequisites:** [[Homotopy Group]], [[CW Complex]]

## Definitions
For $n \ge 1$ and a group $A$ (abelian if $n > 1$), an Eilenberg-Maclane (EM) space is a path-connected CW complex $(K(A, n), *)$ with an isomorphism $\pi_n(K(A, n), *) \cong A$ such that $\pi_k(K(A, n), *) = 0$ for all $k \neq n$.

## Theorems
- $K(A, n)$ always exists and is unique up to homotopy.
- Every space $X$ is iteratively built out of EM spaces (Postnikov tower).
- There is a natural isomorphism $[X, K(A, n)] \cong H^n(X; A)$.

## Examples
- $S^1$ is $K(\mathbb{Z}, 1)$.
- $\mathbb{CP}^\infty$ is $K(\mathbb{Z}, 2)$.

## Sources
- [[01-raw-sources/topology2/week1.pdf]]