Prerequisites: [[Cohomology]]

# Cup Product

## Definition
If $A$ is a ring, the cohomology $H^*(X; A) = \bigoplus_n H^n(X; A)$ has the structure of a **graded ring**. The multiplication is given by the **cup product**:
$$\smile: H^m(X; A) \times H^n(X; A) \to H^{m+n}(X; A)$$

## Properties
- The cup product is natural: $f^*(x \smile y) = f^*(x) \smile f^*(y)$.
- It is compatible with induced maps $f^*$.

## Examples
1. **Real Projective Space**: $H^*(\mathbb{RP}^n; \mathbb{F}_2) \cong \mathbb{F}_2[x] / (x^{n+1})$ where $x \in H^1(\mathbb{RP}^n; \mathbb{F}_2)$.
2. **Complex Projective Space**: $H^*(\mathbb{CP}^n; \mathbb{Z}) \cong \mathbb{Z}[x] / (x^{n+1})$ where $x \in H^2(\mathbb{CP}^n; \mathbb{Z})$.

## Corollary
$\mathbb{CP}^2 \not\simeq S^2 \vee S^4$. 
*Proof*: $H^2$ of the wedge comes from $S^2$, so it can't generate $H^4$ which comes from $S^4 \to 0$. But $x^2 \neq 0$ for some $x \in H^2(\mathbb{CP}^2)$.

## Sources
- [[01-raw-sources/topology2/week1.pdf]]
