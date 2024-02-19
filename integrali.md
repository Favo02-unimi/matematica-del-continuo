## Integrali indefiniti

### Integrali immediati

- $\int 1$ = $x$
- $\int a$ = $ax$
- $\int x^n$ = $\frac{x^{n+1}}{n+1}$
- $\int \frac{1}{x}$ = $log|x|$
- $\int e^x$ = $e^x$
- $\int a^x$ = $\frac{a^x}{log(a)}$
- $\int sin(x)$ = $-cos(x)$
- $\int cos(x)$ = $sin(x)$
- $\int \frac{1}{cos^2(x)}$ = $tan(x)$
- $\int \frac{1}{1+x^2}$ = $arctan(x)$
- $\int \frac{1}{\sqrt{1-x^2}}$ = $arcsin(x)$

### Integrali composti

Trucchi per risolvere integrali "composti" (termine improprio):
- controllare se è presente la derivata $f'(x)$ della funzione $f(x)$ nella parte più complessa dell'integrale (quasi sempre a denominatore):
	- $\int \frac{f(x)}{f'(x)}$ = $log|f(x)|$
	- $\int \frac{f(x)}{1 + f'(x)^2}$ = $arctan(f(x))$
- cercare sempre di portare a numeratore le somme, in modo da poter dividere l'integrale
	- $\int a + b \ dx$ = $\int a \ dx + \int b \ dx$
	- applicare la sostituzione per spostare: $\int \frac{x}{\sqrt{x+1}} \ dx$ = $\int \frac{t-1}{\sqrt{t}} \ dt$

### Integrazione per sostituzione

- sostituire con $t$
- calcolare quanto vale la nuova $x$
- calcolare quanto vale $dx$, da sostituire con $dt = D(t) dx$
	- derivate il valore sostituito con $t$
	- spostare per ottenere $dx =\ ...\ dt$
- calcolare l'integrale per $t$
- sostituire nel risultato il a $x$ a $t$

### Integrazione per parti

- portare l'integrale nella forma $\int f(x) \ g(x) \ dx$
- scegliere una funzione da derivare $f$ e una da integrare $g'$
- calcolare derivata $f'$ e integrale $g$
- applicare la formula $f(x) \ g(x) - \int f'(x) \ g(x) \ dx$
- risolvere (può essere necessario applicare ancora l'integrazione per parti per risolvere l'integrale ottenuto)
