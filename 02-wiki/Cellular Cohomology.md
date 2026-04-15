Prerequisites: [[CW Complex]], [[Cohomology]], [[Homology]]

# Cellular Cohomology

## Definition
For a CW complex $X$, the **cellular cochain complex** is defined as:
$$C^*_{\text{cell}}(X; A) := \text{Hom}(C_*^{\text{cell}}(X; \mathbb{Z}), A)$$
where $C_*^{\text{cell}}(X; \mathbb{Z})$ is the cellular chain complex, with $C_n^{\text{cell}}(X; \mathbb{Z}) = H_n(X_n, X_{n-1}; \mathbb{Z})$.

## Theorem
The cohomology of the cellular cochain complex is naturally isomorphic to the singular cohomology of $X$:
$$H^n(C^*_{\text{cell}}(X; A)) \cong H^n(X; A)$$

## Sources
- [[01-raw-sources/week1.pdf]]
