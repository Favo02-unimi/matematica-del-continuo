## Serie numeriche

### Serie note

- Serie geometrica: $\displaystyle\sum_{n=1}^{\infty} q^n$ dove $q \in \mathbb{R}$
	- in caso $-1 < q < 1$ allora **converge**
	- in caso $q \leq -1$ allora **irregolare**
	- in caso $q \geq 1$ allora **diverge positivamente**

- Serie telescopica: $\displaystyle\sum_{n=1}^{\infty} a_n - a_{n+k}$
	- in caso $\displaystyle\lim_{n \rightarrow \infty} a_n$ sia finito allora **converge**

- Serie armoniche: $\displaystyle\sum_{n=1}^{\infty} \frac{1}{n}$ **converge**
	- Serie armonica generalizzata: $\displaystyle\sum_{n=1}^{\infty} \frac{1}{n^a}$
		- in caso $a > 1$ allora **converge**
		- in caso $a \leq 1$ allora **diverge positivamente**

### Criteri per stabilire carattere

- Disequazione $a_n > 0$
	- in caso sia a termini positivi/negativi (o definitivamente positivi/negativi) allora **converge** o **diverge**

- Criterio necessario per convergenza: $\displaystyle\lim_{n \rightarrow +\infty} a_n = 0$
	- il criterio è solo necessario, **non sufficiente**
		- $\neq 0$ **diverge** o **irregolare**

- Criterio del rapporto: $\displaystyle\sum_{n=1}^{\infty} a_n$
	- $\displaystyle\lim_{n \rightarrow \infty} (\frac{a_{n+1}}{a_n}) = L$
		- in caso $L > 1$ allora **diverge positivamente**
		- in caso $L < 1$ allora **converge**
		- in caso $L = 1$ allora nessuna informazione

- Criterio della radice: $\displaystyle\sum_{n=1}^{\infty} a_n$
	- $\displaystyle\lim_{n \rightarrow \infty} (\sqrt[n]{a_n}) = L$
		- in caso $L > 1$ allora **diverge positivamente**
		- in caso $L < 1$ allora **converge**
		- in caso $L = 1$ allora nessuna informazione

## Serie di potenze

### Raggio di convergenza

_Il raggio di convergenza misura l'estensione dell'insieme aperto più grande su cui la serie converge._

 - Calcolare raggio di convergenza di: $\displaystyle\sum_{n=1}^{\infty} a_n x^n$
	 - isolare $x^n$ e $a_n$
	 - calcolare $L$ utilizzando:
		 - criterio del rapporto: $\displaystyle\lim_{n \rightarrow \infty} (\frac{a_{n+1}}{a_n}) = L$
		 - criterio della radice: $\displaystyle\lim_{n \rightarrow \infty} (\sqrt[n]{a_n}) = L$
	 - raggio $R$: reciproco di $L$: $\frac{1}{L}$

### Insieme di convergenza

- Calcolare l'insieme di convergenza di: $\displaystyle\sum_{n=1}^{\infty} a_n x^n$
	- calcolare il raggio di convergenza $R$
	- controllare se gli estremi dell'intervallo sono inclusi:
		- sostituendo $x^n$ con $-R$, calcolare: $\displaystyle\lim_{n \rightarrow \infty}a_n \cdot R^n = L$
			- se $L = 0$ allora l'estremo destro è incluso $R]$
			- se $L \neq 0$ allora l'estremo destro non è incluso $R)$
		- sostituendo $x^n$ con $-R$, calcolare: $\displaystyle\lim_{n \rightarrow \infty}a_n \cdot (-R)^n = L$
			- se $L = 0$ allora l'estremo sinistro è incluso $[-R$
			- se $L \neq 0$ allora l'estremo sinistro non è incluso $(-R$
	- insieme di convergenza: $[-R, R)$ oppure $(-R, R]$ oppure $(-R, R)$
