# Důkaz věty 1.5 – Nespočetnost $\mathbb{R}$

Předpokládejme pro spor, že existuje prostá funkce $f : \mathbb{R} \to \mathbb{N}$.
*Sestrojeni prostej posloupnosti*
Sestrojíme posloupnost reálných čísel $g(1), g(2), \dots$ takto:

- Pokud pro dané $n \in \mathbb{N}$ existuje $x \in \mathbb{R}$ takové, že $f(x) = n$, pak definujeme $g(n) = x$.
- Pokud žádné takové $x$ neexistuje (tedy $n$ nepatří do obrazu funkce $f$), nechť $g(n) = 0$.

Tím získáme posloupnost $(g(n))_{n=1}^{\infty}$, která podle předpokladu obsahuje všechna reálná čísla.
*Sestrojeni alfa*
Nyní zkonstruujeme reálné číslo $\alpha$, které v této posloupnosti není.

Nechť $a_n$ je $n$-tá cifra za desetinnou čárkou čísla $g(n)$ (v jeho desetinném rozvoji; v případě dvou různých reprezentací zvolíme libovolně jednu).

Definujeme $b_n$ jako nejmenší nenulovou číslici, která se liší od $a_n$ (např. 1 nebo 2, aby se předešlo nejednoznačnosti).

Potom definujeme číslo:
$$
\alpha = 0,b_1 b_2 b_3 \dots
$$

Tento desetinný rozvoj je jednoznačný (neobsahuje nuly ani devítky).
*Spor*
Pro spor předpokládejme, že existuje $n \in \mathbb{N}$ takové, že $\alpha = g(n)$. Pak má $\alpha$ a $g(n)$ shodný jednoznačný desetinný rozvoj.

Ale jejich $n$-tá cifra za desetinnou čárkou se liší: $a_n \ne b_n$, což je spor.

Tedy $\alpha$ není v posloupnosti $(g(n))$, a tudíž $f$ nemůže být prosté zobrazení $\mathbb{R} \to \mathbb{N}$.

Z toho plyne, že množina $\mathbb{R}$ není spočetná.



#proof #lecture1 #uvod #R 
[[Tvrzeni/R|R]]