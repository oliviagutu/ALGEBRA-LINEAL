# Ejercicios unidad 5

5.0 Considera las siguientes matrices ortogonales:

  * con renglones: (cos t, sin t) y (sin t, cos t) (matriz de rotación) 
  * con renglones: (cos t, sin t) y (sin t , -cos t) (matriz de reflexión)
  * con renglones: (0,1) y (1,0) (matriz de permutación)

Para cada una de ellas, dibuja el efecto que tiene en el plano; calcula su matriz inversa; calcula sus valores propios el conjunto de valores singulares correspondientes a cada valor propio y su determinante.

5.1  Da el ejemplo de una matriz Q con columnas ortonormales pero tal QQ^T no es la matriz identidad. ¿Es posible encontrar una matriz con estas características cuadrada?

5.2 Hay una forma de encontrar los autovalores de una matriz (¡sin usar determinantes!) a través de la descomposición QR,
ver e. g. (http://www.ohiouniversityfaculty.com/youngt/IntNumMeth/lecture17.pdf). Checa de qué se trata.

5.3 Sea A una matriz cuadrada. Demuestra que el determinante de A es igual a la multiplicación de sus valores propios. Sugerencia: considere el polinomio característico de A.

5.4 Prueba que vectores propios correspondientes a valores propios diferentes son linealmente independientes.

5.5. Si β es un valor propio  de B y 𝞴 es un valor propio de A entonces  β𝞴 NO necesariamente es un valor propio de AB. ¿Qué hay mal en la siguiente demostración-*fake*:

ABx = Aβx = βAx = β𝞴x

(Recuerda β𝞴 es un valor propio de AB si y solo si AB = BA)

5.6 Sea A una matriz de n x n. Suponga que Ax = 𝞴x. Si 𝞴 = 0 entonces x esta en Ker A. Si 𝞴 ≠ 0 entonces x pertenece a Ran A. La suma de las dimensiones del Ker A y Ran A suman n, ¿porqué esto no asegura que la matriz A tiene n vectores propios linealmente independientes? 

5.7 Da el ejemplo de una matriz de 3 x 3 que no sea diagonalizable.

5.8 Verifica que si AA^T=A^TA entonces A y A^T comparten los mismos vectores propios.

5.9 Da razones por las cuales las matrices A y A^T tienen el mismo conjunto de valores propios.

5.8 ¿Dónde está el problema con el siguiente razonamiento erróneo? "En vista de los dos ejercicios anteriores podemos concluir que A y A^T admiten la misma diagonalización y por tanto A = A^T"

5.9  Sea A la matriz con renglones (0, 0, 1), (0, 1, 0) y (1, 0, 0). ¿Es posible factorizar a A de la forma QR? ¿Es diagonalizable? ¿Es diagonalizable en términos de una matriz ortogonal?

5.10 Prueba que dos matrices similares comparten:

 * el determinante.
 * el conjunto de autovalores.
 * el rango.
 * el número de posibles vectores propios linealmente independientes

5.11 Encuentra una matriz Q que diagonaliza a la matriz simétrica A con renglones (1,0,2), (0, -1, -2) y (2, -2, 0).

5.12 Encuentra la descomposición en valores singulares de la matriz de las siguientes matrices con renglones:

 * (2, 2) y (-1, 1)
 * (2, 2) y (1, 1)
 * (1, 2), (3, 6), (0, 1)
 

