**Dukaz**:
Předpokládejme, že $A \in \mathbb{R}$ a že $f$ je neklesající na nějakém levém prstencovém okolí $P^-(A, \delta_0) = (A - \delta_0, A)$.

Označme:
$$
S = \sup f(P^-(A, \delta_0))
$$

Chceme dokázat, že:
$$
\lim_{x \to A^-} f(x) = S
$$

Nechť $\varepsilon > 0$.

Zvolme $D \in U(S, \varepsilon)$ takové, že $D < S$. Jelikož $D$ není horní mez $f(P^-(A, \delta_0))$, existuje $x_0 \in P^-(A, \delta_0)$ takové, že $f(x_0) > D$.

Protože $f$ je neklesající, pak pro všechna $x \in (x_0, A)$ platí:
$$
f(x) \geq f(x_0) > D
$$

Současně, z definice supremum platí, že $f(x) \leq S$ pro všechna $x$.

Tedy:
$$
f(P^-(A, \delta)) \subseteq U(S, \varepsilon)
$$
pro $\delta = A - x_0$.

Tím je dokázáno, že $\lim_{x \to A^-} f(x) = S$.



#proof #lecture5 #funkce  #limita  
[[X -Limita monotónní funkce]]