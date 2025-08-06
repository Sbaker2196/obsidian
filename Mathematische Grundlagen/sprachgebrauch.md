# 1.1 Das Summensymbol: 

$\sum$, der griechische Buchstabe __*Sigma*__, der dem deutsche "S" entspricht. Man spricht dieses Symbol "Summe" aus.
Sofern keine Klammern um die Summen stehen, können sie vertausche werden: 

$$\sum_{1\leq j \leq n} \sum_{1 \leq i \leq m} a_{ij}$$

#### 1.1.2 Aufgabe
Schreiben sie folgenden Ausdruck als Summe: 
$$\sum_{\substack{1 \leq i \leq 3 \\ 4 \leq j \leq 6}}$$
$$=(a_{14} + a_{15} + a_{16}) + (a_{24} + a_{25} + a_{26}) + (a_{34} + a_{35} + a_{a36}) $$

#### 1.1.3 Aufgabe
Schreiben Sie folgenden Ausdruck mit Hilfe des $\sum$ Symbols

$$ = \sum_{\substack{3 \leq j \leq 5 \\ 6 \leq i \leq 8}} $$

#### 1.1.4 Aufgabe
Berechnen Sie $\sum_{i=1}^{5} i^2$

$$ = 1^2 + 2^2 + 3^2 + 4^2 + 5^2 = 1 + 4 + 9+ 16 + 25 = 55$$

# 1.2 Aussagen 

> [!DEFINITION]
> Eine Aussage ist jeder Sat dem die Eigenschaft "wahr" oder "falsch" zugeordnet werden kann 

## 1.2.1 Beispiel
"Es gibt unendlich viele natürliche Zahlen $x,y,z$, so dass die Gleichung $x^2+y^2=z^2$ lösbar ist"

#### 1.2.2 Aufgabe
Sind die folgenden Sätze Aussagen? Begründen Sie. 

1. Es gibt unendliche viele Primzahlen: 
   Diese Aussage ist wahr, behauptet etwas das mit "wahr" oder "falsch" bewertet werde kann
2. $(a+b)^2$
   Dies ist keine Aussage. Der Satz beinhaltet keine Behauptung die "wahr" oder "falsch" sein kann.
3. Für jede reelle Zahlt $a$ gile $a \cdot 0=0$
   Dies ist eine Aussage, sie kann "wahr" oder "falsch" sein.
4. Wenn $12 \leq 9$ so folgt $6 \geq 7$ und $2 \cdot 2 = 4$
   Dies ist eine Aussage, sie kann entweder "wahr" oder "falsch" sein.


## 1.2.1 Junktoren
Aus Aussagen können neue Aussagen gebildet werden. 

- (a) Die Negation ¬: Wenn $A$ eine Aussage ist, so kann $A$ die Eigenschaft wahr oder falsch zugeordnet werden.

> [!DEFINITION]
> Die Negation von $¬A$ von $A$ ist diejenige Aussage, die falsch ist, wenn $A$ wahr istm und die wahr ist, wenn $A$ falsch ist.

| $A$ | $¬A$ |
| :-: | :--: |
|  w  |  f   |
|  f  |  w   |

- (b) die Konjunktion $\wedge$: Seien $A$ und $B$ Aussagen

> [!DEFINITION]
> Die Konjunktion $A \wedge B$ von $A$ und $B$ ist diejenige Aussage, die genau dann wahr ist, wenn $A$ und $B$ beide wahr sind

| $A$ | $B$ | $A \wedge B$ |
| :-: | :-: | :----------: |
|  w  |  w  |      w       |
|  w  |  f  |      f       |
|  f  |  w  |      f       |
|  f  |  f  |      f       |

- (c) Die Disjunktion $\lor$: Seien $A$ und $B$ Aussagen

> [!DEFINITION] 
>  Die Disjunktion $A \lor B$ von $A$ und $B$ ist diejenige Aussage, die genau dann wahr ist wenn mindestens eine der Aussagen A oder B wahr ist.

| $A$ | $B$ | $A \lor B$ |
| :-: | :-: | :--------: |
|  w  |  w  |     w      |
|  w  |  f  |     w      |
|  f  |  w  |     w      |
|  f  |  f  |     f      |
- (d) Die Implikation $\Rightarrow$: Seien $A$ und $B$ Aussagen

>[!DEFINITION]
Die Implikation $A \Rightarrow B$ von $A$ und $B$ ist diejenige Aussage, die genau dann falsch ist, wenn $A$ wahr und $B$ falsch ist.


| $A$ | $B$ | $A \Rightarrow B$ |
| :-: | :-: | :---------------: |
|  w  |  w  |         w         |
|  w  |  f  |         f         |
|  f  |  w  |         f         |
|  f  |  f  |         w         |

- (e) Die Äquivalenz $\iff$: Seien $A$ und $B$ Aussagen

