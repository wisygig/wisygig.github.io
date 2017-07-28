---
layout: post
title:  "Singular Value Decomposition"
categories: algebra notes
---

Suppose that $$V$$ and $$W$$ are finite dimensional vector spaces over a field $$\mathbb{K}$$, and let $$T: V \to W$$ be a linear transformation.

If $$V$$ and $$W$$ are equipped with an inner product, we can choose an orthonormal bases for each vector space, equivalently we can choose a linear isometry with $$\mathbb{K}^n$$ and $$\mathbb{K}^m$$.

With respect to the choice of basis, we can now write $$T$$ as an $$m \times n$$ matrix $$M$$.


consider the variational proof instead?

**Theorem:** There exists a factorization
$$M = U \Sigma V^*$$
where
* $$\Sigma$$ is a diagonal $$ m \times n$$ matrix with real non-negative entries, and
* $$U, V$$ are unitary matrices.

**Proof**: Consider the bilinear form $$B: U \times V \to \mathbb{K}$$ given by $$B(u, v) = v^*Mu$$.
If we restrict $$B$$ to $$S(U) \times S(V)$$, then either $$B$$ is constant, or there exists a unique maximum value.

Applying lagrange multipliers, yadda
