# Context-Free Grammars (CFG)

## Exercise 1

![Exercise 1](./PNG/01.png)
```text
S -> aSb |
```
---

## Exercise 2

![Exercise 2](./PNG/02.png)
```text
S -> aSb | acb
```
---

## Exercise 3

![Exercise 3](./PNG/03.png)
```text
S -> AB
A -> aA |
B -> aBb |
```
A i B eviten ambigüitats.

---

## Exercise 4

![Exercise 4](./PNG/04.png)
```text
S -> AB
A -> aAb |
B -> bB |
```
---

## Exercise 5

![Exercise 5](./PNG/05.png)
```text
S -> XY
X -> aXbb |
Y -> bY | 
```
---

## Exercise 6

![Exercise 6](./PNG/06.png)
```text
S -> aTb | T
T -> aTbb | aT |
```
---

## Exercise 7

![Exercise 7](./PNG/07.png)
```text
S -> aSbb | T
T -> aT | ab |
```
---

## Exercise 8

![Exercise 8](./PNG/08.png)
```text
S -> aaSb | X
X -> aXb | 
```
---

## Exercise 9

![Exercise 9](./PNG/09.png)
```text
S -> AB
A -> aA |
B -> bB |
```
---

## Exercise 10

![Exercise 10](./PNG/10.png)
```text
S -> aSc | X
X -> aXb |
```
---

## Exercise 11

![Exercise 11](./PNG/11.png)
```text
S -> XY
X -> aXb |
Y -> bYc |
```
---

## Exercise 12

![Exercise 12](./PNG/12.png)
```text
S -> XC | AY | Z

X -> aXb |
Y -> bYc |
Z -> aZc | B

A -> aA|
B -> bB |
C -> cC |
```
---

## Exercise 13

![Exercise 13](./PNG/13.png)
```text
S -> XY
X -> aXa | Yb
Y -> ZY |
Z -> Za | b
```
---

## Exercise 14

![Exercise 14](./PNG/14.png)
```text
S -> aSa | Sb | b
```
---

## Exercise 15

![Exercise 15](./PNG/15.png)
```text
S -> X | Y
X -> aXa | Sb | b
Y -> Ya | Sb | b
```
---

## Exercise 16

![Exercise 16](./PNG/16.png)
```text
S -> aSa | bSb | a | b | 
```
---

## Exercise 17

![Exercise 17](./PNG/17.png)
```text
S -> aXa| bSb | a | b |
X -> bYb | aXa | a |
Y -> bSb | b |
```
---

## Exercise 18

![Exercise 18](./PNG/18.png)
```text
S -> aBa | bAb
A -> bAb | aTa | a 
B -> aBa | bTb | b

T -> aTa | bTb | a | b |
```
---

## Exercise 19

![Exercise 19](./PNG/19.png)
```text
S -> aXa | bSb
X -> bYb | aXa | b
Y -> a | aTa | bSb

T -> aTa | bTb | b | a |
```
---

## Exercise 20

![Exercise 20](./PNG/20.png)
```text
S -> (S)|SS|
```
---

## Exercise 21

![Exercise 21](./PNG/21.png)
```text
S -> SS | (S) | [S] |
```
---

## Exercise 22

![Exercise 22](./PNG/22.png)
```text
S -> (S)S | 
```
---

## Exercise 23

![Exercise 23](./PNG/23.png)
```text
S -> (S)S | [S]S |
```
---

## Exercise 24

![Exercise 24](./PNG/24.png)
```text
S -> aSbS | bSaS |
```
---

## Exercise 25

![Exercise 25](./PNG/25.png)
```text
S -> CaSbS | CbSaS | C 
C -> cC |
```
---

## Exercise 26

![Exercise 26](./PNG/26.png)
```text
S -> aScS | cSaS | bScS | cSbS | 
```
---

## Exercise 27

![Exercise 27](./PNG/27.png)
```text
S -> bSbSaS | bSaSbS | aSbSbS | 
```
---

## Exercise 28

![Exercise 28](./PNG/28.png)
```text
S -> aAbS | bBaS |
A -> aAbA | 
B -> bBaB |
```
---

## Exercise 29

![Exercise 29](./PNG/29.png)
```text
S -> CaAbS | CbBaS | C
A -> CaAbA | C
B -> CbBaB | C
C -> cC | 
```
---

## Exercise 30

![Exercise 30](./PNG/30.png)
```text
S -> cXS | bYS | aYS |

X -> a| b | cXX
Y -> c | aYY | bYY
```
---

## Exercise 31

