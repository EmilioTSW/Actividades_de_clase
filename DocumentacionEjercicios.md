
# Ejercicio 1: Determinantes 2x2

## 1. Determinante de A
La matriz es:

```math
A = \begin{pmatrix}
5 & 2 \\
3 & 1
\end{pmatrix}
```

```math
\det(A) = (5)(1) - (2)(3) = -1
```

---

## 2. Determinante de B

```math
B = \begin{pmatrix}
-1 & 4 \\
2 & -8
\end{pmatrix}
```

```math
\det(B) = (-1)(-8) - (4)(2) = 0
```

---

## 3. Determinante de C

```math
C = \begin{pmatrix}
6 & 9 \\
2 & 3
\end{pmatrix}
```

```math
\det(C) = (6)(3) - (9)(2) = 0
```

---

## 4. Determinante de D

```math
D = \begin{pmatrix}
0 & 5 \\
-5 & 0
\end{pmatrix}
```

```math
\det(D) = (0)(0) - (5)(-5) = 25
```

---

# Ejercicio 2: Regla de Sarrus

## 1. Determinante de E

```math
E = \begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 4 \\
5 & 6 & 0
\end{pmatrix}
```

Diagonales principales:

```math
(1)(1)(0) + (2)(4)(5) + (3)(0)(6) = 40
```

Diagonales secundarias:

```math
-(3)(1)(5) - (1)(4)(6) - (2)(0)(0) = -39
```

```math
\det(E) = 40 - 39 = 1
```

---

## 2. Determinante de F

```math
F = \begin{pmatrix}
2 & -1 & 3 \\
1 & 4 & 0 \\
3 & 2 & -2
\end{pmatrix}
```

Principales:

```math
(2)(4)(-2) + (-1)(0)(3) + (3)(1)(2) = -10
```

Secundarias:

```math
-(3)(4)(3) - (2)(0)(2) - (-1)(1)(-2) = -38
```

```math
\det(F) = -10 - 38 = -48
```

---

# Ejercicio 3: Método de Cofactores

```math
G = \begin{pmatrix}
1 & 0 & 2 \\
-1 & 3 & 1 \\
2 & 0 & 1
\end{pmatrix}
```

## Cofactor C11

```math
C_{11} = \begin{vmatrix}
3 & 1 \\
0 & 1
\end{vmatrix} = 3
```

## Cofactor C13

```math
C_{13} = \begin{vmatrix}
-1 & 3 \\
2 & 0
\end{vmatrix} = -6
```

## Resultado final

```math
\det(G) = (1)(3) + (0)(C_{12}) + (2)(-6) = 3 - 12 = -9
```

---

# Ejercicio 4: Verificación de Propiedades

Matrices:

```math
A = \begin{pmatrix}
2 & 1 \\
1 & 3
\end{pmatrix}
```

```math
B = \begin{pmatrix}
1 & 2 \\
3 & 1
\end{pmatrix}
```

Producto:

```math
AB = \begin{pmatrix}
5 & 5 \\
10 & 5
\end{pmatrix}
```

Determinantes:

```math
\det(A) = 5
```

```math
\det(B) = -5
```

```math
\det(AB) = -25
```

---

# Ejercicio 5: Aplicación Geométrica

```math
M = \begin{pmatrix}
3 & 2 \\
1 & 4
\end{pmatrix}
```

```math
\det(M) = 10
```

```math
\text{Área} = 10
```
