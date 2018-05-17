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
  * A es una matriz con columnas linealmente independientes
  * Ker A = {0}
  * A^TA es invertible. 

Sugerencia: Para probar que Ker A = {0} implica A^TA es invertible pruebe que (A^TA)x=0 implica x=0.

4.6 Considera el conjunto de datos {(0,2),(1,8),(2,8),(1,5),(3,4)}. Encuentra la línea recta a_1x+a_0 que mejor ajuste a los datos en el sentido de mínimos cruadrados.

4.7 Con los mismos datos que en el ejercicio anterior, encuentra una parábola a_2x^2+a_1x+a_0 que mejor ajuste a los datos en el sentido de mínimos cuadrados. ¿Cuáles son tus conclusiones al comparar los resultados del ejercicio anterior en comparación a este?

4.8 Da el ejemplo de un conjunto de datos 100 para el cual falle el algoritmo de mínimos cuadrados para ajustar una recta. ¿Qué condición se requiere pedir a los datos para asegurar el éxito?

4.9 Suponga que las columunas de la matriz A en el algoritmo de mínimos cuadrados no son linealmente independientes. ¿Podría encontrar una matriz B tal que P=B(B^TB)B^T es la proyección sobre Ran A (la fórmula usual falla, pues A^TA no es invertible)

