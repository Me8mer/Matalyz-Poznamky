## Věta: 
*Predpoklady*
Monotónní posloupnost má limitu

Předpokládejme, že posloupnost $(a_n)$ je slabě rostoucí.

Označme $s = \sup \{a_n \,|\, n \in \mathbb{N}\}$. Tvrdíme, že $\lim_{n \to \infty} a_n = s$.
*Spor*
Pro spor předpokládejme, že limita neexistuje, tedy existuje $\varepsilon > 0$ takové, že pro nekonečně mnoho $n$ platí $a_n \notin U(s, \varepsilon)$.

Tedy $a_n < s - \varepsilon$ pro nekonečně mnoho $n$.

Avšak $(a_n)$ je slabě rostoucí, tedy všechny další členy posloupnosti jsou menší než $s - \varepsilon$.

To znamená, že $s - \varepsilon$ je horní mez množiny $\{a_n\}$, což je spor s tím, že $s$ je nejmenší horní mez.

Tedy $\lim_{n \to \infty} a_n = s \in \mathbb{R}^*$.


#proof #lecture2 #posloupnost #limitaPosloupnosti 
[[Limita monotónní posloupnosti]]