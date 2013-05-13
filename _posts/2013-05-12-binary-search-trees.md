---
layout: post
title: "Binary Search Trees"
description: "BST"
category: computerscience
tags: [algorithms, c, datastructures, programming]
---
{% include JB/setup %}

Table of contents:  
[Brief History](#history)  
[References](#references)

# <a id="history"></a>Brief History
In 1736, Leonhard Euler's paper
*Solutio problematis ad geometriam situs pertinentis*
(*eng:* The solution of a problem relating to the geometry of position) was
published.
The paper described the famous problem of the
[Seven Bridges of Königsberg][1].
Put shortly, the problem was to find a walk through the city that would cross
each of the seven bridges only once. Euler proved in his paper that the problem
had no solution.
The paper is considered the first paper in graph theory (although the term
*graph* was not introduced until 1878, by the English mathematician James
Joseph Sylvester (Sylvester, 1878)) and Euler is therefore considered
the founder of graph theory (Biggs, Lloyd, Wilson, 1986).

[1]: https://en.wikipedia.org/wiki/Seven_Bridges_of_K%C3%B6nigsberg

More than a century after Euler's paper, British mathematician Arthur Cayley
started studying a particular class of graphs, namely trees. The term *tree*
was coined by Cayley himself in 1857 (Cayley, 1857).

# Graphs
Euler pointed out that it was only the order of which the bridges were crossed
that was relevant to solving the problem. By eliminating all factors except
the land masses and the bridges that connected them, we can model the problem
in a more abstract manner.

<div class="figure">
  <p><img class="scaled" src="/images/bst/Konigsberg_bridges.png"
      alt="The Seven Bridges of Königsberg">
  <p>Figure 1: The Seven Bridges of Königsberg. Copyright(C) Bogdan Giuşcă.
</div>

Figure 1 shows a map of Königsberg in around 1736,
highlighting the seven bridges. By drawing the land masses as simple circles,
and drawing lines between them to symbolize the edges, we end up with something
like Figure 2.

<div class="figure">
  <p><a href="/images/bst/konigsberggraph.tex"><img class="scaled" src="/images/bst/konigsberggraph.svg"
      alt="Graph of The Seven Bridges of Königsberg"></a>
  <p>Figure 2: A Graph of The Seven Bridges of Königsberg.
</div>

# <a id="references"></a>References
Biggs, N.; Lloyd, E. and Wilson, R. (1986), Graph Theory, 1736-1936, Oxford University Press  
Cayley, A. (1857), On the theory of the analytical forms called trees, Philosophical Magazine, 4th series, 13 : 172-176  
Sylvester, J. J. (1878), Chemistry and Algebra. Nature, volume 17, page 284.  
