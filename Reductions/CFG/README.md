# CFG-Reductions
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
input g1,g2
{
  output g1, g2, g1 | g2;
}
```
---

## Exercise 2

![Exercise 2](./PNG/02.png)
```text
input g1,g2
{
  output g1, g2 | "z", "z";
}
```

---

## Exercise 3

![Exercise 3](./PNG/03.png)
```text
input g1,g2
{
  G1 = substitution(g1, "a" -> "aa");
  G2 = substitution(g2, "a" -> "aa");
  Z = "a";
  output G1, G2|Z, Z;
}
```
Juguem amb la paritat, un mot de Z o G2|Z sempre tindrà |a| != ·2

---

## Exercise 4

![Exercise 4](./PNG/04.png)
```text
input g1,g2
{
  output g1, g2, "z", "z";
}
```
---

## Exercise 8

![Exercise 8](./PNG/08.png)
```text
input g
{
  output substitution(g, "a" -> "a"|"c");
}
```
---

## Exercise 9

![Exercise 9](./PNG/09.png)
```text
input g
{
  output g , ("a"|"b")* ;
}
```

---

## Exercise 10

![Exercise 10](./PNG/10.png)
```text
input g
{
  output ("a"|"b")*, g;
}
```

---

## Exercise 11

![Exercise 11](./PNG/11.png)
```text
input g1,g2
{
  output g1, g2;
}
```

---

## Exercise 12

![Exercise 12](./PNG/12.png)
```text
input g
{
  output g, g;
}
```

---

## Exercise 17

![Exercise 17](./PNG/17.png)
```text
input g
{
  if ("a" belongsto g)
    output g - "a";
  else
    output g | "a";
}
```

---

## Exercise 19

![Exercise 19](./PNG/19.png)
```text
input g
{
  output "a" g| "b"* "a" g;
}
```

---
