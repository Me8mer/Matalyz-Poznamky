## Definice: 

Nechť $A, B \in \mathbb{R}$, kde $A < B$. Funkce $f : (A, B) \to \mathbb{R}$ má na intervalu $(A, B)$ **Newtonův integrál**, pokud:

- má na $(A, B)$ **primitivní funkci** $F$,
- a tato funkce má vlastní **jednostranné limity**:

  $$
  F(A^+) = \lim_{x \to A^+} F(x), \quad
  F(B^-) = \lim_{x \to B^-} F(x)
  $$

Definujeme symbol:

$$
[F]_A^B := F(B^-) - F(A^+)
$$

A samotný Newtonův integrál:

$$
\int_A^B f(x)\ dx := [F]_A^B = \lim_{x \to B^-} F(x) - \lim_{x \to A^+} F(x)
$$

Poznámka:

> Protože každé dvě primitivní funkce se liší jen o aditivní konstantu, rozdíl $F(B^-) - F(A^+)$ je dobře definován.

Třídu všech funkcí, které mají Newtonův integrál na $(A, B)$, značíme:

$$
\mathcal{N}(A, B) = \{ f : f \text{ má na } (A, B) \text{ Newtonův integrál} \}
$$




#definition #lecture10 #urcityIntegral #NewtonovIntegral

