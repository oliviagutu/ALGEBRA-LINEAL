
# Ejercicios unidad 1

1.0 Considere lo siguiente v=(1,2,3) y w=(4,4,4). Calcula lo siguiente:
 * la distancia entre v y w
 * el ángulo entre v y w
 * la norma de v
 * la norma de v-w
    
1.1. Sean v=(1,2,3), w=(1,1,1) y z=(3,5,7) tres vectores en R^3. Sea S el conjunto de combinaciones lineales de esos tres vectores, esto es, S=span{v,w,z}. Decide si S es un punto, una línea o un plano.

1.2. Suponga que tengo un programa EVALMATRIX(A,x) que recibe como entrada una matriz A de mxn (m renglones y n columnas) y un vector n-dimensional x, y regresa como salida al vector m-dimensional Ax. Usa ese programa para obtener:
  * la suma de todas las columnas de A
  * la primera columna
  * la última columna
  * la información del promedio de cada uno de los renglones de A
  
1.3. Describe geométricamente al conjunto de soluciones de Ax=0 donde A es la matriz de 1x3 (1,1,1) y b es  0 (un vector de 1x1).

1.4. Decida y argumente si la matriz con renglones (1,0,2), (2,0,4), (3,0,6) tiene inversa.

1.5. Demuestra que la matriz de rotación Rot_r que vimos en clase, efectivamente rota r grados a cada vector de R^2.

1.6  Pruebe que A es inyectiva (Ax_1=Ax_2 implica x_1=x_2) si y solo si Ax=0 tiene una única solución.

1.7. Suponga que A es una matriz de 4x3 (4 renglones y 3 columnas), ¿es posible que la imagen de A llene a R^4? Razona tu respuesta, discute con tus compañeros. De un ejemplo de una matriz de 4x3 inyectiva.

1.8. Suponga que A es una matriz de 3x4 (3 renglones y 4 columnas), ¿es posible que A sea inyectiva? Razona tu respuesta, discute con tus compañeros. De un ejemplo de una matriz de 3x4 que llene todo R^3.

1.9 Responde verdadero o falso:
   * span{(1,2,3)}=span{(1/3,2/3,1),(4,8,12)}
   * span{(1,1,1),(1,0,1)}=span{(1,1,1)}
   * span{(1,0,0),(0,0,0)}=span{(1,0,0)}
   
1.10  Encuentra la ecuación del hiperplano perpendicular a (1,4,5,6,8,9,10) que pasa por 0.

1.11 Busca en la literatura la *ley del paralelogramo*. Demuéstrala con lo que vimos en clase.

1.12 La desigualdad de Cauchy-Schwartz dice que abs(w.v) <= norm(w)norm(v). ¿Cuándo se cumple la igualdad?

1.13 Prueba que para cualesquiera n números a_1,a_2,...,a_n se cumple que:
    
   (a_1+a_2+...+a_n)^2 <= n*(a_1^2+a_2^2+...+a_n^2).

1.14 Sea A una matriz con renglones (1,3,5), (1,2,4) y (2,1,5):

   *  Encuentra si existe un vector  b para el cual NO exista un x tal que Ax=b.
   *  Escribe al conjunto de soluciones de Ax=0 como el generado de un conjunto de vectores.
   *  Describe geométricamente al conjunto del inciso b.
    
1.15 Sea P una matriz con renglones (1,0,0) y (0,1,0):

   *  ¿Qué efecto le hace esa matriz al espacio R^3?
   *  ¿Es P una función sobreyectiva?
   *  Verifica que hay una infinidad de matrices R (de *right inverse*) de 3x2 tales que, para todo x en R^2:
        P(Rx)=x.
   *  ¿Es P una función inyectiva?

