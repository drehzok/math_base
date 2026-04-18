---
subject: topology
---
Hub: [[Cohomology (Hub)]]

# Singular Cohomology
**Prerequisites:** [[Cohomology (Hub)]], [[Homology (Hub)]], [[Cochain Complex]]

## Definitions
For $Y \in sSet$ and $A$ an abelian group, the cohomology of $Y$ is defined as $H^n(Y; A) = H^n(\operatorname{Hom}(C(Y; \mathbb{Z}), A))$.
If $X$ is a space, $H^n(X; A) = H^n(\rho(X); A)$.

## Theorems
### Homotopy Invariance
If $f \simeq g: X \to Y$, then $H^n(f, A) = H^n(g, A)$.

### Excision
For an excisive triple $(X, L, U)$, the inclusion induces an isomorphism $H^n(X, L; A) \cong H^n(X \setminus U, L \setminus U; A)$.

## Sources
- [[01-raw-sources/topology2/week1.pdf]]