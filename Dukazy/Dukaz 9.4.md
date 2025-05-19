## Věta: Integrace Per Partes

- Funkce $f \cdot G$ a $F \cdot g$ jsou součinem spojitých funkcí ⇒ také spojité.
- Podle vety [[Spojitá funkce má primitivní funkci]] mají obě tyto funkce primitivní funkce.
- Derivace součinu (Leibnizova formule) dává:
$$
\frac{d}{dx} \left( F(x) G(x) \right) = F'(x) G(x) + F(x) G'(x)
= f(x) G(x) + F(x) g(x)
$$

Tedy funkce $F(x) G(x)$ je primitivní k součtu $f(x) G(x) + F(x) g(x)$ ⇒ integrací obou stran:
$$
\int f(x) G(x)\, dx + \int F(x) g(x)\, dx = \int \left( f(x) G(x) + F(x) g(x) \right)\, dx
= F(x) G(x) + c
$$



#proof #lecture9 #neurcityIntegral #integral
[[Integrace per partes]]