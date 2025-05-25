## Důkaz – Rolleova věta

Pokud je funkce $f$ na $[A, B]$ konstantní, pak $f'(C) = 0$ pro každé $C \in (A, B)$ – tvrzení je tedy splněno.

Pokud $f$ není konstantní, pak existuje $D \in (A, B)$ takové, že:
$$
f(D) \ne f(A) = f(B)
$$

Bez újmy na obecnosti předpokládejme $f(D) > f(A) = f(B)$.  
Podle [[X-Maximum a minimum spojité funkce na kompaktu]]](princip maxima) nabývá spojitá funkce na uzavřeném intervalu maximum, tedy existuje $C \in [A, B]$, pro které:
$$
f(C) = \max \{ f(x) \mid x \in [A, B] \}
$$

Z předchozí nerovnosti $f(C) \geq f(D) > f(A)$ plyne, že maximum nemůže být v krajních bodech $A$ ani $B$.  
Tedy $C \in (A, B)$.

Bod $C$ je bodem lokálního maxima, a proto podle [[Nutná podmínka pro lokální extrém]] platí:
$$
f'(C) = 0
$$



#proof #lecture8 #funkce  #derivace
[[Rolleova věta]]