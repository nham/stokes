---
title: "Topological Manifold"
---

## Locally Euclidean spaces {#Locally_Euclidean}

A [topological space][top_space] ``X`` is said to be **locally Euclidean of dimension ``n``** if every point ``x \in X`` has a neighborhood ``U`` such that there is a homeomorphism ``\phi: U \to V``, where ``V`` is an open subset of ``\mathbb{R}^n``.

Let us make a few definitions. A pair ``(U, \phi)`` where

 - ``U`` is an open subset of ``X``
 - ``\phi`` is a homeomorphism of ``U`` with some open subset of ``\mathbb{R}^n``

is called a **chart**. ``\phi`` is a **coordinate map**, and we call ``U`` a **coordinate domain**, a **coordinate neighborhood**, and/or a **coordinate patch**.

A chart ``(U, \phi)`` is said to be **centered** at ``p \in U`` if ``\phi(p) = 0``. For any chart and any point ``p`` in the coordinate domain, we can create a chart centered at ``p`` (compose the coordinate map with a transposition map, which is always a homeomorphism).

Each coordinate map ``\phi`` is a kind of *local coordinate system* on ``U``.

We can now say that a space is locally Euclidean iff there is a collection of charts on ``X`` whose coordinate domains cover ``X``.


### Equivalent definitions

In the definition of "locally Euclidean" it is possible to replace "open subset of ``\mathbb{R}^n``" with "open ball in ``\mathbb{R}^n``" or with "``\mathbb{R}^n``" itself. To see why this is so, you might find these facts useful (and may want to prove them):

 - any two open balls in ``\mathbb{R}^n`` are homeomorphic
 - the unit open ball ``\mathbb{B}^n`` in ``\mathbb{R}^n`` is homeomorphic to ``\mathbb{R}^n`` itself.
 - if ``(U, \phi)`` is a chart mapping onto an open subset of ``\mathbb{R}^n``, you can find a restriction of ``\phi`` whose image is an open ball in ``\mathbb{R}^n``



## Topological manifold {#Manifold}

An ``n``-dimensional topological manifold is any [topological space][top_space] ``X`` that is

 - [second countable][kinds]
 - [Hausdorff][kinds]
 - locally Euclidean of dimension ``n``

## Properties

 - locally path-connected
 - locally compact
 - paracompact
 - has countably many components, each being open and therefore a submanifold

TODO

## Examples

### ``\mathbb{R}^n``

``\mathbb{R}^n`` itself is an ``n``-manifold. It is Hausdorff because it is a metric space, and it is second-countable since it is a separable metric space. The chart ``(\mathbb{R}^n, id)`` (where the coordinate map is the identity mapping on ``\mathbb{R}^n``) establishes it is locally Euclidean.

### Open submanifolds

Any subspace of a manifold is both second-countable and Hausdorff (since these properties are preserved by subspaces). If the subspace is additionally an open subset of the manifold, then the subspace will be locally Euclidean as well. Hence an open subset of any manifold is a manifold, which we call **open submanifolds**.

### Homeomorphic spaces

The properties of being second-countable, Hausdorff, and locally Euclidean are all *topological properties*, meaning they are preserved by homeomorphism. So any space homeomorphic to a manifold is itself a manifold.

### Graphs of continuous functions

TODO

### ``n``-spheres

TODO

### Product manifolds

Any product of manifolds ``X_1, \ldots, X_k`` is both second-countable and Hausdorff (since these properties are preserved by product spaces). Furthermore, the product of locally Euclidean spaces is locally Euclidean, so the product of manifolds is a manifold.

[top_space]: top_space.html
[kinds]: top_space.html#Kinds
