Prerequisites: [[Topology]], [[Homotopy Group]]

# Mapping Space

## Definition
The space of continuous maps $\text{map}(X, Y) := \{f: X \to Y \text{ continuous}\}$ is typically equipped with the **compact-open topology**.

## Theorem
If $X$ is locally compact, then the evaluation map $\text{map}(X, Y) \times X \to Y$ given by $(f, x) \mapsto f(x)$ is continuous.
Furthermore, for any space $Z$, there is a bijection:
$$\{g: Z \to \text{map}(X, Y) \text{ cont}\} \leftrightarrow \{g^\wedge: Z \times X \to Y \text{ cont}\}$$

## Loop Space
The **loop space** of a pointed space $(Y, y_0)$ is defined as:
$$\Omega Y = \text{map}_*(S^1, Y)$$
where $\text{map}_*$ denotes pointed maps.

## Theorem
There is an isomorphism:
$$\pi_n(\Omega Y, c_{y_0}) \cong \pi_{n+1}(Y, y_0)$$
where $c_{y_0}$ is the constant loop at $y_0$. This property is "dual" to suspension.

## Sources
- [[01-raw-sources/topology2/week1.pdf]]
