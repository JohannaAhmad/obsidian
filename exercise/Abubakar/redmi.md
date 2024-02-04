## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Abubakar ->> Mihran: Hello Mihran, how are you?
Mihran-->>John: How about you John?
Mihran--x Abubakar: I am good thanks!
Mihran-x John: I am good thanks!
Note right of John: Mihran thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Mihran-->Abubakar: Checking with John...
Abubakar->John: Yes... John, how are you?
