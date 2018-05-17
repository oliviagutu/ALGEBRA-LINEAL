# Ejercicios unidad 4

4.0 Para la matriz A con renglones (1,0,1), (1,1,2), (2,1,3) encuentra:
  * Encuentra los cuatro subespacios de A: Ran A, Ker A, Ran A^T, Ker A^T
  * Verifica que Ran A es ortogonal a Ker A^T
  * Verifica que Ran A^T es ortogonal a Ker A

4.1 Sea A la matriz con renglones (1,0,1) y (1,2,0). Sea b = (0,-1)^T. Encuentra el conjunto S de soluciones de Ax = b en términos del Ker A. ¿Qué dimensión tiene este conjunto de soluciones?

4.2 Sea S el plano x+y+z=1 y sea b = (1,0,3). Encontrar el punto en el plano más cercano a b.

4.3 Sea S el hiperplano descrito mediante el span del siguiente conjunto de vectores: (1,1,0)^T, (2,0,0)^T
y (3,1,0)^T. Encuentra el punto de S más cercano a b = (2,2,2).

4.3 Haz lo mismo que en el ejercicio 4.1 pero con b = (1,-1)^T. ¿Cambia la dimensión de S?

4.4 Escribe un algoritmo tal que dada una matriz A y un vector b, encuentre la mejor "solución"  correspondiente al sistema: 
 Ax = b. Es decir, el punto x tal que Ax está más cerca de b.
 
4.5 Sea A una matriz cualquiera. Prueba que las siguientes afirmacines son equivalentes:
  * A es una matriz con columnas linealmente independientes.
  * Ker A = {0}
  * A^TA es invertible. 

Sugerencia: Para probar que Ker A = {0} implica A^TA es invertible pruebe que (A^TA)x=0 implica x=0.

4.6 Considera el conjunto de datos {(0,2),(1,8),(2,8),(1,5),(3,4)}. Encuentra la línea recta a_1x+a_0 que mejor ajuste a los datos en el sentido de mínimos cruadrados.

4.7 Con los mismos datos que en el ejercicio anterior, encuentra una parábola a_2x^2+a_1x+a_0 que mejor ajuste a los datos en el sentido de mínimos cuadrados. ¿Cuáles son tus conclusiones al comparar los resultados del ejercicio anterior en comparación a este?

4.8 Da el ejemplo de un conjunto de datos 100 para el cual falle el algoritmo de mínimos cuadrados para ajustar una recta. ¿Qué condición se requiere pedir a los datos para asegurar el éxito?

4.9 Suponga que las columunas de la matriz A en el algoritmo de mínimos cuadrados no son linealmente independientes. ¿Podría encontrar una matriz B tal que P=B(B^TB)B^T es la proyección sobre Ran A (la fórmula usual falla, pues A^TA no es invertible).

4.10 Encuentra una función lineal que a cada punto b en R^3 lo envía a su proyección sobre el plano perpendicular al punto (1, 1 ,1).

4.11 Sea {v_1,v_2, ... v_n} un conjunto de vectores ortogonales. Prueba que si todos los v_i son diferentes de cero, entonces este conjunto es linealmente independiente.

4.12 Sea Q una matriz ortogonal. Demuestra que norm(Qx) = norm(x) para todo x en el dominio de Q. Esto quiere decir que bajo Q el vector x no cambia de norma. Da 5 ejemplos de matrices ortogonales. 

4.13 Supongamos que la matriz  A en el algoritmo de mínimos cuadrados es una matriz ortogonal. Demuestra que este caso la matriz de proyección sobre Ran A es P=AA^T.

4.14 (Gram-Schmidt algorithm) Sea {v_1, v_2, ... v_m} con conjunto linealmente independiente de vectores en R^n. Se puede "orgonalizar" este conjunto, es decir construir  un conjunto {u_1, u_2, ... u_m} ortogonal a partir de los vectores v_i. El algoritmo es el siguiente:

u_1 = v_1

u_2 = v_2 - <v_2,u_1>/<u_1,u_1> u_1

u_3 = v_3 - <v_3,u_1>/<u_1,u_1> u_1 - <v_3, u_2>/<u_2,u_2> u_2

.
.
.

u_m = v_m - Sum_(i=1)^(m-1) <v_m,u_i>/<u_i,u_i> u_i

Demuestra que el conjunto construido es ortogonal.

4.15 Usando el proceso de Gram-Schmidt anterior, ortogonaliza el conjunto de vectores {(1,-1,0), (2,0,-2), (1,-3,3)}.

4.16 Sea A = (v_1, v_2 ––– v_m) una matriz de n x m con m columnas v_i de n entradas, linealmente independientes. Sea {u_1, u_2, ... u_m} el conjunto ortogonal que resulta de aplicarle al conjunto de columnas de A el proceso de ortogonalización de Gram-Scmidt. Para cada i = 1,2, ..., m sea q_i = u_i/norm (u_i). Sea Q = (q_1, q_2, ––– q_m).
 * Verifica que la matriz  Q es ortogonal
 * Sea R la matriz con columnas ()


 **Nota: La matriz A asociada al problema de mínimos cuadrados es la llamada matriz de Vandermonde, revisar internet y las notas de clase.

