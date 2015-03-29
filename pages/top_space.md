---
title: "Topological space"
---

A **topology** on any set ``X`` is a collection ``\mathcal{T}`` of subsets of ``X`` that is

 - closed under arbitrary unions
 - closed under finite intersections
 - contains both ``\emptyset`` and ``X``.

The pair ``(X, \mathcal{T})`` is said to be a **topological space**. (Usually we abuse terminology and just say ``X`` is a topological space.)

The sets in the topology are said to be the **open subsets** of ``X``. A subset ``U \subseteq X`` is said to be a **neighborhood** of ``x \in X`` if both ``x \in U`` and ``U`` is open.

If you're trying to understand what the above definition of a topology *means*, stop trying and read what [Terence Tao has to say](http://mathoverflow.net/a/30231) about it:

 > ... a topology is really a package of several different structures: the notion of openness, the notion of closedness, the notion of neighbourhoods, the notion of convergence, the notion of continuity, the notion of a homeomorphism, the notion of a homotopy, and so forth. They are all important, and it is somewhat artificial to try to designate one of them as being more "fundamental" than the other. But the notion of openness happens to generate all the other notions, and has a particularly elegant and simple axiomatisation, so we have elected to make it the basis for the standard minimalist definition of a topology. But it is important to realise that this is by no means the only way to define a topology, and adopting a more package-oriented point of view can be preferable in some cases (for instance, when generalising the notion of a topology to more abstract structures, such as topoi, in which open sets no longer are the most convenient foundation to begin with).


## Subsets of spaces

See: [Facts_about subsets of topological spaces](top_subsets.html)

## Bases

TODO

## Continuous maps

One of the major reasons for studying topological spaces is for studying continuous maps. Here are some notes on continuous maps: TODO


## Different kinds of spaces {#Kinds}

 - **``T_1`` space**: For any pair of distinct points ``a, b`` in the space, ``a`` has a neighborhood ``U`` that does not contain ``b``, and similarly ``b`` has a neighborhood ``V`` that does not contain ``a``.
 - **Hausdorff space**: Any pair of distinct points ``a, b`` in the space have neighborhoods ``U`` and ``V``, respectively, that are disjoint.
 - **first-countable space**: Every point has a countable neighborhood basis.
 - **second-countable space**: The topology has a countable basis that induces it.
