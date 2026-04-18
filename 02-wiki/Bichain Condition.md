---
subject: category-theory
---
# Bichain Condition
**Prerequisites:** [[Abelian Category]]

## Definitions
In an abelian category $\mathcal{A}$, a **bichain** is a collection of morphisms $X_n \xrightarrow{\alpha_n} X_{n+1} \xrightarrow{\beta_n} X_n$ for $n \in \mathbb{N}_0$.
An object $X \in \mathcal{A}$ satisfies the bichain condition if for every bichain with $X_0 = X$, both $\alpha_n$ and $\beta_n$ are invertible for $n \gg 0$.

## Theorems
- **(Atiyah)** Any object $X$ satisfying the bichain condition can be decomposed into a finite direct sum of indecomposable objects with local endomorphism rings.
- Any object in a finite length abelian category satisfies the bichain condition.
- Any object in a $k$-linear Hom-finite category (where $\dim_k \operatorname{Hom}(A,B) < \infty$) satisfies the bichain condition.

## Sources
- [[01-raw-sources/repr theory/lec2.pdf]]