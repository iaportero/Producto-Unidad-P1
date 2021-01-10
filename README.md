# Producto-Unidad-P1
Integrantes: Bryan Santiago Torres Reyes , Roger Steveen Armas Simbaña , Israel Alejandro Portero Cazares

NRC: 4867

Objetivos :

Objetivo general

*  Analizar y utilizar los diferentes metodos de resolucion de ecuaciones  simultaneas , aparte de familiriarizarse con los metodos de corriente en ramas,analisis de lazos y de nodos  en los diferentes circuitos presentados.

Objetivos especificos

*  Aplicar el metodo de corriente en ramas  para incognitas presentadas en circuitos particulares.

*  Aplicar el metodo de analisis de lazos (mallas) para  determinar  diferentes incognitas  en circuitos presentados.

*  Aplicar el metodo de analisis de nodos  para determinar diferentes incognitas  en circuitos presentados.


Marco teorico/ Diagrams

*  Ecuaciones simultaneas en el analisis de  circuitos

Las ecuaciones simultaneas se componen de un conjunto de n ecuaciones  que contienen n incognitas , donde  n es un numero con un valor de 2 o  mas. El numero de ecuaciones  incluidas en el conjunto debe ser igual al numero de incognitas. Por ejemplo , para determinar dos variables desconocidos, se requieren dos ecuaciones, para tres incognitas, se requieren tres ecuaciones, y asi sucesivamente.


*  Soluciones de ecuaciones simultaneas

Solucion por sustitucion

Para resolver un sistema de ecuaciones por el método de sustitución seguiremos los siguientes pasos:

1.  Se despeja una incógnita en una de las ecuaciones

2.Se sustituye la expresión de esta incógnita en la otra ecuación, obteniendo un ecuación con una sola incógnita

3.  Se resuelve la ecuación

4.  El valor obtenido se sustituye en la ecuación en la que aparecía la incógnita despejada

5.  Los dos valores obtenidos constituyen la solución del sistema

 Ejemplo :
 
![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i1.png)

![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i2.png)

Solucion por determinantes

El Método de determinantes es una forma de resolución de sistemas de ecuaciones lineales, al igual que los métodos sustitución e igualación, este método permite obtener el resultado de un sistema de ecuaciones en unos simples pasos.

La ventaja mas resonante de utilizar este método es que su automatización, entendiendo esto como una forma de resolver ecuaciones de forma metodológica, nos olvidamos de despejes y demás. La forma mas practica de entender el procedimiento es mediante un ejemplo.

Ejemplo

![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i4.png)


![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i3.png)


1.  Para Calcular el determinante del sistema ΔS, Armamos el determinante solo con los valores que estan multiplicando a la X y la Y. Es por eso que nos queda la estructura que vimos arriba, luego multiplicamos cruzados, y restamos los múltiplos.

2. Para Calcular el determinante de X ΔX  lo que tenemos que hacer es armarnos el determinante con los valores que están a la derecha del signo igual, y con los valores que están multiplicando a la Y. De esta forma obtenemos el determinante que vimos arriba. luego la operatoria es la misma, multiplicamos cruzado y restamos las multiplicaciones.

3. Para Calcular el determinante de Y ΔY  lo que tenemos que hacer es armarnos el determinante con los valores que están a la derecha del signo igual, y con los valores que están multiplicando a la X. De esta forma obtenemos el determinante que vimos arriba. Luego la operatoria es la misma, multiplicamos cruzado y restamos las multiplicaciones.

![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i5.png)

para calcular el valor de X tenemos que dividir el determinante de X con el Determinante del sistema y para encontrar el valor de Y tenemos que dividir el determinante de Y con el determinante del sistema


![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i6.png)


Solucion mediante calculadora 

Las calculadoras en general emplean algoritmos  matriciales para determinar la solucion de ecuaciones simultaneas y facilitarla obtencion de los resultados.

Dpendiendo de que programa de calculador que utilice se deja a libre disposicion de usar el cual mas le convenga y  se acomode a su utilizacion

Ejemplo:

https://es.symbolab.com/solver/system-of-equations-calculator

https://www.microsoft.com/es-ec/p/matrix-calculator-free/9nblggh1xws7?activetab=pivot:overviewtab


Diagrama 1:

