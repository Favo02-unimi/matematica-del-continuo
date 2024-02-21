## Simboli di Landau

- sia $x_0 \in \mathbb R \cup \{\pm \infty\}$
- siano $f(x)$ e $g(x)$ due funzioni definite su un intorno $I$ di $x_0$

_Negli esercizi $f$ e $g$ sono quasi sempre successioni a termini non nulli, quindi $x_0 = + \infty$._

### O-grande $O$

$f(x)$ è un O-grande di $g(x)$ per $x \rightarrow x_0$ se esiste finito il limite:

$$f(x) = O(g(x)) \Leftrightarrow lim_{x \rightarrow x_0} \frac{f(x)}{g(x)} = \ell \in \mathbb{R}$$

### Equivalenza asintotica $\sim$

$f(x)$ è asintoticamente equivalente a $g(x)$ per $x \rightarrow x_0$ se e solo se il limite del rapporto è uguale a $1$:

$$f(x) \sim g(x) \Leftrightarrow lim_{x \rightarrow x_0} \frac{f(x)}{g(x)} = 1$$

### o-piccolo $o$

$f(x)$ è o-piccolo di $g(x)$ per $x \rightarrow x_0$ se e solo se il limite del rapporto è uguale a $0$:

$$f(x) = o(g(x)) \Leftrightarrow lim_{x \rightarrow x_0} \frac{f(x)}{g(x)} = 0$$

### Altri simboli

Esistono altri simboli, che non abbiamo trattato _(o almeno, non ci sono negli esercizi)_:

- equigrandezza $\asymp$
- omega piccolo $\omega$
- omega grande $\Omega$
- theta grande $\Theta$
