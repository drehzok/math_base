Prerequisites: [[Cohomology]], [[Homology]], [[Manifold]]

# Poincare Duality

## Theorem
Let $M$ be a compact $n$-dimensional manifold. Then:
$$H^{n-i}(M; \mathbb{F}_2) \cong H_i(M; \mathbb{F}_2)$$
This isomorphism $\varphi$ is given by the **cap product** with a fundamental class $\mu_M \in H_n(M; \mathbb{F}_2)$.

## Corollary
If $M$ is connected, then $H^n(M; \mathbb{F}_2) \cong H_0(M; \mathbb{F}_2) \cong \mathbb{F}_2$.
The map:
$$H^i(M; \mathbb{F}_2) \times H^{n-i}(M; \mathbb{F}_2) \to \mathbb{F}_2$$
$$(x, y) \mapsto \varphi(x \smile y)$$
is a **non-degenerate bilinear form**. It induces an isomorphism:
$$H^{n-i}(M; \mathbb{F}_2) \to \text{Hom}(H^i(M; \mathbb{F}_2), \mathbb{F}_2)$$

## Example: $H^*(\mathbb{RP}^2; \mathbb{F}_2)$
Using non-degeneracy, for $x \in H^1(\mathbb{RP}^2; \mathbb{F}_2)$ with $x \neq 0$, we have $x \smile x \neq 0$.
This implies $H^*(\mathbb{RP}^2; \mathbb{F}_2) \cong \mathbb{F}_2[x] / (x^3)$.

## Sources
- [[01-raw-sources/week1.pdf]]