>[!DEFINTION]
>Die Äquivalenz von $A$ und $B$ wird mit $ A \iff B $ bezeichnet und "$A$ genau dann, wenn $B$" oder "$A$ ist äquivalent zu $B$" ausgesprochen


| $A$ | $B$ | $A \iff B$ |
| :-: | :-: | :--------: |
|  w  |  w  |     w      |
|  w  |  f  |     f      |
|  f  |  w  |     f      |
|  f  |  f  |     w      |

#### 1.2.11 Aufgabe
Beweisen Sie, dass die Wahrheitstafeln von $¬(A \lor B)$ und $¬(A) \wedge ¬(B)$ gleich sind


| $A$ | $B$ | $¬A$ | $¬B$ | $¬(A) \wedge ¬(B)$ | $¬(A \lor B)$ |
| :-: | :-: | :--: | :--: | :----------------: | :-----------: |
|  w  |  w  |  f   |  f   |         f          |       f       |
|  w  |  f  |  f   |  w   |         f          |       f       |
|  f  |  w  |  w   |  f   |         f          |       f       |
|  f  |  f  |  w   |  w   |         w          |       w       |
#### 1.2.12 Aufgabe
Beweisen Sie, dass die Wahrheitstafeln von $¬(A \wedge B)$ und $(¬A) \lor (¬B)$ gleich sind

| $A$ | $B$ | $¬A$ | $¬B$ | $(¬A) \lor (¬B)$ | $¬(A \wedge B)$ |
| :-: | :-: | :--: | :--: | :--------------: | :-------------: |
|  w  |  w  |  f   |  f   |        f         |        f        |
|  w  |  f  |  f   |  w   |        f         |        w        |
|  f  |  w  |  w   |  f   |        f         |        w        |
|  f  |  f  |  w   |  w   |        w         |        w        |
>[!DEFINITION]
>Wenn zwei Aussagen dieselben Wahrheitstaflen habe, so sagen wir, dass die Aussagen logisch äquivalent sind

## 1.2.2 Quantoren 

>[!DEFINITION]
>Existenzquantor $\exists$: Das Symbol $\exists$ wir verbal durch "Es gibt ein" ausgedrückt
>
>In der Mathematik wird "Es gibt ein" im Sinne von "Es gibt ***mindestens*** ein" verwendet

Beispiel: 
"Es gibt ein $x$ mit $A$" $\rightarrow$ $\exists{x}: A$ 

>[!DEFINITION]
>Allquantor $\forall$: Das Symbol $\forall$ wird verbal durch "für alle" ausgedrückt
>

Beispiel: 
"Für alle $x$ gilt $A$ " $\rightarrow \forall{x}: A$

#### 1.2.18 Aufgabe
Drücken Sie folgeden Aussagen verbal aus

1. $\exists{n} \in \mathbb{N}:(\forall{m} \in \mathbb{N}: n \leq m)$
	1. Für alle $m$ gibt es ein $n$ mit $n \leq m$
2. $\exists{n} \in \mathbb{N}: n$ teilt $17$
	1. Es gibt eine $n$ mit $n$ teilt $17$ 

#### 1.2.19 Aufgabe 
Drücken Sie folgende Aussagen mit Hilfe von Quantoren aus.

1. Es gibt eine Primzahl $p$, die durch $3$ teilbar ist
	1. $\exists{p}: 3$ teilt $p$
2. Für alle natürlichen Zahlen $n$ gilt $n \geq 1$
	1. $\forall{n}:n \geq 1$
## 1.2.3 Negation von All- und Existenzaussagen

Die Negation der Aussage "Es gibt ein $x$ mit $A$" ist die Aussage "Für alle $x$ gilt die Aussagen $¬A$"
###### 1.2.21 Merkregel
Bei der Negation einer Existenzaussage $\exists{x}:A$ wird der Existienzquantor in einen Allquantor umgewandelt, und die Aussage $A$ wird negiert.
#### 1.2.22 Aufgabe
Wahr oder Falsch? Die Negation der Aussage.

1. "Es gibt eine Primzahl $p$ mit $p$ ungerade und $p \geq 3$" ist "Für alle Primzahlen $p$ gilt $p$ ist ungerade oder $p \leq 3$"
	1. $\exists{p} \; Primzahl: p \; gerade \wedge p \geq 3 = \forall{p} \; Primzahl: p \; ist \; ungerade \; \lor p\leq3$ 
2. "Es gibt eine reelle zahl $x$ mit $x^2 +1 \leq 0$" ist "Für alle reellen Zahlen $x$ gilt $x^2 + 1 \geq 0$"
	1. $\exists{x} \in \mathbb{R}: x^2+1 \le 0=\forall{x} \in \mathbb{R}: x² + 1 \geq 0$
3. "Es gibe eine Zahl $a \in \mathbb{Z}$ mit $a > 3$ und $a<4$" ist "Für alle ganzen Zahlen $a \in \mathbb{Z} gilt $a \leq 3$ oder $a \geq 4$"
	1. $\exists{a} \in \mathbb{Z}: a > 3 \wedge a < 4 = \forall{a} \in \mathbb{Z}: a \leq 3 \lor a \geq 4$

