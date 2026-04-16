Prerequisites: [[Projective Object]], [[Abelian Category]]

# Projective Cover

In the context of representation theory and homological algebra, a **projective cover** is a way to "approximate" an object by a projective object in a minimal way.

## Definition

Let $\mathcal{A}$ be an abelian category (or more generally, a category where the following makes sense). A **projective cover** of an object $X \in \mathcal{A}$ is a pair $(P, \phi)$ where:
1. $P$ is a [[Projective Object]].
2. $\phi: P \to X$ is an **essential epimorphism**.

### Essential Epimorphism
An epimorphism $\phi: P \to X$ is **essential** (or superfluous) if for any morphism $\alpha: Q \to P$, the condition that $\phi \circ \alpha$ is an epimorphism implies that $\alpha$ is an epimorphism. 

In the category of modules over a ring, this is equivalent to saying that the kernel of $\phi$ is a **superfluous submodule** of $P$, i.e., $\ker(\phi) + K = P$ implies $K = P$ for any submodule $K \subseteq P$.

## Properties

### Characterization (Lemma 1.4)
A morphism $\phi: P \to X$ with $P$ projective is a projective cover if and only if for any endomorphism $\alpha: P \to P$, the condition that $\phi \circ \alpha$ is an epimorphism implies that $\alpha$ is an isomorphism.

### Uniqueness
If an object $X$ has a projective cover, it is unique up to isomorphism. Specifically, if $(P, \phi)$ and $(P', \phi')$ are two projective covers of $X$, there exists an isomorphism $h: P \to P'$ such that $\phi' \circ h = \phi$.

### Indecomposability
If $L$ is a [[Simple Object]] (irreducible), then its projective cover $P(L)$, if it exists, is an **indecomposable** projective object.

### Bijection Theorem (Theorem 1.3)
In an abelian category of finite length, there is a bijection:
$$\text{isomorphism classes of indecomposable projective objects} \leftrightarrow \text{isomorphism classes of simple objects}$$
The bijection is given by $P \mapsto P/\text{rad}(P)$, where $P/\text{rad}(P)$ is simple, and $L \mapsto P(L)$, its projective cover.

## Examples
- **$R = \mathbb{C}[x]/(x^2)$**: Let $\mathbb{C}$ be the 1-dim irreducible module (where $x$ acts as 0). There is a non-split sequence $0 \to \mathbb{C} \to R \xrightarrow{\phi} \mathbb{C} \to 0$. Here $(R, \phi)$ is the projective cover of $\mathbb{C}$.
- In the category of finite-dimensional modules over a finite-dimensional algebra $A$, every object has a projective cover.
- In the category of graded modules over a graded algebra, projective covers exist and are compatible with the grading.

## Sources
- [[01-raw-sources/repr theory/lec1.pdf]]
- [[01-raw-sources/repr theory/lec1_1sthalf.txt]]
- [[01-raw-sources/repr theory/lec1_2ndhalf.txt]]
