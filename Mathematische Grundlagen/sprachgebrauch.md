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
	- Manchmal zieht man einen Beweis der Aussage $A \Rightarrow B$ auch folgendermaßen auf: Es gelte $A$. Angenommen, $B$ wäre falsch. Dann schließt man auf einen Widerspruch. Dieser Widerspruch zeigt, dass die Annahme "$B$ ist flasch." selbst falsch war, uns es folgt, das $B$ richtig sein muss.
- __Ringschlüsse__
	- Oft müssen Aussagen der Form:
	  "wenn $A$ gilt, dann sind die Aussage $(i), (ii) \; und \; (iii)$ äquivalent" bewiesen werden. Am schnellsten geht es wenn $(i) \Rightarrow (ii), (ii) \Rightarrow (iii) \; und \; (iii) \Rightarrow (i)$ bewiesen wird.

## 1.2.6 Korollar

Satz = tiefes, wichtiges Resultat
Proposition = Wichtige Ergebnisse, nicht so wichtig wie eine Satz
Lemma = Besonders wichtiger Schlüsselgedanke
Korollar = Folgerung aus einem Satz oder einer Proposition bzw. aus derem Bewei

## 1.3 Mengen

>[!DEFINITION]
>Einige wichtige Begriffe rund um Mengen definiert:
>(i) Eine Menge $N$ heißt Teilmenge einer Menge $M$, wenn jedes Element aus $N$     auch zu $M$ gehört, wenn also $\forall{x}:(x \in \mathbb{N}|x \in M)$ um eine       Teilmengenbeziehung auszudrücken benutzen wir das Symbol $\subseteq$.
>(ii) Zwei Mengen $M$ und $N$ sind gleich falls $M \subseteq N$ und $N \subseteq M$,       wenn also $M$ und $N$ die gleichen Elemente enthalten.
>(iii) Die leere Menge ist diejenige Menge, die kein einziges Element besitzt. Sie        wird mit $\emptyset$ bezeichnet.

## 1.3.2 Beispiel

