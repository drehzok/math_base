Prerequisites: [[Cochain Complex]]

# Cohomology

## Definition
For a cochain complex $C$, the **$n$-th cohomology group** $H^n C$ is defined as the quotient:
$$H^n C = \frac{\ker d^n}{\text{im } d^{n-1}}$$
The elements of $\ker d^n$ are called **cocycles**, and the elements of $\text{im } d^{n-1}$ are called **coboundaries**.

## Theorem (Induced Maps)
A cochain map $f: C \to D$ induces homomorphisms $H^n f: H^n C \to H^n D$ defined by $[x] \mapsto [f^n(x)]$.
- Cochain homotopic maps induce the same map on cohomology groups.

## Theorem (Long Exact Sequence)
Every short exact sequence (SES) of cochain complexes $0 \to A \xrightarrow{f} B \xrightarrow{g} C \to 0$ gives rise to a **long exact sequence (LES)** in cohomology:
$$\dots \to H^n A \xrightarrow{H^n f} H^n B \xrightarrow{H^n g} H^n C \xrightarrow{\partial} H^{n+1} A \to \dots$$
where $\partial[x] = [y]$ is the connecting homomorphism.

## Sources
- [[01-raw-sources/week1.pdf]]
