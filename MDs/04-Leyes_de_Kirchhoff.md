# LEYES DE KIRCHHOFF
## Primera Ley de Kirchhoff o Ley de corrientes
La Ley de corrientes nos proporciona la relación entre los valores de corriente existentes en los
nodos de un sistema. Llamaremos nodo a cualquier unión de al menos dos trayectorias que
conducen corriente en un circuito.

Esta ley postula que la suma algebraica de las corrientes que entran y salen de un área,
sistema o unión es cero. En otras palabras, la suma de corrientes que entran a un área o
unión en un circuito debe ser igual a la suma de las corrientes que salen.

Observemos por ejemplo el siguiente circuito sencil o consistente en una fuente de tensión
alimentando a tres resistores en paralelo, con las corrientes correspondientes:

Tomemos la unión superior entre los tres resistores, o nodo A. Vemos que es posible representarlo
de la siguiente manera, con sus corrientes apropiadas, sin importar el resto del circuito:

La aplicación de la Ley de corrientes de Kirchhoff indica que la suma algebraica de todas las
corrientes debe ser igual a cero. Para esto sumaremos todas las corrientes asignando signo
positivo a las corrientes que entran y signo negativo a las que salen. Esto nos dará como resultado
la siguiente ecuación:
```
IT – IR1 – IR2 – IR3 = 0
```
Como vemos claramente, esto es lo mismo que expresar que la suma de las corrientes entrantes al
nodo (en este caso la corriente total IT) es igual a la suma de las corrientes salientes del nodo
( IR1 , IR2 e IR3):
```
IT = IR1 + IR2 + IR3
```
## Segunda Ley de Kirchhoff o Ley de tensiones
Así como la Ley de corrientes presentada anteriormente nos proporciona la relación entre los
valores de corriente en cualquier nodo de un sistema, esta ley (que también puede encontrarse
con el nombre de Ley de mal as o Ley de voltajes) postula que la suma algebraica de las
elevaciones y caídas de potencial alrededor de un lazo o trayectoria cerrada de
cualquier circuito es igual a cero.

Para entender esto y poder aplicarlo lo primero que debemos definir es el concepto de lazo
cerrado. Consideraremos un lazo cerrado a cualquier trayectoria continua de un circuito que sale
de un punto en una dirección y regresa al mismo punto desde otra dirección sin abandonar el
circuito. También se le puede l amar malla a un lazo cerrado.

Tomemos por ejemplo el siguiente circuito con cuatro resistores en serie:
Vemos claramente que constituye un lazo cerrado, ya que cumple con la definición expuesta
anteriormente.

Para aplicar la ley de voltaje de Kirchhoff lo primero que debemos hacer es asignar las direcciones
a las elevaciones de tensión (tensiones aplicadas por fuentes de tensión) y a las caídas de tensión.
Una forma de asignar la dirección a una caída de tensión en un elemento pasivo es pensar que
poseerá dirección inversa a la dirección de la corriente eléctrica

A continuación, tomamos un punto cualquiera del circuito y comenzamos a recorrerlo en cualquier
sentido (horario o anti-horario). Aquí tomamos el sentido horario. En base a la ley de Kirchhoff
plantearemos una ecuación de la siguiente manera: sumaremos de manera algebraica todas las
tensiones, asignando signo positivo a las tensiones que vayan en la misma dirección que el
recorrido que estoy siguiendo y signo negativo a las que vayan en sentido opuesto (de manera
análoga a lo que hicimos con las corrientes cuando aplicamos la primera ley)

En este caso, resultará que las caídas de tensión poseerán signo negativo y las elevaciones de
tensión signo positivo, ya que estoy realizando la trayectoria en sentido horario. Sin embargo, un
aspecto fundamental que ayuda a comprender esta ley de Kirchhoff es que si hubiéramos seguido
la trayectoria en sentido opuesto (anti-horario) el resultado hubiera sido el mismo.
Como resultado obtendremos la siguiente ecuación:
```
–VR1 – VR1 – VR3 – VR4 + V = 0
```
Observemos que esta ecuación también puede expresarse de la siguiente manera:
```
V = VR1 + VR1 + VR3 + VR4
```
Con esta última ecuación podemos observar fácilmente otra forma en la que puede expresarse y
entenderse la primera ley de Kirchhoff: en cualquier malla la suma de tensiones aplicadas
es igual a la suma de caídas de tensión de sus elementos componentes.

En este apunte fueron expresados los principios de las leyes de Kirchhoff y su aplicación en
circuitos sencil os, sin embargo veremos que estas leyes resultan de mucha utilidad para analizar
circuitos más complejos con mayor cantidad de mal as y nodos.

---
Apunte realizado por Martín Matus y Esteban Calcagno para uso interno de la materia Taller
de Instrumental y Equipos I de la Carrera de Composición con Medios Electroacústicos de la
Universidad Nacional de Quilmes.
