## Důkaz

Chceme dokázat, že $\lim_{x \to A} f(x) = f(A)$.

Spočítáme:

$$
\lim_{x \to A} f(x) = \lim_{x \to A} \left( f(x) - f(A) + f(A) \right)
= \lim_{x \to A} \left( \frac{f(x) - f(A)}{x - A} \cdot (x - A) + f(A) \right)
$$

$$
= f'(A) \cdot \lim_{x \to A} (x - A) + f(A) = f'(A) \cdot 0 + f(A) = f(A)
$$

Tedy $f$ je v bodě $A$ spojitá.



#proof #lecture7 #funkce  #derivace
[[Spojitost diferencovatelne funkce]]