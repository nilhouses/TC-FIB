# Deterministic finite automata (DFA)

## Exercise 1

![Exercise 1](./PNG/01.png)

---

## Exercise 2

![Exercise 2](./PNG/02.png)

---

## Exercise 3

![Exercise 3](./PNG/03.png)

---

## Exercise 4

![Exercise 4](./PNG/04.png)


Es pot fer a partir d'un NFA:

- {1,a = 1}, {1,b = 1}, {1,a = 2}

---

## Exercise 5

![Exercise 5](./PNG/05.png)

---

## Exercise 6

![Exercise 6](./PNG/06.png)

---

## Exercise 7

![Exercise 7](./PNG/07.png)

---

## Exercise 8

![Exercise 8](./PNG/08.png)

---

## Exercise 9

![Exercise 9](./PNG/09.png)

---

## Exercise 10

![Exercise 10](./PNG/10.png)

---

## Exercise 11

![Exercise 11](./PNG/11.png)

Semblant al 10, ara calia veure que b es equivalent a 2a1b i eliminar l'estat pou.

---

## Exercise 12

![Exercise 12](./PNG/12.png)

A diferència del 10 i l'11, que preguntaven per prefixos, el 12 pregunta infixos. Prenc totes les combinacions per a paraules de longitud 2 i a partir d'aquí, amb el que m'entri puc considerar totes les paraules de longitud 3. Si la  paraula de longitud 3 no compleix la pemissa descarto el mot sencer, sino, prenc els 2 últims caràcters llegits i continuo.

Casos:

	aaa - -> Descarto
	aab +
	aba + 
	abb - -> Descarto
	baa +
	bab - -> Descarto
	bba - -> Descarto
	bbb +

---

## Exercise 13

![Exercise 13](./PNG/13.png)

El mateix que el 12 (a primera vista) però en lloc de descartar 1a2b cal descartar 1a1b.

---

## Exercise 14

![Exercise 14](./PNG/14.png)

---

## Exercise 15

![Exercise 15](./PNG/15.png)

---

## Exercise 16

![Exercise 16](./PNG/16.png)


---

## Exercise 17

![Exercise 17](./PNG/17.png)
![Exercise 17](./PNG/17_1.png)

Intersecció de varis DFAs. Es poden obtenir els 3 DFAs simples i calcular-ne l'intersecció. Sense minimitzar són 4*4*4 = 64 estats en total.

---

## Exercise 18

![Exercise 18](./PNG/18.png)

---

## Exercise 19

![Exercise 19](./PNG/19.png)

Busco b's consecutives amb alguna cadena amb menys de 2 a's

---

## Exercise 20

![Exercise 20](./PNG/20.png)

Múltiples de 2 (acabats en 0) i mot buit. 

---

## Exercise 21

![Exercise 21](./PNG/21.png)

Múltiples de 3, 3 estats:
	x0 = 2x
	x1 = 2x+1
Llegir un 0 és multiplicar per 2 en binari, llegir un 1 és multiplicar per 2 i sumar 1.

---

## Exercise 22

![Exercise 22](./PNG/22.png)

Invertir els estats finals i no finals del DFA anterior.

---

## Exercise 23

![Exercise 23](./PNG/23.png)

Múltiples de 4. L'estat 3 és prescindible al ser equivalent amb l'estat 1.

---

## Exercise 24

![Exercise 24](./PNG/24.png)

Invertir els estats finals i no finals del DFA anterior.

---

## Exercise 25

![Exercise 25](./PNG/25.png)

Múltiples de 5.

---

## Exercise 26

![Exercise 26](./PNG/26.png)

Tota subcadena de longitud 3 ha de tenir exactament dues a's. Es pot fer per casos:

Sigui _ el caràcter a llegir després dels dos caràcters anteriors:

- {bb_} es rebutja (Impossible arribar a |y|<sub>a</sub> = 3 independentment d'_).
- {ba_,ab_} s'accepta si _ = a, es rebutja en cas contrari.
- {aa_} s'accepta si _ = b, es rebutja en cas contrari.
---

## Exercise 27

![Exercise 27](./PNG/27.png)

---

## Exercise 28

![Exercise 28](./PNG/28.png)

Es pot calcular el 27 complementari i negar-lo, per poder fer el revers. S'obté un NFA, que caldrà passar a DFA i determinitzar-lo.

---

## Exercise 29

![Exercise 29](./PNG/29.png)

Trobar paraules amb {ab,ba i bb}. Es pot fer de cap pensant bé cada estat.

---

## Exercise 30

![Exercise 30](./PNG/30.png)

Cal comptar, els DFAs no poden comptar, però puc tenir constància de la diferència. es pot veure com una funció f:

f(0) = f(1) = 0

f(i) = |w[1]...w[i]|<sub>ab</sub> - |w[1]...w[i]|<sub>ba</sub>

<img src="./PNG/30_1.png" alt="Exercise 30" width="800"/>

---

## Exercise 31

![Exercise 31](./PNG/31.png)

---

## Exercise 32

![Exercise 32](./PNG/32.png)

---

## Exercise 33

![Exercise 33](./PNG/33.png)


Per casos.

---

## Exercise 34

![Exercise 34](./PNG/34.png)

---

## Exercise 35

![Exercise 35](./PNG/35.png)


Pensar per casos.

---

## Exercise 36

![Exercise 36](./PNG/36.png)

Conté alguna seqüència amb 3 b més que a.

---

## Exercise 37

![Exercise 37](./PNG/37.png)

---

## Exercise 38

![Exercise 38](./PNG/38.png)

Ara el nombre el mot ha de tenir el mateix nombre d'as i b's a les dues parts:

	λ 	accepta
	|a	accepta
	|b 	accepta
	a|b 	accepta
	b|a	accepta
	bb|	accepta
	|aa	accepta	
	|aaa	accepta
	...
Sempre es podrà trobar una descomposició xy d'un mot w de manera que |x|<sub>a</sub> = |y|<sub>b</sub>.

---

## Exercise 39

![Exercise 39](./PNG/39.png)

Qualsevol mot pertany al llenguatge.
