# Regular Expressions
<!-- 
# Expressions regulars
Tipus d'exercicis:

Normals : Definir variables i completar 
Múltiples : Es solen fer amb dfa's, però fer també pots fer
        
    m4 = ("0"|"1")* "00" | "" | "0";

Per tenir múltiples de 4, per exemple.

Morfismes : Substitution

NFA : DFA amb símbols que representen el mateix símbol. Acabarem fent morfisme del simbol pel símbol que representa.

Alguns et demanen camins de un node a un altre i has de fer cicles intermitjos. -->

## Exercise 1

![Exercise 1](./PNG/01.png)

```text
main
{
  word = "aaa" | "bbb" | "aba" | "bab";
  all = ("a"|"b")*;
  
  output all word all;     
}
```


## Exercise 2

![Exercise 2](./PNG/02.png)
```text
main
{
  a = "a";
  b = "b";
  t = a|b;
  L1 = t* "aaa" t*;
  L2 = substitution(L1, "a" -> "b", "b" -> "a");
  L3 = t* "aba" t*;
  L4 = substitution(L3, "a" -> "b", "b" -> "a");
  
  output L1 & L2 & L3 & L4;
}
```



## Exercise 3

![Exercise 3](./PNG/03.png)
```text
main
{ 
 a = "a";
 b = "b";

 all = ("a" | "b")*;
 
 L1 = all "aaa" all - (all "aaa" all "aaa" all) - (all "aaaa" all);
 L2 = substitution(L1, "b" -> "a", "a" -> "b");
 
 output L1 & L2;
}
```


Fàcil oblidar el segon cas d'L1
## Exercise 4

![Exercise 4](./PNG/04.png)
```text

```


## Exercise 5

![Exercise 5](./PNG/05.png)
```text

```


## Exercise 6

![Exercise 6](./PNG/06.png)
```text

```


## Exercise 7

![Exercise 7](./PNG/07.png)
```text

```


## Exercise 8

![Exercise 8](./PNG/08.png)
```text

```


## Exercise 9

![Exercise 9](./PNG/09.png)
```text

```


## Exercise 10

![Exercise 10](./PNG/10.png)
```text

```


## Exercise 11

![Exercise 11](./PNG/11.png)
```text

```


## Exercise 12

![Exercise 12](./PNG/12.png)
```text

```


## Exercise 13

![Exercise 13](./PNG/13.png)
```text

```


## Exercise 14

![Exercise 14](./PNG/14.png)
```text

```


## Exercise 15

![Exercise 15](./PNG/15.png)
```text

```


## Exercise 16

![Exercise 16](./PNG/16.png)
```text

```


## Exercise 17

![Exercise 17](./PNG/17.png)
```text

```


## Exercise 18

![Exercise 18](./PNG/18.png)
```text

```


<!-- to finish -->