## Numeri complessi

Insieme ($\mathbb{C}$) di numeri che estendono l'insieme dei numeri reali.

Rendono possibili le radici negative: $x^2 = -1$, $i = \sqrt{-1}$

### Forma algebrica

- $z = a + ib$, con $a, b \in \mathbb{R}$
	- $a$ è detta parte reale
	- $ib$ è detta parte immaginaria ($b$ può essere considerato come "coefficiente" della parte immaginaria)
- numero coniugato: $\bar{z} = a - ib$

### Forma trigonometrica (forma polare)

- $z = \rho(cos\Theta + i\ sin\Theta)$
	- con $\rho \in \mathbb{R} \geq 0$
	- con $\rho$ angolo, tale che $-\pi < \Theta \leq \pi$ oppure $0 \leq \Theta < 2\pi$
- $z^4 = \rho^4(cos(4\Theta) + i \ sin(4\Theta))$
- $\bar{z} = \rho(cos\Theta - i \ sin\Theta)$ oppure $\rho(\cos(-\Theta) + i\ sin(-\Theta))$
- $|z| = \rho$
- $i = \rho(cos(\pi/2) + i\ sin(\pi/2))$, quindi ($cos$ = $0$ e $sin$ = $1$)
- moltiplicazione: $\rho_1\rho_2(cos(\Theta_1 + \Theta_2) + i\ sin(\Theta_1 + \Theta_2))$
- divisione: $\frac{\rho_1}{\rho_2}(cos(\Theta_1 - \Theta_2) + i\ sin(\Theta_1 - \Theta_2))$

### Forma esponenziale

_non la so :)_

### Equazioni

- semplificare
	- spostando e dividendo
	- applicando proprietà
		- $\overline{z + w}$ = $\bar{z} + \bar{w}$
		- $\overline{zw}$ = $\bar{z} \bar{w}$
		- $|z^2|$ = $z\bar{z}$
		- $|z|$ = $|\bar{z}|$
		- $z + \bar{z}$ = $a$
		- $z - \bar{z}$ = $b$
- trasformare in forma trigonometrica (tutto, anche la $i$)
- mettere a sistema
	- tutti i $\rho$ fuori dalle parentesi
	- tutti gli angoli $\theta$ interni alle parentesi dei $\rho$
		- aggiungere $+2k\pi$ appena messo a sistema
- risolvere per $\rho$ e $theta$
- trovare tutti i $\theta$
	- sostituire $k$ con $1, 2, ...$ (in "modulo" $2\pi$)
	- fino a trovare una soluzione già trovata (a meno di $2k\pi$)
- ricostruire forma trigonometrica per ogni $\theta$ trovato
	- $\rho(cos(\theta) + i\ sin(\theta))$
- calcolare $cos$ e $sin$ e tornare in forma algebrica (basta memorizzare un quadrante):
	- $0° = 0$: $sin = 0$, $cos = 1$
	- $30° = \pi/6$: $sin = 1/2$, $cos = \sqrt{3}/2$
	- $45° = \pi/4$: $sin = \sqrt{2}/2$, $cos = \sqrt{2}/2$
	- $60° = \pi/3$: $sin = \sqrt{3}/2$, $cos = 1/2$
	- $90° = \pi/2$: $sin = 1$, $cos = 0$
- controllare se $0$ è soluzione (e in caso aggiungerla alle soluzioni)
