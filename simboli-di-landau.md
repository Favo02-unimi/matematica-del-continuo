# Simboli di Landau

Consideriamo $x_0 \in \mathbb{R} \cup \{\pm \infty\}$ e due funzioni $f(x),g(x)$ definite in un intorno $I$ di $x_0$

## O-grande $O$

$f(x)$ è un O-grande di $g(x)$ per $x \to x_0$ se e solo se esiste finito il limite per $x \to x_0$ del rapporto tra $f(x)$ e $g(x)$

$$f(x) = O(g(x)) \Longleftrightarrow \displaystyle\lim_{x \to x_0} \frac{f(x)}{g(x)} = \ell \in \mathbb{R}$$

Un'altra versione dell'O-grande afferma che possiamo definitivamente limitare superiormente la funzione $f(x)$ con $c \cdot g(x)$, ovvero $f(x) \leq c \cdot g(x)$ definitivamente

## Equivalenza asintotica $\sim$

$f(x)$ è asintoticamente equivalente a $g(x)$ per $x \to x_0$ se e solo se il limite del rapporto tra $f(x)$ e $g(x)$ è uguale a $1$

$$f(x) \sim g(x) \Longleftrightarrow \displaystyle\lim_{x \to x_0} \frac{f(x)}{g(x)} = 1$$

## o-piccolo $o$

$f(x)$ è o-piccolo di $g(x)$ per $x \to x_0$ se e solo se il limite del rapporto tra $f(x)$ e $g(x)$ è uguale a $0$

$$f(x) = o(g(x)) \Longleftrightarrow \displaystyle\lim_{x \to x_0} \frac{f(x)}{g(x)} = 0$$

## Altri simboli

Esistono altri simboli che non abbiamo trattato, ma che sono più utili nel corso di Algoritmi e Strutture Dati:
- equigrandezza $\asymp$
- omega piccolo $\omega$ e grande $\Omega$
- theta grande $\Theta$
