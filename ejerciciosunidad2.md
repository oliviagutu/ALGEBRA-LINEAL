# Ejercicios unidad 2

2.0 En la clase vimos varios ejemplos de solución de sistemas de ecuaciones lineales. Haz un resumen  que describa el procedimiento en todos los casos (matrices cuadradas, matrices con más renglones que columnas y matrices con más columnas que renglones).

2.1 Escriba un algoritmo que, dada una matriz A y un vector b:
 * La única solución de Ax=b, si es el caso.
 * Mensaje de "no existe solución de Ax=b", si el sistema no tiene solución. 
 * Pregunte al usuario un número k de soluciones que desee, y en función de eso, regrese k soluciones distintas; esto en el caso que  el sistema tenga infinitas soluciones.
 
 2.2  Demuestre que para tres matrices cualesquiera A,B,C que se puedan multiplicar se cumple que (AB)C=A(BC).
 
 2.3  Sea A una matriz de nxn. Demuestre que si B es una inversa derecha de A, es decir AB=I, donde I es la matriz identidad de nxn, entonces B también es una inversa izquierda, es decir, BA=I. Da un ejemplo donde esto no se cumpla para el caso en que A no sea una matriz cuadrada.
 
 2.4 Sean A y B matrices con la misma dimensión y C una matriz que se puede multiplicar por la derecha con A (y por tanto con B). Verifique que (A+B)C=AC+BC.
 
 2.5 Pruebe o de un contra-ejemplo: "Si AB=B entonces A=I".
 
 2.6 Sea A la matriz con renglones (3,-1) y (3,-2) y sea B la matriz con renglones (1,0,4) y (1,0,6). Calcula lo siguiente sin hacer cuentas de más:
  * la columna 2 de AB
  * el renglón 2 de AB
  * el renglón 2 de AA
  * el renglón 2 de AAA
  
2.7 Sea A una matriz con renglones (0.5, 0.5) y (0.5, 0.5) encuentra A^100000 sin usar la calculadora o la computadora.

2.8 De argumentos para deducir que: si  Ax=0 para alguna x distinta de cero, entonces A no tiene inversa.

2.9 Sea A una matriz de 3x3. Suponga que el renglón 3 = renglón 1 + renglón 2.
  * demuestra que A no es invertible
  * explica porqué el sistema Ax=b no tiene solución si b es el vector (1,0,0) de R^3
  * para que b=(b_1,b_2,b_3) en R^3 el sistema Ax=b sí tendría solución
  * ¿qué le pasa al renglón 3 en la eliminación?
  
2.10 Prueba que una matriz cuadrada con una columna de solo ceros no puede tener inversa.

2.11 Encuentra con operaciones de pivoteo la inversa de la matriz A con renglones (1,0,0), (2,1,3), (0,0,1).

2.12 Da explícitamente la matriz elemental E de 4x4 que causa el siguiente efecto sobre cualquier matriz de 4xk:  
     renglón 3 reemplazado por 5 x renglón 1 + renglón 3. 
  * encuentre la inversa de E
  * ¿qué efecto tiene la inversa de E sobre una matriz A al considerar EA?
  
2.13 Demuestre que es posible que AA=0 para A diferente de la matriz cero, pero no es posible A^TA=0, a menos que A sea la matriz cero.

2.14 Encuentra una matriz de permutación de 3x3 tal que P^3 = I pero P no es la matriz identidad I.

2.15  Verifica que todas las matrices de permutación  que permutan renglones on simétricas. Si P es una de esas matrices, ¿quién es su inversa?

2.16 Encuentra una matriz P_all de 4x4 que permute todos los renglones de una matriz de 4xk. Encuentra la inversa de P_all.

2.17 Sea R la matriz de rotación vista en clase. ¿Es R^T=R^{-1}?

2.18 De 5 ejemplos de matrices para las cuales existan varias  inversas por la derecha. De otros 5 ejemplos para los cuales existan varias inversas por la izquierda.

1.19 Sea A cualquier matriz de mxn cuyas columnas formen un conjunto linealmente independiente. Demuestre que siempre existe una matriz B de nxm tal que ABA=A.

1.20 Sea A una matriz de nxn tal que A^T=A^{-1} (matriz ortogonal). Demuestre que norm(Ax)=norm(x) para todo x en R^n.


