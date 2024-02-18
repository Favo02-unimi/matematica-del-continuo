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

### Criteri per stabilire carattere

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

## Serie di potenze

### Raggio di convergenza

_Il raggio di convergenza misura l'estensione dell'insieme aperto più grande su cui la serie converge._

 - Calcolare raggio di convergenza: $\displaystyle\sum_{n=1}^{\infty} a_n x^n$
	 - isolare $x^n$ e $a_n$
	 - calcolare $l = lim_{n \rightarrow \infty} sup(\sqrt[n]{|a_n|)}$
		 - se $l = 0$ allora $r = +\infty$
		 - se $0 < l < +\infty$ allora $r = \frac{1}{l}$
		 - se $l = +\infty$ allora $r = 0$
	 - trucchi per calcolare $lim_{n \rightarrow \infty}\sqrt[n]{|a_n|)}$
		 - cercare di rimuovere il valore assoluto _(quasi sempre senza conseguenze)_
		 - trasformare radice in esponenziale: $lim_{n \rightarrow \infty}(a_n)^{\frac{1}{n}}$
		 - applicare logaritmo al limite: $log\ lim_{n \rightarrow \infty}(a_n)^{\frac{1}{n}}$
			 - $lim_{x \rightarrow x_0} t(x)$ = $t(x_0)$ = $t(lim_{x \rightarrow x_0}x)$
		 - scambiare logaritmo e limite: $lim_{n \rightarrow \infty}\ log ((a_n)^{\frac{1}{n}})$
			 - proprietà funzioni continue: $lim_{x \rightarrow x_0} t(x)$ = $t(x_0)$ = $t(lim_{x \rightarrow x_0}x)$
		 - tirare fuori esponente: $lim_{n \rightarrow \infty}\ \frac{1}{n}log (a_n)$
			 - proprietà logaritmi: $log ((a)^2)$ = $2 log(a)$
		 - risolvere: $lim_{n \rightarrow \infty}\ \frac{1}{n}log (a_n) = 0$
		 - applicare in modo inverso il logaritmo:
			 - dato che $log(lim_{n \rightarrow \infty}(a_n)^{\frac{1}{n}}) = 0$
			 - ovvero $log(x) = 0$, quindi $x = 1$
			 - quindi $x = lim_{n \rightarrow \infty}(a_n)^{\frac{1}{n}} = 1$
