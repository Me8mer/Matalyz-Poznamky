## Definice: 

Nechť $f : [A, B] \to \mathbb{R}$ je funkce, kde $A < B$ jsou reálná čísla.  
Pro dělení $D = (A_0, A_1, \dots, A_k)$ intervalu $[A, B]$ definujeme:

- **dolní Riemannovu sumu**:

  $$
  s(f, D) = \sum_{i=0}^{k-1} |I_i| \cdot m_i,\quad
  m_i = \inf\{f(x);\ x \in I_i\}
  $$

- **horní Riemannovu sumu**:

  $$
  S(f, D) = \sum_{i=0}^{k-1} |I_i| \cdot M_i,\quad
  M_i = \sup\{f(x);\ x \in I_i\}
  $$

Obě sumy jsou vždy definovány a mají hodnoty v $\mathbb{R} \cup \{-\infty, +\infty\}$.

---

#### Riemannovy integrály

- **Dolní Riemannův integrál:**

  $$
  \underline{\int_A^B} f(x)\ dx = \sup \{ s(f, D):\ D \text{ je dělení } [A, B] \}
  $$

- **Horní Riemannův integrál:**

  $$
  \overline{\int_A^B} f(x)\ dx = \inf \{ S(f, D):\ D \text{ je dělení } [A, B] \}
  $$

---

Funkce $f$ je **Riemannovsky integrovatelná**, pokud:

$$
\underline{\int_A^B} f(x)\ dx = \overline{\int_A^B} f(x)\ dx \in \mathbb{R}
$$

Tuto společnou konečnou hodnotu značíme:

$$
\int_A^B f(x)\ dx
$$

a nazýváme **Riemannovým integrálem** funkce $f$ na intervalu $[A, B]$.

---

Třídu všech takto integrovatelných funkcí označujeme:

$$
\mathcal{R}(A, B)
$$




#definition #lecture10 #urcityIntegral #RiemannuvIntegral

