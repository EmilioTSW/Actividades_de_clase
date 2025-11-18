# Ejercicio 1: Determinantes 2x2

## 1. Determinante de A

La matriz es:

```math
A = \begin{pmatrix}
5 & 2 \\
3 & 1
\end{pmatrix}
```

### Procedimiento
1. Identificar elementos:  
   \(a=5,\ b=2,\ c=3,\ d=1\)
2. Aplicar fórmula:  
```math
\det(A) = (5)(1) - (2)(3)
```
3. Resultado:  
```math
\det(A) = -1
```

---

## 2. Determinante de B

```math
B = \begin{pmatrix}
-1 & 4 \\
2 & -8
\end{pmatrix}
```

### Procedimiento
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

### Procedimiento
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

### Procedimiento
```math
\det(D) = 0 - (-25) = 25
```

---

# Ejercicio 2: Regla de Sarrus

## Determinante de E

```math
E = \begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 4 \\
5 & 6 & 0
\end{pmatrix}
```

### Suma de diagonales:

```math
(1)(1)(0) + (2)(4)(5) + (3)(0)(6) = 40
```

### Resta de diagonales:

```math
(3)(1)(5) + (1)(4)(6) + (2)(0)(0) = 39
```

### Resultado:

```math
\det(E) = 40 - 39 = 1
```

---

## Determinante de F

```math
F = \begin{pmatrix}
2 & -1 & 3 \\
1 & 4 & 0 \\
3 & 2 & -2
\end{pmatrix}
```

### Suma:

```math
-16 + 0 + 6 = -10
```

### Resta:

```math
36 + 0 + 2 = 38
```

### Resultado:

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

Submatriz:

```math
\begin{pmatrix}
3 & 1 \\
0 & 1
\end{pmatrix}
```

```math
C_{11} = 3
```

## Cofactor C13

Submatriz:

```math
\begin{pmatrix}
-1 & 3 \\
2 & 0
\end{pmatrix}
```

```math
C_{13} = -6
```

## Resultado final

```math
\det(G) = (1)(3) + (0) + (2)(-6) = -9
```

---

# Ejercicio 4: Propiedades del Determinante

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

## Cálculo de determinantes

```math
\det(A)=5
```

```math
\det(B)=-5
```

```math
AB = \begin{pmatrix}
5 & 5 \\
10 & 5
\end{pmatrix}
```

```math
\det(AB) = -25
```

### Verificación

```math
\det(A)\det(B) = -25
```

✔ Se verifica.

```math
\det(A^T)=5=\det(A)
```

✔ Se verifica.

---

# Ejercicio 5: Área con Determinantes

Vectores:  
\(\vec u = (3,2)\), \(\vec v = (1,4)\)

```math
M = \begin{pmatrix}
3 & 2 \\
1 & 4
\end{pmatrix}
```

```math
\det(M)=10
```

Área:

```math
\text{Área} = 10
```

Si se intercambian:

```math
\det(M')=-10
```

Área:

```math
|\det(M')|=10
```

El área **no cambia**.
