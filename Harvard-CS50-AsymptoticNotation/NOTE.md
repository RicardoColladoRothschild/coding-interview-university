# Asymptotic Notation

Es una notacion matematica que se utiliza en ciencias de la computacion para describir el limite o comportamiento de una funcion a
medida que su entrada (los datos que esta pueda ir teniendo), van creciendo y se acercan al inifinito.

Proporciona una forma de analizar la eficiencia o caracteristicas de rendimiento de los algoritmos, especialmente en terminos de complejidad
temporal y complejidad espacial.

## Notacion big O: 
Representa el limite superior del crecimiento de una funcion. Describe el escenario peor caso de la complejidad temporal de un algoritmo.
Por ejemplo, si la complejidad temporal de un algoritmo es O(n), sifnifica que el tiempo de ejecucion de un algoritmo, crece de manera lineal con la entrada que este recibe (a mayor entrada, mas tiempo durara el algoritmo, pierde eficiencia, si la entrada crece.)

## Notación omega (Ω):
Representa el limite inferior del crecimiento de una funcion. Describe el mejor caso de la complejidad temporal de un algoritmo. Por ejemplo, si la complejidad temporal de un algoritmo es Ω(n), significa que el tiempo de ejecucion del algoritmo crece al menos de manera lineal con el tamaño de la entrada.

## Notación theta (Θ):
Representa tanto el limite superior como el limite inferior del crecimiento de la funcion. Propociona un limite mas ajustado en la tasa de crecimiento que las notaciones big O y Omega. Si la complejidad temporal de un algoritmo es Θ(n), significa que el tiempo de ejecucion dle algoritmo crece linealmente con el tamaño de la entrada y tiene un limite ajustado. (En un algoritmo de busqueda, el elemento a buscar podria estar en una variable, como podria no estar en esa variable, asi que, su limite inferior y superior son el mismo, por tanto su complejidad theta (n))