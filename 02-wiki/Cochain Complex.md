Prerequisites: [[Homology]], [[Abelian Group]], [[Homomorphism]]

# Cochain Complex

## Definition
A **cochain complex** $C$ consists of:
- A collection of abelian groups $\{C^n\}_{n \in \mathbb{Z}}$
- A collection of homomorphisms $d^n: C^n \to C^{n+1}$ (called coboundary maps)

such that $d^{n+1} \circ d^n = 0$ for all $n$.

A **morphism of cochain complexes** $f: C \to D$ is a collection of homomorphisms $f^n: C^n \to D^n$ such that the following diagram commutes:
$$
\begin{array}{ccc}
C^n & \xrightarrow{d_C^n} & C^{n+1} \\
\downarrow{f^n} & & \downarrow{f^{n+1}} \\
D^n & \xrightarrow{d_D^n} & D^{n+1}
\end{array}
$$

## Cochain Homotopy
Let $f, g: C \to D$ be morphisms of cochain complexes. A **cochain homotopy** $s$ between $f$ and $g$ is a collection of homomorphisms $s^n: C^n \to D^{n-1}$ satisfying:
$$d_D^{n-1} s^n + s^{n+1} d_C^n = f^n - g^n$$
for all $n$.

## Sources
- [[01-raw-sources/week1.pdf]]
