Prerequisites: [[CW Complex]], [[Homotopy Group]], [[Cohomology]]

# Eilenberg-MacLane Space

## Definition
For an integer $n \geq 1$ and an abelian group $A$ (if $n > 1$, $A$ must be abelian), an **Eilenberg-MacLane space** $K(A, n)$ is a path-connected CW complex such that:
$$\pi_k(K(A, n)) \cong \begin{cases} A & \text{if } k = n \\ 0 & \text{if } k \neq n \end{cases}$$

## Theorem (Existence and Uniqueness)
$K(A, n)$ always exists and is unique up to homotopy.

## Theorem (Representability of Cohomology)
There is a natural isomorphism:
$$[X, K(A, n)] \cong H^n(X; A)$$
where $[X, K(A, n)]$ denotes the set of homotopy classes of maps from $X$ to $K(A, n)$.

## Examples
- $S^1$ is a $K(\mathbb{Z}, 1)$.
- $\mathbb{CP}^\infty$ is a $K(\mathbb{Z}, 2)$.

## Sources
- [[01-raw-sources/week1.pdf]]
