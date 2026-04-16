Prerequisites: [[Cohomology]], [[Chain Complex]], [[Simplicial Set]]

# Simplicial Cohomology

## Definition
Let $Y \in \text{sSet}$ be a simplicial set and $A$ be an abelian group. The **cohomology of $Y$ with coefficients in $A$** is defined as:
$$H^n(Y, A) = H^n(\text{Hom}(C(Y; \mathbb{Z}), A))$$
where $C(Y; \mathbb{Z})$ is the chain complex associated with the simplicial set.

For a topological space $X$, we write:
$$H^n(X; A) = H^n(P(X); A)$$
where $P(X)$ is the singular simplicial set of $X$.

## Relative Cohomology
For a sub-simplicial set $Y' \subset Y$, the **relative cohomology** is:
$$H^n(Y, Y'; A) = H^n(\text{Hom}(C(Y; \mathbb{Z})/C(Y'; \mathbb{Z}), A))$$

## Key Properties
1. **Homotopy Invariance**: If $f \simeq g: X \to Y$, then $H^n(f, A) = H^n(g, A)$.
2. **Excision**: For an excisive triple $(X, Y, U)$, the inclusion $(X \setminus U, Y \setminus U) \hookrightarrow (X, Y)$ induces an isomorphism:
   $$H^n(X, Y; A) \cong H^n(X \setminus U, Y \setminus U; A)$$

## Sources
- [[01-raw-sources/topology2/week1.pdf]]
