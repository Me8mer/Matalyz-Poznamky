## Důkaz – Lagrangeova věta

Zaveďme pomocnou funkci:
$$
p(x) := f(A) + (x - A) \cdot \frac{f(B) - f(A)}{B - A}
$$

Tato funkce $p$ je přímka procházející body $(A, f(A))$ a $(B, f(B))$ – má tedy směrnici průměrné změny funkce $f$.

Definujme funkci:
$$
h(x) := f(x) - p(x)
$$

Chceme použít **Rolleovu větu** na $h$.

- Funkce $h$ je spojitá na $[A, B]$, protože je rozdílem dvou spojitých funkcí
- Má derivaci na $(A, B)$
- Navíc:
  $$
  h(A) = f(A) - p(A) = 0,\quad h(B) = f(B) - p(B) = 0
  $$

Tedy platí předpoklady [[Rolleova věta]] (Rolle), a tak existuje $C \in (A, B)$, pro které platí:
$$
h'(C) = 0
$$

Spočítáme derivaci:
$$
h'(x) = f'(x) - \frac{f(B) - f(A)}{B - A}
$$

Takže:
$$
0 = h'(C) = f'(C) - \frac{f(B) - f(A)}{B - A}
\Rightarrow
f'(C) = \frac{f(B) - f(A)}{B - A}
$$


#proof #lecture8 #funkce  #derivace
[[Lagrangeova věta o střední hodnotě]]