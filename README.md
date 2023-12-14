[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=13164468&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Two graphs that don't have the same number of nodes cannot be isomorphic because a bijective function could not exist. In order to have a bijective function each element of set A has to be paired with an element of set B and vice versa. The elements in set A can't be paired with more than one element of set B and vice versa. If $|V_1|<|V_2|$ there must be at least at least one element in $V_2$ that isn't mapped to any element that exists in $V_1$. This directly contradicts the definiton of a bijection and therefore if graphs A and B don't have the same number of nodes they can't be isomorphic.