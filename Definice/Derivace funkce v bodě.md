## Definice: 
**Derivace funkce** $f$ v bodě $A$ je definována jako limita:

$$
f'(A) := \lim_{h \to 0} \frac{f(A + h) - f(A)}{h}
$$

nebo ekvivalentně (přeznačením $x = A + h$):

$$
f'(A) := \lim_{x \to A} \frac{f(x) - f(A)}{x - A}
$$

---
### Poznámky k derivaci (treba vediet ale nie k definici)

- **Derivace zprava** v bodě $A$ je jednostranná limita pro $h \to 0^+$ (nebo $x \to A^+$).  
  Značíme:
  $$
  f'_+(A)
  $$

- **Derivace zleva** je obdobně:
  $$
  f'_-(A)
  $$

- Pokud $f'(A)$ **existuje a je reálná**, říkáme, že funkce $f$ má v bodě $A$ **vlastní derivaci**.

- Pokud $f'(A) \in \{-\infty, +\infty\}$, pak má $f$ **nevlastní derivaci**.

- Pokud derivace **vůbec neexistuje**, může jít o případ:
  - kdy jednostranné limity neexistují,
  - nebo nejsou si rovny.

---

Derivace existuje **právě tehdy**, když obě jednostranné derivace existují **a jsou si rovny**.

Aby mohla derivace (vlastní či nevlastní) v bodě $A$ existovat, musí být funkce $f$ **definovaná v okolí bodu $A$** — nejen v $A$ samotném.




#definition #lecture7 #derivace 
[[Derivace složené funkce-priklad]]
[[Derivace identity]]

