# Ejercicios unidad 3

3.0 Escribe en forma ordenada las definiciones de:
  * espacio vectorial
  * combinación lineal
  * conjunto linealmente independiente
  * base de un espacio vectorial
  * dimensión de un espacio vectorial

3.1 Verifica que los siguientes conjuntos son espacios vectoriales (con la suma y multiplicación por escalar natural):
  * El conjunto Pol_10 de polinomios de grado menor o igual a 10
  * El conjunto Mat_3x4 de matrices de 3x4
  * El conjunto C[-1,1] de funciones continuas definidas sobre [-1,1]
  * El conjunto c_0 de sucesiones de números reales {a_1,a_2,a_3,....} que convergen a 0
  * La imagen Ran A de una matriz cualquiera A
  * El kernel Ker A de una matriz cualquiera A
  * El span S de cualquier conjunto S (¡no necesariamente finito!) de vectores de un espacio vectorial V

3.2 Verifica que los siguientes conjuntos NO son espacios vectoriales:
 * El conjunto de polinomios de grado igual a 10
 * El conjunto de matrices invertibles de 4x4
 * El conjunto de puntos (x,y,z) tales que x+y+z=1

3.3 Encuentra una base y la dimensión de Pol_10, Mat_3x4.

3.4 Demuestra que imposible encontrar una base con cardinalidad finita para los espacios C[-1,1] y c_0.

3.5 Escribe un algoritmo para encontrar una base para el Ran A para una matriz dada A.

3.6 Escribe un algoritmo para encontrar una base para el Ker A para una matriz dada A.

3.7 Sea S un subconjunto arbitrario de vectores de V. Demuestra que span S es un espacio vectorial de dimensión finita si y solo si S es un conjunto finito.

3.8  Sea V un espacio vectorial, se dice que un conjunto W (diferente del vacío) es un SUBESPACIO de V si para todo w_1 y w_2 in W y para cualquier par de escalares α_1 y α_2 se cumple que α_1w_1+α_2w_2 está en W. Verifica lo siguiente:

  * El conjunto Pol_4 de polinomios de grado menor o igual a 4 es un subespacio de Pol_10.
  * El conjunto Sym_4x4 de matrices simétricas de 4x4 es un subespacio de Mat_4x4.
  * El conjunto de funciones continuas y pares definidas sobre [-1,1] es un subespacio de C[-1,1].
  * El conjunto de c_00 de sucesiones de números reales que convergen a 0, con un número finito de elementos distintos de cero es un subespacio de c_0.
  * El conjunto de vectores en R^8 ortogonales al plano generado por (1,1,0,1,0,0,0,0) y (0,1,0,1,0,0,0,0) es un subespacio de R^8.

3.9 Encuentra la dimensión de cada uno de los subespacios vectoriales del ejercicio 3.8

3.10 Prueba o da un contrajemplo: "La intersección de dos subespacios vectoriales es también un espacio vectorial"

3.11 Escribe un algoritmo que verifique si un conjunto de m vectores en R^n  es linealmente independiente o no.

3.12 Demuestra que no puede haber un conjunto de m vectores linealmente independiente en R^n si m>n.

3.13 Considere el conjunto de numeros reales con la suma definida por a + b = a x b y   multiplicación por escalar definida por α a = a^α. ¿Es este conjunto un espacio vectorial?

3.14 Escribe un algoritmo que decida si un conjunto de polinomios en Pol_10 es linealmente independiente o no.
 
