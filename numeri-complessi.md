# Numeri complessi

L'insieme dei numeri complessi $\mathbb{C}$ viene introdotto come estensione dell'insieme dei numeri reali $\mathbb{R}$ per permette la risoluzione di alcune equazioni che nell'insieme dei reali non è possibile risolvere, come ad esempio $x^2 + 1 = 0$

## Piano complesso

Il __piano complesso__ è un piano dove sull'asse delle $X$ è presente l'insieme dei numeri reali, mentre l'asse delle $Y$ è l'asse immaginario, ovvero multipli dell'__unità immaginaria__ $i$

Ogni punto di questo piano complesso individua un numero complesso

## Forme

### Forma algebrica

Ogni punto del piano complesso può essere espresso nella forma $a + ib$, dove $a$ rappresenta la __parte reale__ e $b$ rappresenta la __parte immaginaria__

Banalmente, $a$ è la proiezione del punto complesso sull'asse reale e $b$ è la proiezione del punto complesso sull'asse immaginario

Un numero importante che possiamo trovare partendo da un numero complesso è il suo __coniugato__ $\bar{z} = a - ib$: questo numero, visto nel piano complesso, ha stessa parte reale ma parte immaginaria opposta, quindi in poche parole è il simmetrico rispetto all'asse reale del numero $z$

### Forma trigonometrica (forma polare)

La __forma trigonometrica__, detta anche _forma polare_, cerca di definire il punto nel piano complesso in termini di seno e coseno

Come prima cosa chiamiamo $\rho = |z| = \sqrt{a^2 + b^2}$ la distanza tra l'origine e il punto complesso e $\theta$ l'angolo tra l'asse reale e la retta che congiunge l'origine con il punto (se vado in senso anti-orario ho segno positivo, altrimenti negativo)

Poi, riscriviamo la forma algebrica usando le coordinate polari: infatti, la proiezione sull'asse reale $a$ vale $\rho \cos(\theta)$ e la proiezione $b$ sull'asse immaginario $b$ vale $\rho \sin(\theta)$

Il numero $z = a + ib$ diventa $z = \rho \cos(\theta) + i \rho \cos(\theta) = rho (\cos(\theta) + i \sin(\theta))$

Per il coniugato $\bar{z}$ la formula è analoga, solo che l'angolo diventa $-\theta$, essendo specchiato rispetto all'asse reale, quindi $\bar{z} = \rho (\cos(-\theta) + i \sin(-\theta))$

Può essere comodo ricordare che:
- $\cos(x) = \cos(-x)$ perché il coseno è una funzione pari
- $\sin(x) = -\sin(-x)$ perché il seno è una funzione dispari

Possiamo anche definire $i$ con la forma trigonometrica: infatti, nel piano complesso $i$ si trova a distanza $1$ dall'origine con un angolo $\theta = \frac{\pi}{2}$, quindi $z = 1(\cos(\frac{\pi}{2}) + i \sin(\frac{\pi}{2})) = 1 (0 + i \cdot 1) = i$

Possiamo definire tre operazioni con la forma esponenziale:
- __prodotto__: $z_1 \cdot z_2 = \rho_1 \rho_2 \cdot (\cos(\theta_1 + \theta_2) + i \sin(\theta_1 + \theta_2))$
- __divisione__: $\frac{z_1}{z_2} = \frac{\rho_1}{\rho_2} \cdot (\cos(\theta_1 - \theta_2) + i \sin(\theta_1 - \theta_2))$
- __elevamento a potenza__: detta anche __formula di De Moivre__, è un caso particolare del prodotto, che infatti viene eseguito $n$ volte per lo stesso numero $z$

  La formula afferma che $z^n = p^n (\cos(n \theta) + i \sin(n \theta))$


### Forma esponenziale

Forma abbastanza inutile utilizzata solo per dare una forma compatta alla forma trigonometrica: infatti, il generico numero $z = a + ib = \rho (\cos(\theta) + i \sin(\theta))$ viene scritto come $e^{i \theta}$ in forma esponenziale

## Come risolvere le equazioni

La prima cosa da fare ogni volta che si risolve un'equazione complessa è controllare se $z = 0$ è soluzione

Una volta fatto ciò, si considerano solo i valori di $z \neq 0$ e si possono fare diverse cose:
- rimuovere eventuali $\bar{z}$ dall'equazione, moltiplicando entrambi i membri per $z$, ricordando che:
	- $z \cdot \bar{z} = |z|^2$
	- $|z|$ = $|\bar{z}|$
	- $z + \bar{z}$ = $a$
	- $z - \bar{z}$ = $b$
- spostare tutte le $|z|$ da una parte e tutti i "termini noti" dall'altra
- trasformare tutto in forma trigonometrica
- scrivere un sistema di $2$ equazioni
	- la prima equazione mette in uguaglianza i due moduli, ovvero le due distanze dei punti dall'origine: questo è banale perché per avere due punti uguali devo avere la stessa distanza dall'origine
	- la seconda equazione mette in uguaglianza i due angoli con l'aggiunta di $2 k \pi$: questo perché ogni $2 \pi$ giri si ritorna nella stessa situazione
- risolvere la prima equazione per $\rho$
- risolvere la seconda equazione per $\theta$ mettendo dei valori di $k$ consecutivi (si consiglia di partire da $0$ e arrivare a $n-1$) per ottenere tutte le soluzioni
- per ogni valore di $\theta$ trovato scrivere il numero $z = \rho (\cos(\theta) + i \sin(\theta))$ corrispondente
- in caso venga chiesta la forma trigonometrica calcolare seno e coseno degli angoli $\theta$ inseriti
