# Tecnológico de Software
## Materia: Fundamentos de álgebra
## Alumno: David Habacuc Mandujano Franco
## Actividad \#16 - Matrices doc

---
### Identificación de matrices

Matriz identidad, porque la diagonal está compuestos por solo unos y los elementos fuera de la diagonal son ceros.

$$ A =
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$

MUESTRA

Calcula la suma de A y B

$$ A =
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
9 & 10 & 11 \\
12 & 13 & 14 \\
\end{pmatrix}
$$

$$ A + B =
\begin{pmatrix}
1 + 9 & 2 + 10 & 3 + 11 \\
4 + 12 & 5 + 13 & 6 + 14 \\
\end{pmatrix}
$$

$$ A + B =
\begin{pmatrix}
10 & 12 & 14 \\
16 & 18 & 20 \\
\end{pmatrix}
$$

---
# OTRO EJERCICIO
...
# Determinantes y Aplicaciones – Ejercicios 1 a 5

---

## Ejercicio 1: Determinantes 2×2

Para una matriz:

```math
\begin{pmatrix}
a & b \\
c & d
\end{pmatrix}
```

el determinante se calcula como:

```math
\det =
ad - bc
```

---

### 1. Determinante de A

```math
A =
\begin{pmatrix}
5 & 2 \\
3 & 1
\end{pmatrix}
```

**Procedimiento**

1. Identificar elementos: \(a=5,\ b=2,\ c=3,\ d=1\).
2. Sustituir en la fórmula:

```math
\det(A) = (5)(1) - (2)(3)
```

3. Operar:

```math
\det(A) = 5 - 6 = -1
```

**Resultado**

```math
\det(A) = -1
```

---

### 2. Determinante de B

```math
B =
\begin{pmatrix}
-1 & 4 \\
2 & -8
\end{pmatrix}
```

**Procedimiento**

1. Elementos: \(a=-1,\ b=4,\ c=2,\ d=-8\).

```math
\det(B) = (-1)(-8) - (4)(2) = 8 - 8 = 0
```

**Resultado**

```math
\det(B) = 0
```

---

### 3. Determinante de C

```math
C =
\begin{pmatrix}
6 & 9 \\
2 & 3
\end{pmatrix}
```

**Procedimiento**

```math
\det(C) = (6)(3) - (9)(2) = 18 - 18 = 0
```

**Resultado**

```math
\det(C) = 0
```

---

### 4. Determinante de D

```math
D =
\begin{pmatrix}
0 & 5 \\
-5 & 0
\end{pmatrix}
```

**Procedimiento**

```math
\det(D) = (0)(0) - (5)(-5) = 0 - (-25) = 25
```

**Resultado**

```math
\det(D) = 25
```

---

## Ejercicio 2: Regla de Sarrus (Matrices 3×3)

Para una matriz:

```math
M =
\begin{pmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{pmatrix}
```

La regla de Sarrus indica:

```math
\det(M) =
(a_{11}a_{22}a_{33} + a_{12}a_{23}a_{31} + a_{13}a_{21}a_{32})
-
(a_{13}a_{22}a_{31} + a_{11}a_{23}a_{32} + a_{12}a_{21}a_{33})
```

---

### 1. Determinante de E

```math
E =
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 4 \\
5 & 6 & 0
\end{pmatrix}
```

#### Suma de diagonales principales

```math
\text{Suma} =
1\cdot 1\cdot 0
+ 2\cdot 4\cdot 5
+ 3\cdot 0\cdot 6
= 0 + 40 + 0 = 40
```

#### Suma de diagonales secundarias

```math
\text{Resta} =
3\cdot 1\cdot 5
+ 1\cdot 4\cdot 6
+ 2\cdot 0\cdot 0
= 15 + 24 + 0 = 39
```

#### Determinante

```math
\det(E) = \text{Suma} - \text{Resta} = 40 - 39 = 1
```

**Resultado**

```math
\det(E) = 1
```

---

### 2. Determinante de F

```math
F =
\begin{pmatrix}
2 & -1 & 3 \\
1 & 4 & 0 \\
3 & 2 & -2
\end{pmatrix}
```

#### Suma de diagonales principales

```math
\text{Suma} =
2\cdot 4\cdot (-2)
+ (-1)\cdot 0\cdot 3
+ 3\cdot 1\cdot 2
= -16 + 0 + 6 = -10
```

#### Suma de diagonales secundarias

```math
\text{Resta} =
3\cdot 4\cdot 3
+ 2\cdot 0\cdot 2
+ (-1)\cdot 1\cdot (-2)
= 36 + 0 + 2 = 38
```

#### Determinante

```math
\det(F) = \text{Suma} - \text{Resta} = -10 - 38 = -48
```

**Resultado**

```math
\det(F) = -48
```

---

## Ejercicio 3: Método de Cofactores

