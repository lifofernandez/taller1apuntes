CIRCUITOS EN SERIE Y EN PARALELO

Los resistores se encuentran entre los componentes pasivos más utilizados en circuitos
electrónicos. Su característica principal es que presentan cierta resistencia al flujo de corriente
eléctrica, a diferencia de los materiales conductores que no presentan (idealmente) resistencia
alguna o los materiales aislantes que impiden completamente el flujo de corriente (o dicho en
otros términos, poseen resistencia infinita). Los más comunes y económicos son los de carbón.
La resistencia eléctrica se mide en Ohm, unidad que también puede representarse con la letra
griega omega: Ω . En los esquemas de circuitos los resistores se simbolizan de la siguiente forma:

Existen diversas formas de interconectar dos o más resistores, siendo posible encontrarse con
circuitos como el siguiente:

A continuación se expondrán los principios más sencillos de conexión de resistores, que servirán
como base para estudiar circuitos más complejos.

Conexión de resistores en serie
Si en vez de un resistor conectamos dos de la siguiente forma, esto es lo que se llama circuito
serie

La diferencia es que aquí, en vez de tener un resistor de 1Ω tenemos dos, por lo tanto la
resistencia total al flujo de corriente será del doble. Es decir que podemos representar el circuito
anterior por uno equivalente como el que sigue
1

en el cual la resistencia total es la suma de las dos resistencias:

RT = R1 + R2 = 1Ω + 1Ω = 2 Ω

Al duplicarse la resistencia , la corriente que circula por el circuito es de la mitad respecto al
ejemplo anterior. Esto se obtiene aplicando, como hemos visto, la ley de Ohm:

I = V = 1 Volt = 0,5 Amperes

RT 2 Ω

Un aspecto importante a tener en cuenta es que al seguir manteniéndose 1 Volt como valor de
tensión suministrada por la fuente, se le está aplicando a cada resistor 0,5 Volts (que es lo mismo
que decir que cada resistor posee una caída de tensión de 0,5 Volts). Esto sucede de esta forma
porque los dos resistores poseen valores iguales, si fueran distintos la caída de tensión en cada
uno de ellos sería proporcional a sus valores de resistencia.
Por ejemplo si R1 = R2 = 2Ω la caída de tensión en cada resistor seguiría siendo de 0,5 volts (si
bien disminuiría el flujo de corriente a 0,25 A, ya que el valor de resistencia total pasó a ser de
4Ω).
Si R1 = 3Ω y R2 = 1Ω, la corriente circulante seguiría siendo de 0,25 A, sin embargo la caída de
tensión en cada uno de los resistores variaría. Se puede obtener la caída de tensión en cada
resistor aplicando nuevamente la ley de ohm:

Caída de tensión en R1: VR1 = I . R1 = 0,25A . 3Ω = 0,75 V
Caída de tensión en R2: VR2 = I . R2 = 0,25A . 1Ω = 0,25 V

Vemos como las caídas de tensión en los resistores son proporcionales a sus valores de resistencia,
mientras que la caída de tensión total sigue siendo la aplicada por la fuente de tensión, es decir

VR1 + VR2 = 0,25V + 0,75 V = 1 V = V

De lo visto se deduce una noción fundamental para analizar los circuitos en serie: la tensión
aplicada se divide entre sus componentes mientras que la corriente que circula es única. Más
adelante veremos que este es el principio del divisor resistivo de tensión.
Pueden conectarse tantos resistores en serie como se desee, manteniéndose siempre los principios
mencionados anteriormente, y dando como resultado que la resistencia total equivalente será la
suma de todas las resistencias conectadas en serie.
2

Circuito en serie : conceptos

•
La resistencia total de resistores en serie es la suma de los valores de sus resistencias.
•
Para resistores en serie la resistencia total siempre aumentará cuando sean agregados
elementos adicionales en serie.
•
Al aumentar el número de resistores en serie, el nivel de corriente disminuye para la misma
tensión aplicada.
•
Los elementos en serie de un circuito pueden intercambiarse sin afectar la resistencia total,
la corriente o la potencia de cada elemento.
•
Por todos los elementos de un circuito serie circula la misma corriente.
•
La tensión aplicada en un circuito serie equivale a la suma de las caídas de tensión de sus
elementos.
•
La caída de tensión en los elementos resistivos se dividirá proporcionalmente en función de
la magnitud de sus niveles de resistencia.
•
La caída de tensión en un resistor en un circuito serie es igual al valor de ese resistor
multiplicado por la tensión total de los elementos en serie, dividido entre la resistencia total
de los elementos en serie. Esto se denomina regla del divisor de tensión.

