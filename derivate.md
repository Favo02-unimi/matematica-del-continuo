# Derivate

## Derivate come operatore lineare

L'operatore derivata è un __operatore lineare__, ovvero è possibile:
- "dividere" la derivata di una somma come somma delle singole derivate
- "dividere" la derivata di un prodotto con uno scalare come prodotto tra lo scalare e la derivata

$$(a \cdot f(x) + b \cdot g(x))' = a \cdot f'(x) + b \cdot g'(x)$$

## Derivate immediate

Le derivate ovviamente vanno intese nel loro dominio di definizione (`CE`)

| $f(x)$ | $f'(x)$ |
| :----: | :-----: |
| $n \in \mathbb{R}$ | $0$ |
| $x$ | $1$ |
| $x^a$ | $a x^{a-1}$ |
| $e^x$ | $e^x$ |
| $a^x$ | $a^x \ln(a)$ |
| $\ln(x)$ | $\frac{1}{x}, \, x > 0$ |
| $\ln(\|x\|)$ | $\frac{1}{x}, \, x \neq 0$ |
| $\log_a(x)$ | $\frac{1}{x \ln(a)}, \, x > 0$ |
| $\|x\|$ | $\frac{\|x\|}{x}, \, x \neq 0$ |
| $\sin(x)$ | $\cos(x)$ |
| $\cos(x)$ | $-\sin(x)$ |
| $\tan(x)$ | $\frac{1}{\cos^2(x)}, \, x \neq \frac{\pi}{2} + k\pi$ |
| $\cot(x)$ | $-\frac{1}{\sin^2(x)}, \, x \neq k\pi$ |
| $\arcsin(x)$ | $\frac{1}{\sqrt{1-x^2}}, \, x \in [-1,1]$ |
| $\arccos(x)$ | $-\frac{1}{\sqrt{1-x^2}}, \, x \in [-1,1]$ |
| $\arctan(x)$ | $\frac{1}{1+x^2}$ |

## Derivate "avanzate"

| $f(x)$ | $f'(x)$ |
| :----: | :-----: |
| $f(g(x))$ | $f'(g(x)) \cdot g'(x)$ |
| $f(x) \cdot g(x)$ | $f'(x) \cdot g(x) + f(x) \cdot g'(x)$ |
| $\frac{f(x)}{g(x)}$ | $\frac{f'(x) \cdot g(x) - f(x) \cdot g'(x)}{g^2(x)}$ |

## Derivata con definizione

Nel caso ci venga richiesto di calcolare la derivata di una funzione $f(x)$ tramite la sua definizione dobbiamo calcolare il limite del rapporto incrementale $\displaystyle\lim_{h \rightarrow 0} \frac{f(x+h) - f(x)}{h}$

Nel caso ci venga chiesto anche il calcolo della derivata in un punto $x_0$ andiamo a sostituire questo punto nella derivata trovata
