

### Příklad - Derivace složené funkce i bez derivace dílčích funkcí

Když máme složenou funkci, ve které jedna z dílčích funkcí nemá derivaci,  
**ještě to neznamená**, že neexistuje derivace složené funkce.

Uvažujme:

- $f(x) = |x|$  
- $g(x) = x^2$

Pak:

- $h_1(x) = f(g(x)) = |x^2|$  
- $h_2(x) = g(f(x)) = |x|^2$

Hledáme derivace $h_1$ a $h_2$ v nule.

Nelze přímo dosadit do vzorce z věty 7.10, protože $f$ **nemá derivaci v nule**.

Nicméně, snadno nahlédneme, že pro každé $x$ platí:

- $h_1(x) = h_2(x) = x^2$

Tedy:

- $h_1'(0) = h_2'(0) = 0$


#example #lecture7 #derivace 
[[Derivace funkce v bodě]]