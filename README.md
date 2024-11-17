# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.


## Answer

We have to prove that isomorphic graphs do not have to be connected. 

Let's consider we have two graphs $C and D$. Graph $C$ has vertices (A, B, and C) and graph $D$ has vertices (D, E, and F). The edges for Graph $C$ are (A and B) and (B and C). The edges for Graph $D$ are (D and E) and (E and F). 

Using the statement we have above for the bijection function $f: V_1 \rightarrow V_2$. This will make $f(A) = D, f(B) = E, and f(C) = F$. This will satisfy the one-to-one and onto (bijection) functions for isomorphism.

With that, we also have for every edge $(u,v) \in E_1$, there is a corresponding edge $(f(u),f(v)) \in E_2$. With this in mind, we can say that $(A, B) \in E_1$ aligns with $(D, E) \in E_2$. This demonstrates isomorphism.

Since both graph $A$ and graph $B$ are not fully connected, with two nodes connected and the nodes not connected it will pass the test.

## Sources

I looked at rmille70's repo after I had finished this to see if I did it right. Which it looks like I did. I just dif not use as many nodes and edges he did.

## Plagarism Statement
“I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.”

