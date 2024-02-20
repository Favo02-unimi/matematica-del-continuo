# Esercizi vari filtro

___RICORDARSI SEMPRE LE CONDIZIONI DI ESISTENZA (DOMINIO)___

## Disequazioni con sostituzione

Se troviamo complicato risolvere una disequazione con fattori esponenziali/logaritmici/trigonometrici dobbiamo "tornare" nel mondo della potenze facendo una __sostituzione__

Una volta fatta la sostituzione dobbiamo ovviamente tornare alla disequazione precedente, visto che le soluzioni le vogliamo in $x$ e non nella variabile che abbiamo usato per sostituire

_Primo esempio:_ $2^{2x} - 2^x - 3 > 0$

Facciamo una sostituzione $t = 2^x$ e otteniamo la nuova disequazione $t^2 - t - 3 > 0$

Dopo aver trovato la soluzione $t < t_1 \vee t > t_2$ torniamo in $x$, quindi risolviamo $2^x < t_1 \vee 2^x > t_2$

_Secondo esempio:_ $sin(x)^2 + 2sin(x) +1 \leq 0$

Come prima, andiamo a sostituire $t = \sin(x)$ e otteniamo $t^2 + 2t + 1 \leq 0$

Notiamo come questo è un quadrato di binomio, e un quadrato è $\leq 0$ se e solo se il suo "argomento" è uguale a $0$ (non possiamo andare sotto zero con un quadrato), quindi basta risolvere $t + 1 = 0$, che "riportato" in $x$ equivale a risolvere $\sin(x) = -1$

## Disequazioni esponenziali e logaritmiche

Andiamo a isolare tutti i logaritmi da una parte e tutti i termini noti dall'altra, poi cerchiamo di:
- "unire" tutti i logaritmi in uno, usando la somma o la differenza di logaritmi
- portare dentro al logaritmo tutte le costanti, mettendole all'esponente
- trasformare le costanti in un logaritmo che abbia la stessa base del logaritmo dalla parte opposta

Una volta che abbiamo una situazione simile a $\log_a (\text{qualcosa in x}) \leq \geq \log_a (\text{costanti})$ andiamo a togliere il logaritmo e consideriamo solo gli argomenti, invertendo il senso della disequazione nel caso $0 < a < 1$

_Esempio:_ $log_2 (4x) + log_2 (5) - 3 < 0$

Isoliamo il logaritmo a sinistra e le costanti e destra, poi uniamo i due logaritmi in uno solo

$log_2 (4x \cdot 5) < 3$

Trasformiamo il $3$ in un logaritmo in base $2$, ricordandoci che $c = log_a a^c$ e che $log_a b = c \Longleftrightarrow a^c = b$

$log_2 (20x) < log_2 (2^3)$

Ora che abbiamo due logaritmi uguali andiamo a guardare solo gli argomenti, e visto che $2 > 1$ non invertiamo il senso della disequazione

## Disequazioni esponenziali

Come il capitolo precedente:
- isoliamo gli esponenziali da una parte e le costanti dall'altra parte
- mettiamo tutto nella stessa base
- consideriamo solo gli esponenti, invertendo la disequazione se la base è tra $0$ e $1$

## Disequazioni trigonometriche

_Esempio:_ $\cos (x) \geq 1$

- $\cos$ e $\sin$ hanno codominio $-1 \leq x \leq 1$
- $\cos (x) = 1$ quando $x = 2k\pi$
- $\cos (x) = -1$ quando $x = \pi + 2k\pi$
- $\sin (x) = 1$ quando $x = \frac{\pi}{2} + 2k\pi$
- $\sin (x) = -1$ quando $x = \frac{3\pi}{2} + 2k\pi$

Quando ho disequazioni del tipo $\sin(x) \geq 1$ oppure $\sin(x) \leq -1$ siamo ai valori "limite", quindi andiamo con le uguaglianze viste sopra

Altro appunto: $\sin(2x) \geq 1$ si risolve ponendo l'__ARGOMENTO__ uguale a $\frac{\pi}{2} + 2k\pi$, quindi $2x = \frac{\pi}{2} + 2k\pi$, che va poi risolta per $x$

## Disequazioni con valore assoluto

In una disequazione con valore assoluto abbiamo diverse situazioni:
- il valore assoluto è "da solo": divido il valore assoluto in due "rami", uno dove _IL SUO ARGOMENTO_ è $\geq 0$, uno dove è $< 0$, e poi considero l'unione dei risultati
- ho più valori assoluti che si moltiplicano tra loro: esiste una proprietà che afferma $|a| \cdot |b| = |a \cdot b|$, e una volta fatto questo fare come al punto precedente

## Appartenenza ad un insieme

Una cosa molto utile è calcolare gli estremi di questo insieme, e poi vedere come variano invece gli elementi "interni" al range, usando valori "furbi" come ad esempio gli zeri (valori che annullano l'equazione)

_Esempio:_ $B = \{ | x-1 | \text{ tale che } 0 < x < 2 \}$

Notiamo la presenza di un modulo, quindi avremo solo valori positivi

Vediamo dove il valore assoluto è nullo, e poi tutti gli altri valori saranno sopra

Gli estremi in questo caso sono $|-1| = 1$ e $|1| = 1$

Riusciamo ad andare oltre? No, perché $0$ e $2$ sono equamente distanti dal punto di annullamento $x = 1$, quindi l'insieme $B$ è l'intervallo $[0,1)$

## Aumento e rapporto

Se parliamo di _aumento_ vogliamo la differenza tra il valore nuovo e il valore vecchio

Se parliamo di _rapporto_ vogliamo il rapporto tra il valore nuovo e il valore vecchio

_Esempio:_ "Se raddoppio il lato di un triangolo equilatero, di quanto aumenta la sua area?"

Trucco utile nei triangoli equilateri: usare il teorema di Pitagora $a^2 + b^2 = c^2$ per trovare l'altezza, dove $a,b$ sono i cateti e $c$ è l'ipotenusa
