---
title: "Smooth Manifold"
---

Recall that for any [topological manifold](top_manifold.html) ``X``, two [charts](top_manifold.html#Locally_Euclidean) ``(U, \phi)`` and ``(V, \psi)`` on ``X`` are said to be **smoothly compatible** if either:

 - ``U`` and ``V`` are disjoint
 - ``\phi \circ \psi^{-1}``, called the **transition map from ``\psi`` to ``\phi``**, is a diffeomorphism ``\psi(U \cap V) \to \phi(U \cap V)``, where ``\psi(U \cap V)`` and ``\phi(U \cap V)`` are open subsets of ``\mathbb{R}^n``.

An **atlas** on a manifold is a collection of charts whose coordinate domains cover the manifold. An atlas is said to be **smooth** if all its charts are smoothly-compatible with one another.

When trying to prove that some atlas is smooth, it suffices to prove that all transition maps are smooth.

An atlas ``\mathcal{A}`` is called **maximal** if there is no atlas that contains ``\mathcal{A}`` as a proper subcollection. A topological manifold ``X`` is said to have **smooth structure** ``\mathcal{A}`` if ``\mathcal{A}`` is a maximal smooth atlas for ``X``.

A **smooth manifold** is a pair ``(X, \mathcal{A})`` where ``X`` is a topological manifold and ``\mathcal{A}`` is a smooth structure (maximal smooth atlas). Of course, the **dimension** of a smooth manifold is just the dimension of the underlying topological manifold. A chart ``(U, \phi)`` in the smooth structure is called a **smooth chart**, and the map ``\phi`` is called the **smooth coordinate map**. The set ``U`` is called a **smooth coordinate domain** or **smooth coordinate neighborhood** or **smooth coordinate patch**.