Die Schreibweise $M := \{2'|i \; ist \; eine \; gerade \; Zahl\}$ bedeutet:
$M$ wird definiert als die Menge $\{...,2^{-6}, 2^{-4}, 2^{-2}, 2^0, 2^2, 2^4, 2^6,...\}$

>[!DEFINITION]
>Seien $M$ und $N$ Mengen.
>(i) Die Vereinigung von $M$ und $N$ wird mit $\cup$ bezeichnet und ist definiert als $M \cup N := \{x|x \in M \; und \; x\ in N\}$
>(ii) Der Durchschnitt von $M$ und $N$ wird mit $\cap$ bezeichnet und ist definiert als $M \cap N := \{x|x \in M \; und \; x\ in N\}$
>(iii) Die Differenzmenge von $M$ und $N$ wird mit $\setminus$ bezeichnet und ist definiert als $M \setminus N := \{x|x \in M \; und \; x\ in N\}$
>(iv) Zwei Mengen $M$ und $N$ heißen disjunkt falls $M \cap N = \emptyset$ gilt

### 1.3.4 Beispiele
(a.) Seien $M:=\{1,2,3,4,5,6\}$ und $N := \{4,5,6,7,8\}$. Dann gilt
$$ 
	M \cup N = \{1,2,3,4,5,6,7,8\}
$$
$$
	M \cap N = \{4,5,6\}
$$
$$
	M \setminus N = \{1,2,3\}
$$
(b.) Sei $\mathbb{Z}$ die Menge der ganzen Zahlen $= \{..., -2, -1, 0, 1, 2,...\}$. Dann gilt: 

$$
	\mathbb{N} \cup \mathbb{Z} = \mathbb{Z}
$$
$$
	\mathbb{N} \cap \mathbb{Z} = \mathbb{N}
$$
$$
	\mathbb{N} \setminus \mathbb{Z} = \emptyset
$$
$$
	\mathbb{Z} \setminus \mathbb{N} = {...,-2,-1,0}
$$
>[!DEFINITION]
>Besitzt eine Menge $M$ nur endlich viele Elemente so sagen wir, das $M$ eine engliche Menge ist. Anderenfalls nennen wir $M$ eine unendliche Menge

#### 1.3.6 Aufgabe
1. Wenn $M \setminus N = \emptyset$ für zwei Mengen $M$ und $N$ gilt, so folgt $M=N$ 
	1. Wahr. BEsp.: Sei $M := \{¸1,2} und $N := {1,2,3}$ dann ist $M \setminus N = \emptyset$ aber $M \neq N$ 
2. Wenn $M \cup N$ endlich ist, dann sind $M$ und $N$ endlich 
	1. Wahr. Angenommen $M$ wäre unendlich und $N$ endlich, dann ist $M \cup N$ unendlich. Denn wenn $M := \{1,2,3,...,\infty\}$ und $N := \{1,2,3\}$ dann ist $M \cup N$ unendlich
3. Wenn $M \cap N$ endlich ist, dann sind $M$ und $N$ endlich
	1. Falsch. Wenn $M := \{1,2,3,...,\infty\}$ und $N := \{1,2,3\}$ dann ist $M \cap N = \{1,2,3\}$ und somit endlich obwohl $M$ unendlich ist.

>[!DEFINITION]
>Sei $M$ eine Menge. Wir nennen $|M|$ die Mächtigkeit oder die Kardinalität von $M$

#### 1.3.8 Aufgabe
1. Wenn $|M \cup N| = |M| + |N|$ für endliche Mengen $M$ und $N$, so folgt $M \cap N = \emptyset$ 
	1. Wahr. Seien $M$ und $N$ endlichen Mengen. Wenn $M$ und $N$ leer sing , gilt: $|M \cup N| = |M| + |N|$, die Voraussetzung und die Behauptung für diesen Spezialfall.
	   Seien nun $M$ und $N$ nicht leere, endliche Mengen. Dann haben $M$ und $N$ die Form $M = \{x_i,...,x_m\}$ und $N = \{y_1,...,y_n\}$ für gewisse $m,n \in \mathbb{N}$. Sei $|M \cup N| = |M| + |N|$. Dann hat $M \cup N$ die Form $\{x_1,...,x_m,y_1,...,y_n\}$, es gilt also $x_i \neq y_j$ für alle $1 \leq i \leq m$ und $1 \leq j \leq n$. Somit gilt $x_i \neq N$ für alle $1 \leq i \leq m$ und $y_j \notin M$ für alle $1 \leq j \leq n$. Es folgt also $M \cap N = \emptyset$, die Behaptung.
	2. Seien $M$ und $N$ endliche Mengen, So müssen drei Fälle betrachtet werden: 
	   3. Sind $M$ und $N$ leer, so ist $M \cap N = \emptyset$ 
	   4. Sei $M := \{x_i,...,x_m\}$ und $N := \{y_j,...,y_n\}$ wobei $y \notin N$ und $x \notin N$ und $1 \leq i \leq n$ sowie $1 \leq j \leq n$ so wäre $M \cap N = \emptyset$ und $|M \cup N| = |M|  + |N|$ 

>[!DEFINITION]
>Sind $M$ und $N$ nicht leere Mengen, so definieren wir die Produktmenge von $M \times N$ von $M$ und $N$ durch $M \times N := \{(m,n)|m \ in M \; und \; n \in N\}$
>*Gleichheit geordneter Paare: $(m,n) = (m', n')$ genau dann wenn $m=m'$ und $n=n'$ 

#### 1.3.10 Aufgabe 
Sind $M$ und $N$ endliche, nicht leere Mengen, so ist |M \times N| = |M| \cdot |N|

Wahr. Sei $M := \{x_i,...,x_m\}$ und sei $N := \{y_j,...,y_n\}$. Sei $x \in M$. Es gibt n geordnete Paare $(x_i, y_1),...,(x_i,y_n)$ und da es $m$ Möglichkeiten für $x_i$ gibt, folgt, dass es $m \cdot n$ Paare in $M \times N$ gibt.

![[Screenshot 2025-08-07 at 01-11-24 Desmos Graphing Calculator.png]]