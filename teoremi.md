## Teoremi

_Enunciato e dimostrazione per scritto e orale ridotto:_
- [Retta tangente al grafico in un punto di derivabilità](#retta-tangente-al-grafico-in-un-punto-di-derivabilità)
- [Teorema di Fermat](#teorema-di-fermat)
- [Teorema di Rolle](#teorema-di-rolle)
- [Teorema della media integrale](#teorema-della-media-integrale)
- [Teorema fondamentale del calcolo integrale](#teorema-fondamentale-del-calcolo-integrale)
- [Formula fondamentale del calcolo integrale](#formula-fondamentale-del-calcolo-integrale)

_Enunciato per orale ridotto e dimostrazione per orale completo:_
- [Teorema dell'unicità del limite di successioni convergenti](#teorema-dellunicità-del-limite-di-successioni-convergenti)
- [Teorema della permanenza del segno](#teorema-della-permanenza-del-segno)
- [Teorema del confronto](#teorema-del-confronto)
- [Teorema di Darboux o dei valori intermedi](#teorema-di-darboux-o-dei-valori-intermedi)
- [Relazione tra derivabilità e continuità](#relazione-tra-derivabilità-e-continuità)
- [Teorema di Lagrange o del valor medio](#teorema-di-lagrange-o-del-valor-medio)
  - [(1) Funzioni con derivata nulla su un intervallo sono costanti](#1-funzioni-con-derivata-nulla-su-un-intervallo-sono-costanti)
  - [(2) Funzioni con derivate coincidenti su intervallo differiscono per una costante additiva](#2-funzioni-con-derivate-coincidenti-su-intervallo-differiscono-per-una-costante-additiva)
  - [(3) Relazioni tra monotonia e segno della derivata su un intervallo](#3-relazioni-tra-monotonia-e-segno-della-derivata-su-un-intervallo)
- [Prima formula dell'incremento finito](#prima-formula-dellincremento-finito)
- [Seconda formula dell'incremento finito](#seconda-formula-dellincremento-finito)


## Retta tangente al grafico in un punto di derivabilità

- sia $f : (a, b) \subseteq \mathbb{R} \rightarrow \mathbb{R}$
- sia $x_0 \in (a, b)$

Allora $f$ si dice derivabile in $x_0$ se esiste finito il limite $\displaystyle\lim_{h \rightarrow 0} \frac{f(x_0 + h) - f(x_0)}{h}$.

Questo limite si chiama derivata e si indica con $f'(x_0)$, $\frac{df}{dx}(x_0)$, $Df(x_0)$.

**Significato geometrico**:

Se $f$ è derivabile in $x_0$ allora il grafico di $f$ ammette nel punto $(x_0, f(x_0))$ retta tangente di equazione $y = f'(x_0)(x-x_0) + f(x_0)$.

Infatti l'equazione della retta passante per i punti $A = (x_0, f(x_0))$ e $B = (x_0+h, f(x_0+h))$ è $y = \frac{f(x_0+h) - f(x_0)}{h} (x - x_0) + f(x_0)$.

> Passaggi chiave:
> - rapporto incrementale
> - equazione retta

## Teorema di Fermat

- sia $f : [a, b] \subseteq \mathbb{R} \rightarrow \mathbb{R}$
- sia $x_0 \in (a, b)$
- sia $f$ derivabile in $x_0$
- sia $x_0$ un punto estremante per $f$ su $[a,b]$

Allora $f'(x_0) = 0$.

**Dimostrazione**:

Sia $x_0$ un punto di minimo relativo, quindi:

$\exists \delta > 0$ tale che $x \in (x_0 - \delta, x_0 + \delta) \cap (a,b) \Rightarrow f(x_0) \leq f(x)$

Pertanto:

- $\frac{f(x_0+h)-f(x_0)}{h}$ è $\geq 0$ per ogni $h \in (0, \delta)$
- $\frac{f(x_0+h)-f(x_0)}{h}$ è $\leq 0$ per ogni $h \in (-\delta, 0)$

Passando al limite:
- $\displaystyle\lim_{h \rightarrow 0^+} \frac{f(x_0+h)-f(x_0)}{h} = f'_ +(x_0)$, per il teorema della permanenza del segno $f'_ +(x_0) \geq 0$
- $\displaystyle\lim_{h \rightarrow 0^-} \frac{f(x_0+h)-f(x_0)}{h} = f'_ -(x_0)$, per il teorema della permanenza del segno $f'_ -(x_0) \leq 0$

Dato che per definizione di derivata i due limiti (destro e sinistro) devono essere uguali, allora $f'(x_0) = 0$.

> Passaggi chiave:
> - intorno di $x_0$
> - rapporto incrementale per $h > 0$ e $h < 0$
> - passaggio al limite
> - limite destro e sinistro devono essere uguali

## Teorema di Rolle

- sia $f : [a, b] \subseteq \mathbb{R} \rightarrow \mathbb{R}$
- sia $f$ continua su $[a, b]$
- sia $f$ derivabile in $(a, b)$
- sia $f(a) = f(b)$

Allora $\exists z \in (a,b)$ tale che $f'(z) = 0$ (punto stazionario).

**Dimostrazione**:

- sia $f(x)$ costante su $[a,b]$

allora $f'(z) = 0 \ \forall z \in (a,b)$.

- sia $f(x)$ non costante su $[a,b]$

allora dato che $f$ è continua su $[a,b]$, per il teorema di Weierstrass $f$ ammette un punto di minimo assoluto $m$ e un punto di massimo assoluto $M$.

I punti $m$ e $M$ non possono essere entrambi agli estremi dell'intervallo $[a,b]$, altrimenti $f$ sarebbe costante su $[a,b]$ e di conseguenza si ricadrebbe nel primo caso (assurdo).

Quindi il punto $z$ estremante ($m$ o $M$) interno all'intervallo $(a,b)$ ha per il teorema di Fermat $f'(z) = 0$.

> Passaggi chiave:
> - $f$ costante e $f$ non costante
> - massimo e minimo assoluto su $f$
> - per Fermat derivata nulla

## Teorema della media integrale

- sia $f : [a, b] \subseteq \mathbb{R} \rightarrow \mathbb{R}$
- sia $f$ continua su $[a, b]$

Allora $\exists z \in [a,b]$ tale che $f(z)(b-a) = \int_a^b f(x)dx$.

**Dimostrazione**:

Dato che $f$ è continua su $[a,b]$, per il teorema di Weierstrass esistono un minimo assoluto $m$ e un massimo assoluto $M$:

- $m \leq f(x) \leq M \ \forall x \in [a,b]$
- $\int_a^b m\ dx \leq \int_a^b f(x) dx \leq \int_a^b M\ dx$ _(proprietà di monotonia dell'integrale)_
- $(b-a) m \leq \int_a^b f(x) dx \leq (b-a) M$
- $m \leq \frac{1}{(b-a)}\int_a^b f(x) dx \leq M$

Dato che $f$ è continua su $[a,b]$, per la proprietà di Darboux:

$\exists z \in [a,b]$ tale che $f(z) = \frac{1}{(b-a)} \int_a^b f(x) \ dx$,

quindi $f(z)(b-a) = \int_a^b f(x) \ dx$.

> Passaggi chiave:
> - massimo e minimo di $f$
> - minimo $\leq$ integrale $\leq$ massimo
> - proprietà di Darboux

## Teorema fondamentale del calcolo integrale

- sia $f : [a, b] \subseteq \mathbb{R} \rightarrow \mathbb{R}$
- sia $f$ continua su $[a,b]$
- sia $F(x)$ la sua funzione integrale: $F(x) = \int_a^x f(t)\ dt\ \forall x \in [a,b]$

Allora $F$ è derivabile in $[a,b]$ e ha valore $F'(x) = f(x) \ \forall x \in [a,b]$.

Inoltre, $F$ si dice primitiva di $f$ su $[a,b]$.

**Dimostrazione**:

Sia $x_0$ un punto interno a $(a,b)$.

Consideriamo il rapporto incrementale di $F$ centrato in $x_0$, con $h \neq 0$ sufficientemente piccolo che $x_0 + h \in (a, b)$:

- $\frac{F(x_0+h) - F(x_0)}{h}$
- $\frac{1}{h} (\int_a^{x_0+h} f(t)\ dt - \int_a^{x_0} f(t)\ dt)$
- $\frac{1}{h} (\int_a^{x_0} f(t)\ dt + \int_{x_0}^{x_0+h} f(t)\ dt - \int_a^{x_0} f(t)\ dt)$
- $\frac{1}{h} (\int_{x_0}^{x_0+h} f(x)\ dx)$

Per il teorema della media integrale allora esiste un punto $z$:

- $x_0 \leq z \leq x_0+h$ se $h > 0$
- $x_0+h \leq z \leq x_0$ se $h < 0$

tale che $f(z)$ sia la media integrale.

Quindi passando al limite per $h \rightarrow 0$ del rapporto incrementale:

- $\displaystyle\lim_{h \rightarrow 0} \frac{F(x_0+h) - F(x_0)}{h}$
- $\displaystyle\lim_{h \rightarrow 0}\frac{1}{h} (\int_{x_0}^{x_0+h} f(x)\ dx)$
- $\displaystyle\lim_{h \rightarrow 0}\frac{1}{h}(x_0+h-x_0)(f(z))$
- $\displaystyle\lim_{h \rightarrow 0}f(z)$
- $\displaystyle\lim_{z \rightarrow x_0}f(z)$
- $f(x_0)$

_Nota_: se $x_0 = a$ (o se $x_0 = b$), la dimostrazione è uguale alla precedente considerando solo il limite destro (o sinistro), poiché $h > 0$ (o $h < 0$).

> Passaggi chiave:
> - rapporto incrementale centrato di $F$ centrato in $x_0$ con $h$ abbastanza piccolo
> - dividere rapporto incrementale in 3 integrali
> - semplificare rimuovendo $\frac{1}{h}$ e i due integrali "esterni"
> - per la media integrale $\exists z$
> - applicazione limite per $z \rightarrow x_0$

## Formula fondamentale del calcolo integrale

- sia $f : [a, b] \subseteq \mathbb{R} \rightarrow \mathbb{R}$
- sia $f$ continua su $[a,b]$
- sia $G(x)$ una qualsiasi primitiva di $f$ su $[a,b]$

Allora $\int_a^b f(t)\ dt = G(b) - G(a)$.

**Dimostrazione**:

Dal teorema fondamentale del calcolo integrale, sappiamo che:

$F(x) = \int_a^x f(t)\ dt \ \forall x \in [a,b]$.

$F$ e $G$ sono entrambe primitive della stessa funzione $f$ su $[a,b]$. Per la seconda conseguenza del teorema di Lagrange, tutte le primitive differiscono solo di una costante additiva $c$, quindi:

- $F(x) = G(x) + c$, $\forall x \in [a,b]$
- $\int_a^x f(t) \ dt = G(x) + c$

Sostituendo $x = a$:

- $\int_a^a f(t) \ dt = G(a) + c$
- $0 = G(a) + c$
- $c = -G(a)$

Sostituendo $x = b$:

- $\int_a^b f(t) \ dt = G(b) + c$
- $\int_a^b f(t) \ dt = G(b) - G(a)$

> Passaggi chiave:
> - teorema fondamentale del calcolo integrale $F(x)$
> - seconda conseguenza teorema di Lagrange: le primitive differiscono di $c$
> - sostituire $x = a$
> - sostituire $x = b$

## Teorema dell'unicità del limite di successioni convergenti

- sia $\displaystyle \lim_{n \rightarrow +\infty} a_n = a$
- sia $\displaystyle \lim_{n \rightarrow +\infty} a_n = b$

Allora $a = b$.

> Se il limite esiste (finito o infinito), allora è unico

## Teorema della permanenza del segno

- sia $\displaystyle \lim_{n \rightarrow +\infty} a_n = a \in \mathbb{R}$

Se $a > 0$ allora $\exists n_0$ tale che $\forall n > n_0 \ a_n > 0$.

Se $a < 0$ allora $\exists n_0$ tale che $\forall n > n_0 \ a_n < 0$.

> Una successione che tende a un limite positivo (negativo) ha definitivamente soltanto termini positivi (negativi), quindi la funzione è localmente concorde con il segno del limite

## Teorema del confronto

- siano $a_n$, $b_n$, $c_n$ tre successioni

1. Se $a_n \leq b_n$ e $\displaystyle \lim_{n \rightarrow +\infty} a_n = +\infty$ allora $\displaystyle \lim_{n \rightarrow +\infty} b_n = +\infty$
2. Se $b_n \leq c_n$ e $\displaystyle \lim_{n \rightarrow +\infty} c_n = -\infty$ allora $\displaystyle \lim_{n \rightarrow +\infty} b_n = -\infty$
3. Se $a_n \leq b_n \leq c_n$ e $\displaystyle \lim_{n \rightarrow +\infty} a_n = \lim_{n \rightarrow +\infty} c_n = \alpha$ allora $\displaystyle \lim_{n \rightarrow +\infty} b_n = \alpha$ _(Teorema dei due carabinieri)_

> Calcolare il limite di una successione (o funzione) confrontandola con altre due che "si stringono sempre di più" intorno a quella data

## Teorema di Darboux o dei valori intermedi

- sia $f : [a,b] \subseteq \mathbb{R} \rightarrow \mathbb{R}$
- sia $f$ continua su $[a,b]$

Allora $f$ assume tutti i valori compresi tra $f(a)$ e $f(b)$.

> L'immagine di $f$ assume tutti i valori compresi tra le immagini degli estremi del dominio

## Relazione tra derivabilità e continuità

- sia $f : (a,b) \subseteq \mathbb{R} \rightarrow \mathbb{R}$
- sia $x_0 \in (a,b)$

Allora se $f(x)$ è derivabile in $x_0$, allora $f$ è continua in $x_0$.

> La derivabilità implica sempre la continuità (condizione sufficiente), mentre la continua non implica necessariamente la derivabilità (condizione necessaria)

## Teorema di Lagrange o del valor medio

- sia $f : [a,b] \subseteq \mathbb{R} \rightarrow \mathbb{R}$
- sia $f$ continua su $[a,b]$
- sia $f$ derivabile in $(a,b)$

Allora $\exists x_0 \in (a,b)$ tale che $f'(x_0) = \frac{f(b) - f(a)}{b-a}$ ovvero $f(b) - f(a) = f'(x_0)(b-a)$.

> Esiste almeno un punto in cui la tangente al grafico di una funzione è parallela alla secante passante per gli estremi del dominio della funzione

## Conseguenze del teorema di Lagrange

### (1) Funzioni con derivata nulla su un intervallo sono costanti

- sia $f$ continua su $[a,b]$
- sia $f$ derivabile su $(a,b)$
- sia $f'(x) = 0 \ \forall x \in (a,b)$

Allora $f(x) = c \ \forall x \in [a,b]$.

> La funzione è costante sull'intervallo in cui la derivata è nulla

### (2) Funzioni con derivate coincidenti su intervallo differiscono per una costante additiva

- siano $f$ e $g$ continue su $[a,b]$
- siano $f$ e $g$ derivabili su $(a,b)$
- sia $f'(x) = g'(x) \ \forall x \in (a,b)$

Allora $f$ e $g$ differiscono di una costante additiva $c$: $\exists c$ tale che $f(x) = g(x) + c$.

> Se due funzioni hanno la stessa derivata su un intervallo, allora differiscono per una costante additiva

### (3) Relazioni tra monotonia e segno della derivata su un intervallo

- sia $f$ continua su $[a,b]$
- sia $f$ derivabile su $(a,b)$

Allora valgono:
1. $f'(x) \geq 0 \ \forall x \in (a,b) \Longleftrightarrow f$ è monotona crescente su $(a,b)$
2. $f'(x) \leq 0 \ \forall x \in (a,b) \Longleftrightarrow f$ è monotona decrescente su $(a,b)$
3. $f'(x) > 0 \ \forall x \in (a,b) \Longleftrightarrow f$ è monotona strettamente crescente su $(a,b)$
4. $f'(x) < 0 \ \forall x \in (a,b) \Longleftrightarrow f$ è monotona strettamente decrescente su $(a,b)$.

> La derivata di una funzione su un intervallo ne descrive la sua monotonia

## Prima formula dell'incremento finito

- sia $f : (a,b) \subseteq \mathbb{R} \rightarrow \mathbb{R}$
- sia $x_0 \in (a,b)$
- sia $f$ derivabile in $x_0$

Allora vale la formula: $f(x) = f(x_0) + f'(x_0)(x - x_0) + o(x - x_0)$ per $x \rightarrow x_0$.

## Seconda formula dell'incremento finito

- sia $f$ derivabile in un intorno di $x_0 : I_\delta(x_0) = (x_0 - \delta, x_0 + \delta)$ con $\delta > 0$

Allora $\forall x \in (x_0 - \delta, x_0 + \delta) \ \exists z \in \begin{cases} (x_0, x) \text{ se } x > x_0 \\ (x, x_0) \text{ se } x < x_0 \end{cases}$ tale per cui $f(x) = f(x_0) + f'(z)(x - x_0)$.
