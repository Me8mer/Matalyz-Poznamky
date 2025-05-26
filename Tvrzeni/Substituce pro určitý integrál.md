## Tvrzeni

**Tvrzení:**  
Nechť $\varphi : [\alpha, \beta] \to \mathbb{R}$ je spojitá funkce, která má v každém bodě intervalu $(\alpha, \beta)$ vlastní derivaci.  
Označme:
$$
J := \varphi((\alpha, \beta)) = \{ \varphi(t) \mid t \in (\alpha, \beta) \}
$$

Nechť $f$ je funkce spojitá na $J$ a Newtonovsky integrovatelná na jeho vnitřku.  
Pak platí:
$$
(N) \int_\alpha^\beta f(\varphi(t)) \varphi'(t)\, dt = (N) \int_{\varphi(\alpha)}^{\varphi(\beta)} f(x)\, dx
\quad \text{(rovnice (11.1))}
$$


Notes:

- Pokud $\varphi(\alpha) > \varphi(\beta)$, pak platí:
  $$
  (N) \int_{\varphi(\alpha)}^{\varphi(\beta)} f = - (N) \int_{\varphi(\beta)}^{\varphi(\alpha)} f
  $$

- Pokud $\varphi(\alpha) = \varphi(\beta)$, pak:
  $$
  (N) \int_{\varphi(\alpha)}^{\varphi(\beta)} f := 0
  $$

- Interval $J$ může být otevřený, uzavřený nebo polootevřený – je obrazem $(\alpha, \beta)$ funkcí $\varphi$.

- Při ověřování podmínek pro funkci $f$ je nutné ověřit vlastnosti **na celém intervalu $J$**,  
  nestačí jen na intervalu mezi $\varphi(\alpha)$ a $\varphi(\beta)$.

- Při výpočtu integrálu podle této věty není třeba znát přesně krajní body $J$,  
  stačí ověřit, že $f$ splňuje podmínky na nějakém intervalu obsahujícím $J$.  
  Například pokud je $f$ spojitá na $\mathbb{R}$, pak je spojitá i na $J$.


#theorem #lecture10 #urcityIntegral 
[[10.3]]