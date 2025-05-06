## Důkaz 

## Důkaz (stručně rozšířený, s odkazy na věty)

Dokažme existenci maxima. Minimum se řeší obdobně.

- Protože $f$ je spojitá a $M$ kompaktní, obraz $f[M] \subseteq \mathbb{R}$ je také kompaktní  
  → **uzavřený a omezený** .
- Kompaktní podmnožina $\mathbb{R}$ má supremum, tedy existuje $A = \sup f[M] \in \mathbb{R}$.

Z definice suprema:
- Pro každé $n \in \mathbb{N}$ existuje $x_n \in M$ takové, že

$$
f(x_n) > A - \frac{1}{n}
$$

→ tedy $f(x_n) \to A$.

- Kompaktnost $M$ zaručuje, že posloupnost $(x_n) \subseteq M$ má konvergentní podposloupnost $(x_{n_k}) \to b \in M$  
  podle _Bolzano–Weierstrassovy věty_ 

- Funkce $f$ je spojitá, plyne z toho, že zachovává limitu (Heineho definice spojitosti):

$$
f(b) = \lim_{k \to \infty} f(x_{n_k}) = A
$$

Závěr: $f$ dosahuje na $M$ maximum v bodě $b \in M$.

$$
\boxed{f(b) = \max f[M]}
$$

---

**Poznámka:** Důkaz využívá základní vlastnosti:
- Každá omezená posloupnost má konvergentní podposloupnost (Bol-weis), [[Bolzanova–Weierstrassova věta]]
- Spojitá funkce zachovává limity posloupností (Věta 4.17 – Heine).


---

## Důkaz 2

Dokažme, že funkce $f$ spojitá na intervalu $I$ nabývá svého maxima. Případ minima je obdobný.

Definujme:
$$
S = \sup \{ f(x) \mid x \in I \} = \sup f(I)
$$

Z definice suprema platí, že $S$ je reálné číslo nebo $+\infty$ (protože $f(I)$ je neprázdná a shora omezená množina).

Cílem je ukázat, že existuje $L \in I$ takové, že $f(L) = S$. Takový bod $L$ bude bodem maxima funkce $f$.

---

### 1. Konstrukce posloupnosti přibližující supremum

Z definice suprema vyplývá, že **pro každé** $n \in \mathbb{N}$ existuje $x_n \in I$, pro které:
$$
f(x_n) \in U(S, \tfrac{1}{n})
$$
tedy:
$$
f(x_n) \to S
$$

---

### 2. Existence konvergentní podposloupnosti

Podle **Bolzano–Weierstrassovy věty** (_Věta 3.10_), pokud je interval $I$ **omezený**, pak každá posloupnost $(x_n) \subseteq I$ má **konvergentní podposloupnost** $(z_n)$:

$$
z_n \to L \in I
$$

Kompaktnost intervalu $I$ (uzavřenost + omezenost) zajišťuje, že limita $L$ náleží do $I$.

---

### 3. Přenos limit přes spojitou funkci

Z $(f(x_n)) \to S$ plyne, že i podposloupnost $(f(z_n)) \to S$.

Pokud by bylo $f(L) \ne S$, tak kvůli ohraničenosti musí platit $f(L) < S$ (jinak by $f(L)$ byla větší než supremum $S$, což je spor).

Zvolíme $\varepsilon > 0$ takové, že:
$$
U(S, \varepsilon) \cap U(f(L), \varepsilon) = \emptyset
$$

Funkce $f$ je spojitá v bodě $L$ (nebo jednostranně spojitá, pokud je $L$ krajní bod $I$), takže  platí:
$$
\lim_{x \to L} f(x) = f(L)
$$

Tedy existuje $\delta > 0$ takové, že:
$$
x \in U(L, \delta) \cap I \Rightarrow f(x) \in U(f(L), \varepsilon)
$$

Z $z_n \to L$ plyne, že existuje $n_0$ takové, že $\forall n \geq n_0$: $z_n \in U(L, \delta) \cap I$

Z $f(z_n) \to S$ plyne, že existuje $n_1$ takové, že $\forall n \geq n_1$: $f(z_n) \in U(S, \varepsilon)$

---

### 4. Spor

Zvolme $n \geq \max\{n_0, n_1\}$. Pak:
- $z_n \in U(L, \delta) \Rightarrow f(z_n) \in U(f(L), \varepsilon)$
- a zároveň $f(z_n) \in U(S, \varepsilon)$

Ale množiny $U(S, \varepsilon)$ a $U(f(L), \varepsilon)$ jsou disjunktní. **To je spor.**

---

### Závěr:

Naše předpoklady vedly ke sporu, tudíž nutně platí:
$$
f(L) = S
$$

Tedy funkce $f$ nabývá v bodě $L \in I$ svého maxima:
$$
\boxed{f(L) = \max f(I)}
$$




#proof #lecture6 #funkce  #limita
[[Maximum a minimum spojité funkce na kompaktu]]
