# Limiti con definizione

## Limiti di successione

In un limite di successione l'unico punto di accumulazione è $+\infty$, quindi abbiamo solo due "versioni" di limite: se il nostro "intorno sulle $Y$" è finito avremo $\epsilon$ ad indicare l'intorno, altrimenti $M$

### $Y$ finita

$$ \displaystyle \lim_{n \rightarrow +\infty} a_n = l \\ \forall{\epsilon} > 0 \quad \exists n_0 > 0 \quad \text{tale che} \quad \forall{n} > n_0 \Longrightarrow |a_n - l| < \epsilon $$

### $Y +\infty$

$$ \displaystyle \lim_{n \rightarrow +\infty} a_n = +\infty \\ \forall{M} > 0 \quad \exists n_0 > 0 \quad \text{tale che} \quad \forall{n} > n_0 \Longrightarrow a_n > M $$

### $Y -\infty$

$$ \displaystyle \lim_{n \rightarrow +\infty} a_n = -\infty \\ \forall{M} > 0 \quad \exists n_0 > 0 \quad \text{tale che} \quad \forall{n} > n_0 \Longrightarrow a_n < -M $$

## Limiti di funzione

In questo caso abbiamo ancora più "versioni" di definizione di limite, perché in un limite di funzione ogni punto è punto di accumulazione, quindi possiamo considerare limiti con $x$ che tendono a valori finiti

Il nostro "intorno sulle $X$" dipende dal valore al quale la $X$ tende: se è finito allora avremo $\delta$ ad indicare l'intorno, altrimenti $N$

Lo stesso discorso vale per le $Y$: se il valore del limite è finito avremo $\epsilon$ ad indicare l'intorno, altrimenti $M$

### $X$ finito, $Y$ finita

$$ \displaystyle \lim_{x \rightarrow x_0} f(x) = l \\ \forall{\epsilon} > 0 \quad \exists \delta > 0 \quad \text{tale che} \quad |x - x_0| < \delta \Longrightarrow |f(x) - l| < \epsilon $$

### $X$ finito, $Y +\infty$ 

$$ \displaystyle \lim_{x \rightarrow x_0} f(x) = +\infty \\ \forall{M} > 0 \quad \exists \delta > 0 \quad \text{tale che} \quad |x - x_0| < \delta \Longrightarrow f(x) > M $$

### $X$ finito, $Y -\infty$ 

$$ \displaystyle \lim_{x \rightarrow x_0} f(x) = -\infty \\ \forall{M} > 0 \quad \exists \delta > 0 \quad \text{tale che} \quad |x - x_0| < \delta \Longrightarrow f(x) < -M $$

### $X +\infty$, $Y$ finita 

$$ \displaystyle \lim_{x \rightarrow +\infty} f(x) = l \\ \forall{\epsilon} > 0 \quad \exists N > 0 \quad \text{tale che} \quad x > N \Longrightarrow |f(x) - l| < \epsilon $$

### $X -\infty$, $Y$ finita 

$$ \displaystyle \lim_{x \rightarrow -\infty} f(x) = l \\ \forall{\epsilon} > 0 \quad \exists N > 0 \quad \text{tale che} \quad x < -N \Longrightarrow |f(x) - l| < \epsilon $$

### $X +\infty$, $Y +\infty$

$$ \displaystyle \lim_{x \rightarrow +\infty} f(x) = +\infty \\ \forall{M} > 0 \quad \exists N > 0 \quad \text{tale che} \quad x > N \Longrightarrow f(x) > M $$

### $X +\infty$, $Y -\infty$

$$ \displaystyle \lim_{x \rightarrow +\infty} f(x) = -\infty \\ \forall{M} > 0 \quad \exists N > 0 \quad \text{tale che} \quad x > N \Longrightarrow f(x) < -M $$

### $X -\infty$, $Y +\infty$

$$ \displaystyle \lim_{x \rightarrow -\infty} f(x) = +\infty \\ \forall{M} > 0 \quad \exists N > 0 \quad \text{tale che} \quad x < -N \Longrightarrow f(x) > M $$

### $X -\infty$, $Y -\infty$

$$ \displaystyle \lim_{x \rightarrow -\infty} f(x) = -\infty \\ \forall{M} > 0 \quad \exists N > 0 \quad \text{tale che} \quad x < -N \Longrightarrow f(x) < -M $$
