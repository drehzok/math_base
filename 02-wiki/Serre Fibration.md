Prerequisites: [[Homotopy Group]], [[Fibration]]

# Serre Fibration

## Definition
A map $p: E \to B$ is a **Serre fibration** if it has the homotopy lifting property with respect to every CW complex $X$. That is, for every map $H: X \times I \to B$ and map $h: X \times \{0\} \to E$ such that $p \circ h = H|_{X \times \{0\}}$, there exists a lift $\tilde{H}: X \times I \to E$ such that $p \circ \tilde{H} = H$ and $\tilde{H}|_{X \times \{0\}} = h$.

## Theorem (Long Exact Sequence of Homotopy Groups)
If $p: E \to B$ is a Serre fibration with fiber $F = p^{-1}(b)$ for some $b \in B$, then there is a long exact sequence:
$$\dots \to \pi_n(F, x) \to \pi_n(E, x) \to \pi_n(B, p(x)) \xrightarrow{\partial} \pi_{n-1}(F, x) \to \dots$$

## Corollary (Hopf Fibration)
For $n=1$, the fibration $S^3 \xrightarrow{S^1} S^2$ (the Hopf map $\eta: S^3 \to S^2$) induces an isomorphism $\pi_k(S^3) \cong \pi_k(S^2)$ for $k \geq 3$.
In particular, $\pi_3(S^2) \cong \mathbb{Z}$ with generator $\eta$.

## Sources
- [[01-raw-sources/week1.pdf]]
