# WP-Reductions
<!-- Alguns caràcters 
  EXISTS       -> ∃ 
  FORALL       -> ∀ 
  PHI          -> φ
  NATURALS     -> ℕ
  IMPLIES      -> ⇒
  INTERSECTION -> ∩
  UNION        -> ∪
  PERTANY      -> ∈
-->

## Exercise 1

![Exercise 1](./PNG/01.png)
```text
u
v
l->r
l->r
```
Obtenim <u,v,R'>, on R' són les mateixes regles duplicades, ⇒ ∣R'∣ % 2 = 0.

---

## Exercise 2

![Exercise 2](./PNG/02.png)
```text
u
v
l->r
l->r
u->u
```
Obtenim <u,v,R'>, on R' són les mateixes regles duplicades i la regla inútil u->u, ⇒ ∣R'∣ % 2 = 1. Perquè |l->r, l->r| és un nombre parell i |u->u| és senar.

---

## Exercise 3

![Exercise 3](./PNG/03.png)
```text
u
v
l->i
i->r
```
Obtenim <u,v,R'>, on R' són les mateixes regles amb un pas intermig, és a dir, cada norma de reescriptura x -> y passa a ser x -> i, i -> y, on i és un identificador únic, pel que no tenim repeticions. Al afegir una regla extra per cada regla estem forçant que ∣R'∣ % 2 = 0.

---

## Exercise 4

![Exercise 4](./PNG/04.png)
```text
u
v
l->i
i->r
#->#
```

Seguim la mateixa idea, forrçem que sigui parell i afegim una regla inútil.

---

## Exercise 5

![Exercise 5](./PNG/05.png)
```textu
v
l->r
#l->#r
```

Aquí la restricció ∣Σ∣≤3 no ens permet usar i, que assigna un idenfiticador nou a cada regla. Usem un caràcter nou `#` al prinicpi de les regles, pel que tenim |l->r, #l->#r|, que és un nombre parell.

---

## Exercise 6

![Exercise 6](./PNG/06.png)
```text
u
v
l->r
#l->#r
#->#
```
El mateix, regles de mida parella (#l->#r) + regla més inútil (#->#) = regles de mida senar.

---

## Exercise 7

![Exercise 7](./PNG/07.png)
```text
s(a) = abba
s(b) = aba
s(#) = aa
s(u)
s(v)
s(l)->s(r)
s(#l)->s(#r)
```
Ara podem usar morfismes. Volem usar alguna cosa com (#l->#r), però sense usar #, ja que només podem tenir dos símbols.Hem triat aquest morfisme per evitar col·lisions entre cadenes.    

---

## Exercise 8

![Exercise 8](./PNG/08.png)
```text
s(a) = abba
s(b) = aba
s(#) = aa
s(u)
s(v)
s(l)->s(r)
s(#l)->s(#r)
s(#) -> s(#)
```
---

## Exercise 9

![Exercise 9](./PNG/09.png)
```text
u
v
l->r
u->u
```

- Cas positiu (u->*Rv)  
  Si es parell no faig servir la regla nova |parell|  
	Si es imparell faig servir la regla nova |parell|    
	
- Cas negatiu (u no té camí fins a v)
  No hi haurà cap camí parell  


---

## Exercise 10

![Exercise 10](./PNG/10.png)
```text
u
v
l -> r 
u -> u
```

---

## Exercise 11

![Exercise 11](./PNG/11.png)
```text
u
v
l -> i
i -> r
```
<!--

---
 ## Exercise 12

![Exercise 12](./PNG/12.png)
```text



```

---

## Exercise 13

![Exercise 13](./PNG/13.png)
```text

```

---

## Exercise 14

![Exercise 14](./PNG/14.png)
```text

```

---

## Exercise 15

![Exercise 15](./PNG/15.png)
```text

```

---

## Exercise 16

![Exercise 16](./PNG/16.png)
```text


```

--- -->

## Exercise 17

![Exercise 17](./PNG/17.png)
```text
u
v
# 
l->r
v->#

```
```
#        = W
l->r     Permet u->v
v->#     Permet u→R∗​v→R∗w
```
---

<!-- ## Exercise 18

![Exercise 18](./PNG/18.png)
```text

```

---

## Exercise 19

![Exercise 19](./PNG/19.png)
```text

```

---

## Exercise 20

![Exercise 20](./PNG/20.png)
```text


```

---

## Exercise 21

![Exercise 21](./PNG/21.png)
```text

```

---

## Exercise 22

![Exercise 22](./PNG/22.png)
```text

```

---

## Exercise 23

![Exercise 23](./PNG/23.png)
```text

```

---

## Exercise 24

![Exercise 24](./PNG/24.png)
```text

```

---

## Exercise 25

![Exercise 25](./PNG/25.png)
```text

```

---

## Exercise 26

![Exercise 26](./PNG/26.png)
```text

```

---

## Exercise 27

![Exercise 27](./PNG/27.png)
```text

```

---
## Exercise 28

![Exercise 28](./PNG/28.png)
```text

```

--- -->