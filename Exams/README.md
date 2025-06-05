# Exams

## [Exam](https://racso.lsi.upc.edu/juezwsgi/exam?examid=15) on CFGs, March 27th, 2015 
## Exercise 1
![Exercise 1](./PNG/01.png)
```text
S -> aSa | bSb | b |
```
### Exercise 2
![Exercise 2](./PNG/02.png)
```text
S -> bST | aAT
A -> bAT | aBT
B -> bBT | c
T -> a|b
```
### Exercise 3

![Exercise 3](./PNG/03.png)
```text
S ->  XY | aXbYc
X -> aaXb |
Y -> bYcc |
```
## [Exam](https://racso.lsi.upc.edu/juezwsgi/exam?examid=56) on CFGs, March 29th, 2016 
## Exercise 1
![Exercise 1](./PNG/04.png)
```text
S -> aSa | bSb | aXb | bXa
X -> TXT | 
T -> a|b
```

### Exercise 2
![Exercise 2](./PNG/05.png)
```text
S -> BaXbA| BcA 
X -> BaSbA
A -> aA |
B -> bB |
```
## [Exam](https://racso.lsi.upc.edu/juezwsgi/exam?examid=129) on DFAs and CFGs, April 21st, 2021 
## Exercise 1
![Exercise 1](./PNG/06.png)

## Exercise 2
![Exercise 2](./PNG/07.png)

## Exercise 3
![Exercise 3](./PNG/08.png)
Aquest es pot fer minimitzant.
```text
     a    b
0A  1A  _1B +
1A  2A   0B
_1B 0A  _2C
2A   P   1B
0B  1A  _1C +
_2C _1B  P
P    P   P 
1B  2A   0C
_1C 0A  P
0C  1A  P +
```

## Exercise 4
![Exercise 4](./PNG/09.png)
```text
S -> aSa | bXb | a |
X -> aXa | bYb | b
Y -> aYa | bSb  
```

## Exercise 5
![Exercise 5](./PNG/10.png)
```text

S -> AC | YC | AXC | XYC

Y -> bYc | bc
X -> aXb | ab

A -> aA |
C -> cC |
```
Casos:  
- 1) j = 0
- 2) i = 0 (|b| <= |c|)
- 3) 0 < j <= i
- 4) j > i > 0  

Y fa b = c, a S ja poso les Cs extra  
X fa a = b, amb |a| = |b| > 0

## Exercise 6
![Exercise 6](./PNG/11.png)
```text
S -> X | Y | Z | ETX

X -> TX | 
Y -> XcY| XcXcX
T -> a|b

Z -> aZa | bZb | aWb | bWa
W -> TWT | TXc | c

E -> TET | c
```
Casos:  
- 1) mots sense c's
- 2) mots amb 2 c's o més
- 3) |y| <= |x| i yR no es prefix de x
- 4) |y| > |x| i yR no es prefix de x

X i Y fan casos *1* i *2*   
Z i W fan *|y| <= |x|*  
E fa *|y| = |x|*, a S ja es posa *y > x*  

## [Exam](https://racso.lsi.upc.edu/juezwsgi/exam?examid=102) on DFAs and CFGs, November 8th, 2019 
## Exercise 1
![Exercise 1](./PNG/12.png)

### Exercise 2
![Exercise 2](./PNG/13.png)

### Exercise 3
![Exercise 3](./PNG/14.png)

### Exercise 4
![Exercise 4](./PNG/15.png)
```text
S -> BaX
X -> BaXbA | BcA

B -> bB |
A -> aA |
```

### Exercise 5
![Exercise 5](./PNG/16.png)
```text
S -> XY
X -> a | bXX
Y -> aY | bY |
```

### Exercise 6
![Exercise 6](./PNG/17.png)
```text
S -> X | Y | Z | ETX

X -> TX | 
Y -> XcY| XcXcX
T -> a|b

Z -> aZa | bZb | aWb | bWa
W -> TWT | TXc | c

E -> TET | c
```
Casos:  
- 1) sense c (1 mot buit)
- 2) mots amb 2 c's o més
- 3) |x| == |y| (i W!= wcwR)
- 4) |x| != |y| (i W!= wcwR)

X fa cas *1*   
Y fa cas *2*     
Z i Q fan cas *3*  
W i R fan cas *4*  

## [Exam](https://racso.lsi.upc.edu/juezwsgi/exam?examid=55) on DFAs, February 29th, 2016 
## Exercise 1
![Exercise 1](./PNG/18.png)

### Exercise 2
![Exercise 2](./PNG/19.png)

### Exercise 3
![Exercise 3](./PNG/20.png)

### Exercise 4
![Exercise 4](./PNG/21.png)

### Exercise 5
![Exercise 5](./PNG/22.png)

