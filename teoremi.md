## Teoremi

### Retta tangente al grafico in un punto di derivabilità

- sia $f : (a, b) \subseteq \mathbb{R} \rightarrow \mathbb{R}$
- sia $x_0 \in (a, b)$

Allora $f$ si dice derivabile in $x_0$ se esiste finito il limite $lim_{h \rightarrow 0} \frac{f(x_0 + h) - f(x_0)}{h}$.
Questo limite si chiama derivata e si indica con $f'(x_0)$, $\frac{df}{dx}(x_0)$, $Df(x_0)$.

**Significato geometrico**:

Se $f$ è derivabile in $x_0$ allora il grafico di $f$ ammette nel punto $(x_0, f(x_0))$ retta tangente di equazione $y = f'(x_0)(x-x_0) + f(x)$.
Infatti l'equazione della retta passante per i punti $A = (x_0, f(x_0))$ e $B = (x_0+h, f(x_0+h))$ è $y = \frac{f(x_0+h) - f(x_0)}{h} (x - x_0) + f(x_0)$.
