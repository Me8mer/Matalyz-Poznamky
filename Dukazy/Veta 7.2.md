
## Důkaz k větě 7.8 – Aritmetika derivací (bod 3 a 4)
(*Mozno netreba dôkaz, počkaj na upresnenie*)

První dvě tvrzení jsou okamžitým důsledkem věty o aritmetice limit.

Páté tvrzení vyplývá ze třetího a čtvrtého pomocí přepisu:
$$
\frac{f(x)}{g(x)} = f(x) \cdot \left( \frac{1}{g(x)} \right)
$$

Zbývá tedy dokázat třetí a čtvrté tvrzení. Všimněme si, že z existence vlastní derivace plyne podle **Věty 7.7**, že funkce $f$ i $g$ jsou spojité v $A$.

---

### Důkaz bodu 3: derivace součinu

$$
(fg)'(A) = \lim_{x \to A} \frac{f(x)g(x) - f(A)g(A)}{x - A}
$$

Rozepišme výraz:
$$
= \lim_{x \to A} \frac{f(x)g(x) - f(A)g(x) + f(A)g(x) - f(A)g(A)}{x - A}
$$

Skupiny:
$$
= \lim_{x \to A} \left( \frac{f(x) - f(A)}{x - A} \cdot g(x) + f(A) \cdot \frac{g(x) - g(A)}{x - A} \right)
$$

Přes limitu:
$$
= f'(A) \cdot g(A) + f(A) \cdot g'(A)
$$

---

### Důkaz bodu 4: derivace inverzní funkce $1/g$

$$
\left( \frac{1}{g} \right)'(A) = \lim_{x \to A} \frac{1/g(x) - 1/g(A)}{x - A}
$$

Úprava zlomků:
$$
= \lim_{x \to A} \frac{g(A) - g(x)}{g(x)g(A)(x - A)}
$$

Rozklad:
$$
= \lim_{x \to A} \frac{1}{g(x)g(A)} \cdot \lim_{x \to A} \frac{g(A) - g(x)}{x - A}
$$

Zápis derivace:
$$
= -\frac{g'(A)}{g(A)^2}
$$

Poslední krok využívá spojitost funkce $g$ v bodě $A$.


#proof #lecture7 #funkce  #derivace
[[Aritmetika derivací]]