![Exercise 31](./PNG/31.png)
```text
S -> aBBS | bAS | bXBS |
B -> b | aBBB
A -> bX | bAA 
X -> a | bAX
```
---

## Exercise 32

![Exercise 32](./PNG/32.png)
```text
S -> BaSbA | BcA
A -> aA |
B -> bB |
```
---

## Exercise 33

![Exercise 33](./PNG/33.png)
```text
S -> BAabSbaAB | BAcAB
B -> bB |
A -> aA |
```
---

## Exercise 34

![Exercise 34](./PNG/34.png)
```text
S -> aA | bS | F
A -> aA | bB | F
B -> bS | aC | F

C -> Db | Ca
D -> Ea | Db
E -> Ca | Yb

F -> c | Fa | Gb 
G -> Ha | Gb | c
H -> Fa | c

X -> aY | bX | G
Y -> bZ | aY | G
Z -> bX | aD | G
```
---

## Exercise 35

![Exercise 35](./PNG/35.png)
```text
S -> aSa | bSb | T
T -> aT | bT | c 
```
---

## Exercise 36

![Exercise 36](./PNG/36.png)
```text
S -> aS | bS | X
X -> aXa | bXb | c
```
---

## Exercise 37

![Exercise 37](./PNG/37.png)
```text
S -> aXT | bST
X -> aYT | bST
Y -> TYT | c

T -> a|b
```
---

## Exercise 38

![Exercise 38](./PNG/38.png)
```text
S ->  X | Y | Z
X -> aXb | aX | a
Y -> aYb |Yb | b
Z -> WbWaW
W -> aW |bW |
```
Els complementaris d'un llenguatge es fan per casos:
- X: |w|<sub>a</sub> > |w|<sub>b</sub>
- Y: |w|<sub>a</sub> < |w|<sub>b</sub>
- Z: Mots amb alguna b abans que una a
---

## Exercise 39

![Exercise 39](./PNG/39.png)
```text
S -> aSb | aXa | bXb | bXa | a | b
X -> aX | bX | 
```
---

## Exercise 40

![Exercise 40](./PNG/40.png)
```text
S -> aSa | bSb | aTb | bTa
T -> aT | bT | 
```
---

## Exercise 41

![Exercise 41](./PNG/41.png)
```text
S -> XbaX | XcaX | XcbX | YC | Z

X -> aX | bX | cX |
Y -> aYb | aA | Bb
Z -> aZc | aAB | BCc

A -> aA |
B -> bB |
C -> cC |
``` 
---

## Exercise 42

![Exercise 42](./PNG/42.png)
```text
S -> X | Y | Z | T
				
X -> AcAcA
A -> aA | bA | cA|

Y -> aY | bY |

Z -> aZa|aZb|bZa|bZb|aYc|bYc|cYa|cYb

T -> LaY | MbY
M -> DMD | aYc 
L -> DLD | bYc

D -> a | b
```
Casos:
- X: |w|<sub>c</sub> >= 2 
- Y: |w|<sub>c</sub> = 0, (i el mot buit λ) 
- Z: |w|<sub>c</sub> = 1 ∧ w = xcy, x != y
- T: |w|<sub>c</sub> = 1 ∧ w = xcy, ∃ i tq x[i] != y[i]
Z i T es complementen, cap de les dues cobreix tots els casos tal i com està implementat.
---

## Exercise 43

![Exercise 43](./PNG/43.png)
```text
E -> N |E O E | (E)
O -> + | - | * | /

N -> 0D | 1D | 2D | 3D | 4D | 5D | 6D | 7D | 8D | 9D 
D -> 0D | 1D | 2D | 3D | 4D | 5D | 6D | 7D | 8D | 9D | 
```
---

## Exercise 44

![Exercise 44](./PNG/44.png)
```text
E -> E+T | E-T | T
T -> T*F | T/F | F
F -> (E) | D

D -> 0D | 1D | 2D | 3D | 4D | 5D | 6D | 7D | 8D | 9D | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9

```
Ordeno per prioritat pels operadors amb associativitat a l’esquerra <br />
'+' '-'  <br />
'*' '/'  <br />
'('')'   <br />

---

## Exercise 45

![Exercise 45](./PNG/45.png)
```text
S -> XCD | YD | Z

X -> aXb |
Y -> aYc | B
Z -> aZd | BC

B -> bB |
C -> cC |
D -> dD |

```
Casos:
- X: |w|<sub>a</sub> =  |w|<sub>b</sub> 
- Y: |w|<sub>a</sub> =  |w|<sub>c</sub> 
- Z: |w|<sub>a</sub> =  |w|<sub>d</sub> 

---