![](https://lh3.googleusercontent.com/IcAHluUsiM0aS6Ofh8pFcRbE-eHhvpGUTbbfYduWd7-ypPCJCynxqvtlU3Z_aM2ZQn7HqZ-Zx6fwElVIy8n0AvMntuUvhGEoyACYPORQ8fIYvNtI0v76MowrDpyZ78aUs0ZiB2HU)





*  Metodo de corrientes en ramas

El metodo de corrientes en ramas es un metodo de analisis de circuitos que utiliza las LVK y  LCK  para determinar la corriente que circula en cada rama de un circuito generando ecuaciones simultaneas. Una vez que se conocen las corrientes presentes en las ramas , se pueden determinar los voltajes.

Pasos:

1.  Asiganar una corriente en cada rama del circuito en una direccion arbitraria

2.  Indicar las polaridades de los voltajes presentes en los resistorees de acuerdo con las direcciones de las corrientes asignadas

3. Aplicar la LVK alrededor de cada lazo( la suma algebraica de los voltajes es igual a 0)

4.  Aplicar la LCK en el numero minimo de  nodos de modo que todas las corrientes  de rama esten incluidas ( la sumas algebraica de las corrientes que entran o salen a un nodo es igual a 0)

5.  Resolver las ecuaciones resultantes de los pasos 3 y 4 para determinar los valores de las corrientes de rama.

Circuito  ejemplo  :

![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i7.png)

Circuito asignando las corrientes de rama I1,I2,I3 en sus respectivas  direcciones

![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i8.png)

Ecuaciones generadas en lazo 1 y  2 usando LVK.

![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i9.png)

Usando  la LCK para  generar la ecuacion final

![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i10.png)

*  Metodo de la corriente de lazo

En  el metodo de corriente de lazo( tambien conocido como metodo de corrientes),se trabajara con corrientes de lazo en lugar de corrientes de rama. A diferencia de las corrientes  de rama , las  de lazo son cantidades matematicas , y no corrientes fisicas reales.

Pasos:

1.  Aunque la direccion asignada a una corriente de lazo es arbitraria , se asignara una corriente en el sentido de las manecillas del reloj alrededor de cada lazo no redundante , por consistencia . Esta puede no ser la direccion de la corriente  real, pero no importa. El numero  de asignaciones de corrientes de lazo debe ser suficiente para  incluir las corrientes que circulan a traves  de todos los componentes del circuito.

2.  Indicar las polaridades de las caidas de voltaje en cada lazo con base  en las direcciones de corrientes asignadas.

3. Aplicar LVK alrededor de cada lazo. Cuando mas de un corriente de lazo pasa a traves de un componente , se debera  incluir su caida de voltaje.Esto produce una ecuacion por cada lazo.

4.  Resolver las ecuaciones resultantes para las corrientes de lazo utilizando sustitucion o determinants.

Circuito ejemplo:

Se asignan a las corrientes de lazo el sentido de las manecillas del reloj y la polaridad de las caidas de voltaje

![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i11.png)

Ecuaciones de los lazos del circuito aplicando la LVK

![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i12.png)

Se reordena las ecuaciones obtenidas para aplicar los diferentes metodos de soluciones de ecuaciones vista.

![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i13.png)

Diagrama 2 

![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i14.png)


*  Metodo de voltajes en nodos

Otro metodo de analisis de circuitos de lazos multiples se denomina  metodo del voltaje en nodos. S ebasa en la determinacion de los voltajes presentes en cada nodo del circuito mediante la LCK. Un nodo es la union de dos o mas componentes.

Pasos: 

1. Determinar el numero de nodos

2.  Seleccionar un nodo de referencia .Todos los voltajes seran con respecto al nodo de referencia . Asignar designaciones de voltaje a cada  nodo donde el voltaje es desconocido.

3.  Asignar corrientes en cada nodo donde se desconoce el voltaje , excepto en el nodo de referencia .Las direcciones son arbitrarias.

4. Aplicar LCK a cada nodo donde se asignan las corrientes.

5. Expresar las ecuaciones de  corrientes en funcion del voltaje , y resolver  las ecuaciones para determinar  los voltajes de nodo desconocidos mediante ley de Ohm.


Circuito ejemplo:

Se establece los nodos, se escoge un nodo de referencia  ( Nodo B)

![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i15.png)

Se asignan arbitrariamente las corrientes de nodo  ( Nodo A) . Se aplica  LCK en el nodo seleccionado 

![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i16.png)

Se expresanlas corrientes en funcion de voltajes de circuito utilizando la ley de Ohm

![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i17.png)

Se sustituye estos terminos en la ecuacion de corrientes se obtiene :

![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i18.png)

Diagrama 3
)
![](https://github.com/iaportero/Producto-Unidad-P1/blob/main/Imagenes/i19.png)

Desarrollo:

https://github.com/iaportero/Producto-Unidad-P1/tree/main/Codigo%20Fuente

Aportaciones:



Conclusiones:

*  Ampliando el conocimiento de metodos de resolucion de ecuaciones  se nos hace mas facil la resolucion de circuitos con varias incognitas.

*  Tanto el metodo de analisis de  ramas como el de  lazos  son metodos efectivos para la resolucion de ejercicios con incognitas la unica diferencia es en los valores que trabaja cada uno el uno valores reales fisicos y el otro valores numericos

*En el analisis de nodos  es un metodo efectivo si maneja bien la observacion y teoria de los nodos en un circuito.

Anexos:

Link de video del producto unidad



Link del Articulo




Bibliografia :

Principios de Circuitos Electricos, Floyd .L.Thomas,Mexico 2007,Recuperado:10-01-2021,Capitulo 9 , pags: 335-369


▷ MÉTODO DE DETERMINANTES - RESOLUCIÓN DE ECUACIONES. (n.d.). Retrieved January 10, 2021, from https://www.electrontools.com/Home/WP/metodo-de-determinantes-o-metodo-de-cramer/


Mapa conceptual capitulo_8_edwin_enamorado. (n.d.). Retrieved January 10, 2021, from https://es.slideshare.net/ElvisLopez5/mapa-conceptual-capitulo8edwinenamorado






















