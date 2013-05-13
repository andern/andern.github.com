---
layout: post
title: "Binary Search Trees"
description: ""
category: computerscience
tags: [algorithms, c, datastructures, programming]
---
{% include JB/setup %}
# Brief History
In 1736, Leonhard Euler's paper
*Solutio problematis ad geometriam situs pertinentis*
(*eng:* The solution of a problem relating to the geometry of position) was
published.
The paper described the famous problem of the
[Seven Bridges of Königsberg](http://en.wikipedia.org/wiki/Seven_Bridges_of_K%C3%B6nigsberg).
Put shortly, the problem was to find a walk through the city that would cross
each of the seven bridges only once. Euler proved in his paper that the problem
had no solution. The paper is considered the first paper in graph theory
(although the term *graph* was not introduced until 1878, by the English
mathematician James Joseph Sylvester (Sylvester, 1878))
and Euler is therefore considered the founder of graph theory
(Biggs, Lloyd, Wilson, 1986).

More than a century after Euler's paper, British mathematician Arthur Cayley
started studying a particular class of graphs, namely trees. The term *tree*
was coined by Cayley himself in 1857 (Cayley, 1857).

# Test
    struct node {
        int data;
        struct node* left;
        struct node* right;
    };
Test syntax highlighting later.

Testing latex, how does it work? Just like this?
$x = 5$
Or not?
# References
Biggs, N.; Lloyd, E. and Wilson, R. (1986), Graph Theory, 1736-1936, Oxford University Press  
Cayley, A. (1857), On the theory of the analytical forms called trees, Philosophical Magazine, 4th series, 13 : 172-176  
Sylvester, J. J. (1878), Chemistry and Algebra. Nature, volume 17, page 284.  
