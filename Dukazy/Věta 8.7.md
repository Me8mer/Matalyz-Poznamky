## Důkaz 

Podle definice pravostranné derivace:
$$
f'_+(A) = \lim_{x \to A^+} \frac{f(x) - f(A)}{x - A}
$$

**Ověření podmínek pro l’Hospitalovo pravidlo:**
- $\lim_{x \to A^+} f(x) = f(A)$ ⇒ čitatel $\to 0$
- $\lim_{x \to A^+} (x - A) = 0$
- Funkce $f$ je spojitá zprava, tedy spojitá na $[A, B)$
- Derivace v okolí bodu $A$ existují:  
  $(f(x) - f(A))' = f'(x)$ a $(x - A)' = 1$

Použijeme l’Hospitalovo pravidlo:
$$
f'_+(A) = \lim_{x \to A^+} \frac{f'(x)}{1} = \lim_{x \to A^+} f'(x) = L
$$

#proof #lecture8 #funkce  #derivace
[[Spojitost derivace v krajním bodě]]