###### 1.2.23 Merkregel
Bei der Negation einer Allaussage $\forall{x}: A$ wird der Allquantor in einen Existenzqauntor umgewandelt, und die Aussage $A$ wird negiert.

#### 1.2.24 Aufgabe
Wahr oder Falsch? Die Negation der Aussage

1. $\forall{n} \geq 3: x^n + y^n + z^n = \exists{n} \geq 3: x^n + y^n \neq z^n$
2. $\forall{x} \in X: x \; gerade \lor x \; Primzahl = \exists{x} \in X: x \; ungerade \lor x \; keine\;Primzahl$
3. $\forall{x} \geq 5: a_n < 0 = \exists{n} \geq 5: a_n \geq 0$
4. $\forall{a} \geq 5 \wedge a \leq : 2a \geq 10 \wedge 2a \leq 14 = \exists{a} \geq 5 \wedge a \leq 7: 2a \leq 10  \lor 2a > 14$

#### 1.2.25 Aufgabe 
Bestimme Sie die Negation folgender Aussagen

1. $\exists{n} \in \mathbb{N}: \{n \leq m | m \in \mathbb{N}\} = \forall{n} \in \mathbb{N}: \{n > m | m \in \mathbb{N}\}$
2. $\forall{y} \in Y: \{\exists{x} \in X | f(x) = y \} = \exists{y} \in Y: \{\forall{x} \in X | f(x) \neq y\}$

## 1.2.4 Vollständige Induktion

Mit $\mathbb{N}_0$ bezeichnen wir die Menge $\{0,1,2,...\}$. Sei $n_0 \in \mathbb{N}_0$ fest gewählt, und $A(n)$ für alle $n \in \mathbb{N}_0, n \geq n_0$ eine Aussage. Angenommen, wir können zeigen: 

- (i) Induktionsanfang: $A(n_0)$ ist richtig
- (ii) Induktionsschritt: Für alle $n \geq n_0$ folgt: Ist $A(n)$ richtig, so auch $A(n+1)$ 

Induktionsbeweise werden in drei Schritten formuliert: 
1. Formulierung des Induktionsanfangs
2. Formulieren der Induktionsannahme $A(n)$ 
3. Induktionsschritt; hier wird gezeigt das $A(n)$ die Aussage $A(n+1)$ impliziert.

#### 1.2.26 Aufgabe
Beweisen sie folgende Aussage mit vollständiger Induktion:
$$\sum_{i=1}^n \frac{1}{i(i+1)} = 1 - \frac{1}{n+1}, n \in \mathbb{N}$$
Sei $n_0 = 1$. Dann gilt $\frac{1}{1(1+1)} = \frac{1}{2} = 1-\frac{1}{1+1}$, der Induktionsanfang.
Sei nun $n \geq 1$. Für den Induktionsschritt nehmen wir an dass $\sum_{i=1}^{n} \frac{1}{i(i+1)}=1-\frac{1}{n+1}$ gitl, und wir müssen herleiten $\sum_{i=1}^{n+1} \frac{1}{i(i+1)}=1-\frac{1}{n+2}$. 
Es gilt: 
$$ 
\sum_{i=1}^{n+1} \frac{1}{i(i+1)} = (\sum_{i=1}^{n} \frac{1}{i(i+1)}) + \frac{1}{(n+1)(n+2)} 
$$
$$
= 1-\frac{1}{n+1} + \frac{1}{(n+1)(n+2)}
$$
$$
= 1- \frac{n+2+1}{(n+1)(n+1)}
$$
$$
=1-(\frac{n+2-1}{(n+1)(n+2)})
$$
$$
= 1-\frac{n+1}{(n+1)(n+2)}
$$
$$
=1-\frac{1}{n+2} \tag{$\blacksquare$}
$$
## 1.2.5 Beweise

- __Das Prinzip der vollständigen Induktion__
	- Beschrieben in Abschnitt [[1.2.4]]. Anwendbar auf Aussagen der Form "Beweisen Sie, dass für alle $n \in \mathbb{N}$ folgendes gilt."  
- __Direkte Beweise__ 
	- In einem so genannten direkten Beweis der Aussage $A \Rightarrow B$ nimmt man die Aussgage $A$ würde gelten und schließt dann, dass auch $B$ gelten muss. Vor Beweisen von Äquivalenzaussagen ($A \Leftrightarrow B$) deutet man durch Pfeile $\Rightarrow$ und $\Leftarrow$ an welche Implikation bewiesen wird
- __Beweis durch Kontraposition__ 
	- Ein Beweis der Aussage $A \Rightarrow B$ durch Kontraposition läuft nach folgendem Scheme ab: Wir nehmen an, es gelte $¬B$ und folgern, dass $¬A$ gilt.
- __Indirekte Beweise (Beweis durch Widerspruch__) 
- 

