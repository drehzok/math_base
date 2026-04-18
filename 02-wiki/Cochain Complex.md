---
subject: hom-alg
dual: "[[Chain Complex]]"
---
# Cochain Complex
**Prerequisites:** [[Abelian Group]]

## Definitions
A **cochain complex** $C$ consists of abelian groups $C^n$ and homomorphisms $d^n: C^n \to C^{n+1}$ such that $d^{n+1} \circ d^n = 0$.

The $n$-th cohomology group is defined as $H^n C = \frac{\ker d^n}{\operatorname{im} d^{n-1}}$.

## Sources
- [[01-raw-sources/topology2/week1.pdf]]