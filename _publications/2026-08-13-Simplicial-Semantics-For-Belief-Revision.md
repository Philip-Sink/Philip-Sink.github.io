---
title: "Simplicial Semantics for Belief Revision"
collection: publications
category: prepublications
permalink: /publication/2026-08-13-Simplicial-Semantics-For-Belief-Revision
excerpt: 'This paper will give a definition of belief revision within simplicial semantics. Starting from the work presented in "A Semantics for Belief in Simplicial Complexes" as a baseline, this paper modifies the semantics for belief given there to allow atomic formulae to be assigned to nodes, not facets. Conceptually and philosophically, this version of the semantics is better suited if one wishes to interpret the nodes of a simplicial model of epistemic logic as a "perspective" assigned to a particular agent. If nodes are perspectives, it then follows that worlds, or the facets of a simplicial model, are composed themselves of perspectives. This allows us to say that two worlds are more similar, or "nearer", if they share more perspectives. With this conceptual notion of nearness in hand, two different formal presentations of revision are given. We conclude by exploring some conceptual pitfalls surrounding these definitions under iterated revision, and motivate a few potential solutions that involve giving the agents a "memory" of what has been announced so far. '
date: 2026-08-13
venue: 'arXiv'
slidesurl: 
paperurl: 'https://arxiv.org/abs/2608.13763'
bibtexurl: 'https://arxiv.org/abs/2608.13763'
citation: 'Philip Sink (2026). &quot;Simplicial Semantics for Belief Revision&quot; <i>arXiv</i> '
---
<p>If you've ever wondered why philosophers should care about simplicial semantics for modal logic, here is my answer! In this paper I show that simplicial semantics offers a nice implementation of belief revision à la Lewis. The basic idea is that, because simplicial semantics does not take worlds as foundational objects, worlds themselves have more "structure" that we can exploit. In particular, worlds are made up of "local states" of individual agents, and worlds sharing a particular agent's local state is how we model an agent being "uncertain" between the two worlds.</p>

<p>Building on the work [here](arxiv.org/abs/2512.14647), the insight in this new paper was to use these local states also to model "nearness"; if two worlds share more local states, we say that they are nearer or more similar! This makes sense for the following reason: Worlds are composed of local states, hence having more local states in common makes two worlds more similar. The implementation of revision hence leverages a kind of "trust" between the agents. Agents revise to worlds that preserve as many of their fellow agents' local states as possible. This paper explores the philosophical dimensions of this, as well as proposes new directions one could take this work on this basis.</p>
