# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

A one-to-one function would mean that every vertex in A would map to a unique vertex in B, 
and an onto function means that every vertex in B is mapped to by a vertex in A. Combining 
these functions, we get a bijection, where every vertex A is mapped to a unique vertex B, 
so that every vertex is mapped. 

If two graphs do not have the same number of nodes, there are two cases that can occur.

Case 1: 

Let graph A have less nodes than graph B. Then every vertex in A could map to a different 
vertex in B, however, since graph B has more vertices and each vertex in A can only map to a vertex in B once,
that means there would be at least one vertex in B that would not be mapped 
to by a vertex in A. This would violate the onto requirement, therefore violating the 
bijection function as stated in the definition of isomorphism. 

Case 2: 

Let graph A have more nodes than graph B. Then every vertex in B could be mapped to at least once
by the vertices in A. However, A would run out of new vertices to map to in A, requiring them to map
to the same vertices. This would then
violate the uniqueness requirement for a one-to-one function, therefore violating the bijection
function as stated in the definition of isomorphism. 

Therefore any two graphs A and B that do not have the same number of nodes (vertices) cannot be isomorphic
by definition. By definition, there must be an equal number of vertices in both graph A and
graph B for every vertex in A to map to a unique vertex in B without leaving any vertex out. 

### Plagiarism and Sources

https://www.mathsisfun.com/sets/injective-surjective-bijective.html, to provide context for one-to-one, onto, and bijection 

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.