```math
G =
\begin{pmatrix}
1 & 0 & 2 \\
-1 & 3 & 1 \\
2 & 0 & 1
\end{pmatrix}
```

Usamos expansión por la **primera fila**:

```math
\det(G) = 1\cdot C_{11} + 0\cdot C_{12} + 2\cdot C_{13}
```

El término con \(C_{12}\) es cero.

---

### 1. Cofactor \(C_{11}\)

Submatriz (eliminando fila 1 y columna 1):

```math
\begin{pmatrix}
3 & 1 \\
0 & 1
\end{pmatrix}
```

Determinante:

```math
(3)(1) - (1)(0) = 3
```

Signo:

```math
(-1)^{1+1} = +1
```

```math
C_{11} = 3
```

---

### 2. Cofactor \(C_{13}\)

Submatriz (eliminando fila 1 y columna 3):

```math
\begin{pmatrix}
-1 & 3 \\
2 & 0
\end{pmatrix}
```

Determinante:

```math
(-1)(0) - (3)(2) = -6
```

Signo:

```math
(-1)^{1+3} = +1
```

```math
C_{13} = -6
```

---

### 3. Sustitución en la fórmula

```math
\det(G) = 1(3) + 0 + 2(-6)
```

```math
\det(G) = 3 - 12 = -9
```

**Resultado**

```math
\det(G) = -9
```

---

## Ejercicio 4: Verificar propiedades

Matrices:

```math
A =
\begin{pmatrix}
2 & 1 \\
1 & 3
\end{pmatrix}
```

```math
B =
\begin{pmatrix}
1 & 2 \\
3 & 1
\end{pmatrix}
```

Propiedades a verificar:

1. ```math
   \det(AB) = \det(A)\det(B)
   ```
2. ```math
   \det(A^T) = \det(A)
   ```

---

### 1. Cálculo de \(\det(A)\)

```math
\det(A) = (2)(3) - (1)(1) = 6 - 1 = 5
```

**Resultado**

```math
\det(A) = 5
```

---

### 2. Cálculo de \(\det(B)\)

```math
\det(B) = (1)(1) - (2)(3) = 1 - 6 = -5
```

**Resultado**

```math
\det(B) = -5
```

---

### 3. Producto \(AB\)

```math
AB =
\begin{pmatrix}
2 & 1 \\
1 & 3
\end{pmatrix}
\begin{pmatrix}
1 & 2 \\
3 & 1
\end{pmatrix}
=
\begin{pmatrix}
5 & 5 \\
10 & 5
\end{pmatrix}
```

Determinante:

```math
\det(AB) = (5)(5) - (5)(10) = 25 - 50 = -25
```

**Resultado**

```math
\det(AB) = -25
```

---

### 4. Verificación de \(\det(AB) = \det(A)\det(B)\)

```math
\det(A)\det(B) = 5 \cdot (-5) = -25
```

Como:

```math
\det(AB) = -25
```

se cumple:

```math
\det(AB) = \det(A)\det(B)
```

---

### 5. Verificación de \(\det(A^T) = \det(A)\)

Traspuesta:

```math
A^T =
\begin{pmatrix}
2 & 1 \\
1 & 3
\end{pmatrix}
```

Es igual a \(A\), así que:

```math
\det(A^T) = 5 = \det(A)
```

La propiedad se verifica.

---

## Ejercicio 5: Aplicación geométrica

Vectores:

```math
\vec{u} = (3, 2), \quad \vec{v} = (1, 4)
```

El área del paralelogramo formado por \(\vec{u}\) y \(\vec{v}\) es:

```math
\text{Área} = |\det(M)|
```

donde:

```math
M =
\begin{pmatrix}
3 & 2 \\
1 & 4
\end{pmatrix}
```

---

### a) Área del paralelogramo

Determinante:

```math
\det(M) = (3)(4) - (2)(1) = 12 - 2 = 10
```

Área:

```math
\text{Área} = |\det(M)| = |10| = 10
```

**Respuesta:** El área del paralelogramo es **10**.

---

### b) ¿Cambia el área si se intercambian los vectores?

Si intercambiamos los vectores:

```math
M' =
\begin{pmatrix}
1 & 4 \\
3 & 2
\end{pmatrix}
```

Determinante:

```math
\det(M') = (1)(2) - (4)(3) = 2 - 12 = -10
```

Área:

```math
|\det(M')| = |-10| = 10
```

**Respuesta:** El área **no cambia**, sigue siendo **10**; solo cambia el **signo del determinante**.

---

### c) Interpretación del signo del determinante

- Si el determinante es **positivo**, la orientación de \(\vec{u}\) a \(\vec{v}\) es **antihoraria** (orientación estándar).
- Si el determinante es **negativo**, la orientación es **horaria** (se invierte el sentido).

El signo del determinante indica la **orientación** de los vectores en el plano.








---# tarea-Maskdown
