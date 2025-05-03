## Dukaz:
Jednoznačnost limity

Dokažme spor. Předpokládejme, že posloupnost $(a_n)$ má dvě různé limity $K, L \in \mathbb{R}^*$.

Zvolíme $\varepsilon > 0$ tak malé, že $U(K, \varepsilon) \cap U(L, \varepsilon) = \emptyset$.

Z předpokladu, že $\lim_{n \to \infty} a_n = K$, plyne existence $n_0$ takového, že pro každé $n \geq n_0$ platí $a_n \in U(K, \varepsilon)$.

Analogicky, protože $\lim_{n \to \infty} a_n = L$, existuje $n_1$ takové, že pro každé $n \geq n_1$ platí $a_n \in U(L, \varepsilon)$.

Zvolme $n = \max\{n_0, n_1\}$. Pak by $a_n \in U(K, \varepsilon) \cap U(L, \varepsilon)$, což je spor.

Tedy limita je jednoznačná. 


#proof #lecture2 #posloupnost #limitaPosloupnosti 
[[Jednoznačnost limity]]