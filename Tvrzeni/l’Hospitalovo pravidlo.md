## Věta: 
Nechť $A \in \mathbb{R}^*$, nechť $P(A, \delta)$ je nějaké prstencové okolí bodu $A$, a nechť $f, g : P(A, \delta) \to \mathbb{R}$ mají na $P(A, \delta)$ vlastní derivace. Nechť $g'(x) \ne 0$ pro všechna $x \in P(A, \delta)$.

Předpokládejme, že existuje (ne nutně vlastní) limita:
$$
L = \lim_{x \to A} \frac{f'(x)}{g'(x)} \in \mathbb{R}^*
$$

Potom platí:

1. Pokud $\lim_{x \to A} f(x) = \lim_{x \to A} g(x) = 0$, pak:
$$
\lim_{x \to A} \frac{f(x)}{g(x)} = L
$$

2. Pokud $\lim_{x \to A} |g(x)| = +\infty$, pak:
$$
\lim_{x \to A} \frac{f(x)}{g(x)} = L
$$

Pravidlo platí obdobně pro jednostranné limity $x \to A^+$ nebo $x \to A^-$, při použití jednostranných okolí $P^+(A, \delta)$ nebo $P^-(A, \delta)$, přičemž derivace $f$ a $g$ zůstávají oboustranné.



#theorem #lecture8 #derivace 
[[]]