Conexión de resistores en paralelo
Otra de las maneras más sencillas de conectar dos (o más) resistores es la que se conoce como
conexión en paralelo:

Aquí la diferencia es que la tensión aplicada a los dos resistores es la misma, como puede
observarse, siendo lo que varía el flujo de corriente circulante.
Para estudiar el circuito equivalente a este (reemplazando como hicimos anteriormente los dos
resistores por uno solo con resistencia total equivalente) debe tenerse en cuenta que en el circuito
paralelo la conductancia total es igual a la suma de las conductancias.
La conductancia (G) se mide en Siemens y se define como la facilidad con que puede establecerse
corriente en un material (es decir, se define inversamente a la resistencia). Para calcularla
simplemente se calcula la inversa del valor de resistencia:

G = 1

R

3

Por lo tanto, en el circuito paralelo anterior, sabiendo que la conductancia total es igual a la suma
de las conductancias de los resistores podemos obtener la resistencia total equivalente de la
siguiente forma:
Gt = G1 + G2

1 = 1 + 1
Rt R1 R2

1 = R2 + R1
Rt R1 . R2

Rt = R1 . R2
R1 + R2

Como puede verse claramente en el diagrama anterior, en el circuito paralelo la tensión aplicada es
la misma en los dos resistores (la tensión de la fuente), siendo lo que varía la corriente que circula
por los resistores. Si tenemos dos resistores de 1Ω por cada uno de ellos circulará 1 A, siendo la
corriente total del circuito (es decir, la que se exige a la fuente que entregue) 2 A.

Esto puede corroborarse sustituyendo el circuito paralelo por su resistencia equivalente

De lo visto se deduce la noción fundamental para analizar los circuitos en paralelo: la corriente que
circula se divide entre sus componentes mientras que la tensión es la misma. De manera análoga
al circuito serie puede haber tantos resistores en serie como se desee. Un forma sencilla de
calcular la resistencia total equivalente es tomar de a dos resistores en paralelo e ir calculando su
valor equivalente.

Por ejemplo, para calcular la resistencia total equivalente del circuito previo de cuatro resistores en
paralelo podemos calcular en primer lugar el valor de R1 en paralelo con R2 y el valor de R3 en
4

paralelo con R4. Luego calculamos el paralelo de estos valores y esto nos dará el valor de
resistencia total.
Un aspecto útil a tener en cuenta es que siempre que se calcule el paralelo de dos resistencias de
igual valor, la resistencia total equivalente será de la mitad (por ejemplo, si los dos valores de
resistencias conectadas en paralelo son de 8 Ω, el valor de la resistencia total equivalente será de
4Ω).

Circuito en paralelo : conceptos

•
En un circuito con resistores en paralelo, la conductancia total es la suma de las conductancias
individuales.
•
Para resistores en paralelo, la resistencia total siempre disminuirá cuando sean agregados
elementos adicionales en paralelo.
•
Al aumentar el número de resistores en paralelo, el nivel de corriente de entrada aumenta para
la misma tensión aplicada.
•
Los elementos en paralelo pueden ser intercambiados sin cambiar la resistencia total, la
corriente o la potencia de cada elemento.
•
La tensión en los elementos de un circuito paralelo es la misma.
•
La corriente entregada por la fuente en un circuito paralelo es igual a la suma de las corrientes
individuales de cada rama.
•
La corriente siempre busca la trayectoria de menor resistencia, es decir, cualquiera sea el
número de resistores en paralelo la corriente se dividirá entre ellos de manera inversamente
proporcional a sus valores de resistencia.
•
La resistencia total equivalente de resistores en paralelo es siempre menor que el valor de
resistencia del resistor más pequeño.
•
Puede obtenerse la corriente que circula por un resistor en paralelo con otro multiplicando a la
corriente total de entrada por el valor de resistencia del otro resistor, y dividiendo el resultado
por la suma de los valores de sus resistencias. Esto se denomina regla del divisor de corriente.

Apunte realizado por Martín Matus y Esteban Calcagno para uso interno exclusivo de
la materia Taller de Instrumental y Equipos I de la Carrera de Composición con
Medios Electroacústicos de la Universidad Nacional de Quilmes.
5

