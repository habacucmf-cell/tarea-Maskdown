# Tecnológico de Software  
## Materia: Fundamentos de Álgebra  
## Alumno: David Habacuc Mandujano Franco
## Actividad #16 - Operaciones con matrices  

---

## Ejercicio 1: Clasificar matrices  

Identifica el tipo de cada matriz:

### Matriz A
$$
A=\begin{pmatrix}
1 & 0 \\
0 & 1
\end{pmatrix}
$$

Matriz identidad, diagonal, escalar, simétrica y triangular.  
Propiedad: $A = A^T$.

---

### Matriz B
$$
B=\begin{pmatrix}
3 & 0 & 0 \\
0 & -2 & 0 \\
0 & 0 & 5
\end{pmatrix}
$$

Matriz diagonal.  
También es simétrica.  
No es escalar porque sus diagonales son diferentes.

---

### Matriz C
$$
C=\begin{pmatrix}
2 & 1 & 4 \\
1 & 3 & 5 \\
4 & 5 & 6
\end{pmatrix}
$$

Matriz simétrica.  
Cumple $C_{ij} = C_{ji}$.

---

### Matriz D
$$
D=\begin{pmatrix}
1 & 2 & 3 \\
0 & 4 & 5 \\
0 & 0 & 6
\end{pmatrix}
$$

Matriz triangular superior.

Determinante:
$$
\det(D)=1\cdot 4\cdot 6 = 24 \neq 0
$$

Por lo tanto, es invertible.

---

## Conclusión del Ejercicio 1  

Se identificaron los distintos tipos de matrices: identidad, diagonal, simétrica y triangular.

---

## Ejercicio 2: Operaciones básicas  

Matrices dadas:

$$
A=\begin{pmatrix}
2 & -1 \\
3 & 4
\end{pmatrix}
\qquad
B=\begin{pmatrix}
5 & 2 \\
-1 & 3
\end{pmatrix}
$$

---

### a) Suma de matrices  
$$
A+B=
\begin{pmatrix}
7 & 1 \\
2 & 7
\end{pmatrix}
$$

---

### b) $2A - B$
$$
2A-B=
\begin{pmatrix}
-1 & -4 \\
7 & 5
\end{pmatrix}
$$

---

### c) Producto $AB$
$$
AB=
\begin{pmatrix}
11 & 1 \\
11 & 18
\end{pmatrix}
$$

---

### d) Producto $BA$
$$
BA=
\begin{pmatrix}
16 & 3 \\
7 & 13
\end{pmatrix}
$$

---

### e) Transpuesta de $A$
$$
A^T=
\begin{pmatrix}
2 & 3 \\
-1 & 4
\end{pmatrix}
$$

---

## Conclusión del Ejercicio 2  

Se aplicaron operaciones básicas entre matrices: suma, resta, multiplicación y transposición.  
Se comprobó que el producto matricial NO es conmutativo.

---

## Ejercicio 3: Multiplicación en cadena  

Matrices dadas:

$$
A=\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
\qquad
B=\begin{pmatrix}
2 & 0 \\
1 & 3
\end{pmatrix}
\qquad
C=\begin{pmatrix}
1 & 1 \\
0 & 2
\end{pmatrix}
$$

---

### Calcular \(AB\)
$$
AB=
\begin{pmatrix}
4 & 6 \\
10 & 12
\end{pmatrix}
$$

---

### Calcular \((AB)C\)
$$
(AB)C=
\begin{pmatrix}
4 & 16 \\
10 & 34
\end{pmatrix}
$$

---

### Calcular \(BC\)
$$
BC=
\begin{pmatrix}
2 & 2 \\
1 & 7
\end{pmatrix}
$$

---

### Calcular \(A(BC)\)
$$
A(BC)=
\begin{pmatrix}
4 & 16 \\
10 & 34
\end{pmatrix}
$$

---

### Verificación  
$$
(AB)C = A(BC)
$$

---

## Conclusión del Ejercicio 3  

Se verificó la propiedad asociativa de la multiplicación de matrices.
