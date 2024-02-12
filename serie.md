## Serie numeriche

### Serie note

- Serie geometrica: $\displaystyle\sum_{n=1}^{\infty} q^n$ dove $q \in \mathbb{R}$
	- in caso $-1 < q < 1$ allora **converge**
	- in caso $q \leq -1$ allora **irregolare**
	- in caso $q \geq 1$ allora **diverge positivamente** 

- Serie telescopica: $\displaystyle\sum_{n=1}^{\infty} a_n - a_{n+k}$
	- in caso $lim_{n \rightarrow \infty} a_n$ sia finito allora **converge**

- Serie armoniche: $\displaystyle\sum_{n=1}^{\infty} \frac{1}{n}$ **converge**
	- Serie armonica generalizzata: $\displaystyle\sum_{n=1}^{\infty} \frac{1}{n^a}$
		- in caso $a > 1$ allora **converge**
		- in caso $a \leq 1$ allora **diverge positivamente**

### Criteri per stabilire rapporto

- Disequazione $a_n > 0$
	- in caso sia a termini positivi/negativi (o definitivamente positivi/negativi) allora **converge** o **diverge**

- Criterio necessario per convergenza: $lim_{n \rightarrow +\infty} a_n = 0$
	- il criterio è solo necessario, **non sufficiente**
		- $\neq 0$ **diverge** o **irregolare**

- Criterio del rapporto: $\displaystyle\sum_{n=1}^{\infty} a_n$
	- $lim_{n \rightarrow \infty} (\frac{a_{n+1}}{a_n}) = L$
		- in caso $L > 1$ allora **diverge positivamente**
		- in caso $L < 1$ allora **converge**
		- in caso $L = 1$ allora nessuna informazione

- Criterio della radice: $\displaystyle\sum_{n=1}^{\infty} a_n$
	- $lim_{n \rightarrow \infty} (\sqrt[n]{a_n}) = L$
		- in caso $L > 1$ allora **diverge positivamente**
		- in caso $L < 1$ allora **converge**
		- in caso $L = 1$ allora nessuna informazione
