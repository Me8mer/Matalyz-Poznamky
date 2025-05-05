## Věta: 

Předpokládejme, že $f(A) < 0 < f(B)$ (druhý případ je analogický).

Definujme množinu $Z = \{x \in [A, B] \mid f(x) < 0\}$. Tato množina je neprázdná ($A \in Z$) a shora omezená (např. horní mez $B$).

Označme $S = \sup Z$. Zjevně $S \in [A, B]$.

Ukážeme, že $f(S) = 0$.

**Spor 1:** Předpokládejme, že $f(S) > 0$. Jelikož $S \in (A, B]$, $f$ je spojitá zleva. Tedy existuje $\delta > 0$ takové, že $f(x) > 0$ pro $x \in (S - \delta, S)$.

To znamená, že žádné $x$ z intervalu $(S - \delta, S)$ nepatří do $Z$, tedy $S - \delta$ je horní mez $Z$, což je spor s tím, že $S$ je supremum.

**Spor 2:** Předpokládejme, že $f(S) < 0$. Potom $S \in [A, B)$, tedy $f$ je spojitá zprava. Opět existuje $\delta > 0$ takové, že $f(x) < 0$ pro $x \in (S, S + \delta)$.

Ale to znamená, že existují $x > S$ s $f(x) < 0$, a tedy $x \in Z$, což je spor s tím, že $S$ je supremum $Z$.

Oba spory vedou k závěru, že $f(S) = 0$.



#proof #lecture5 #funkce  #limita
[[Bolzanova věta]]