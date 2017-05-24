# Fuentes de Alimentación

## Introducción
Muchos circuitos y componentes electrónicos necesitan ser alimentados mediante una
señal de corriente continua (por ejemplo, la mayoría de los circuitos integrados). Esto
puede realizarse de dos formas diferentes:

- Mediante pilas: las cuales entregan una corriente continua, pero tiene desventajas
como por ejemplo que se gastan y que a veces no pueden producir la potencia
suficiente
- Mediante una fuente de alimentación: comúnmente las utilizamos todos los días para
enchufar muchos de los diversos aparatos electrónicos.

En general las fuente de alimentación que usamos a diario se enchufan directamente a
la red eléctrica doméstica, que como sabemos es de corriente alterna (220 volts CA).
Pero en su salida las fuentes de alimentación pueden tener muchos valores de tensión
diferentes además de que, por supuesto, se obtiene corriente continua.
La idea de esta clase es entender como se transforma una tensión alterna como la de
la red hogareña de 220 Volts CA a un valor de CC, y además como se puede obtener
diversos valores diferentes de tensión.

## Fuente de alimentación – Bloques

Las fuentes de alimentación que vamos a estudiar pueden dividirse en general en
cuatro grandes bloques que desarrollan funciones diferentes:

- Transformador
- Rectificacióni
- Filtrado
- Regulación

Repasaremos uno por uno cada uno de estos ítems para entender como funcionan las
fuentes de tensión.

### Transformador – Inducción electromagnética

Una bobina que es recorrida por una corriente variable (CA) desarrolla un campo
magnético variable que pueden inducir fuerzas electromagneticas al atravesar otras
bobinas que se encuentran en su proximidad.

Cuando cerramos la llave, el instrumento (galvanómetro) nos marcará el paso de una
pequeña corriente, pero esta volverá a cero. Si abrimos nuevamente la llave el
instrumento indicará una corriente, pero en el sentido contrario. 

Esto se da por que al cerrar el interruptor, se aplica a la bobina A una corriente que tiende a crecer desde 0
hasta su valor nominal. Esta variación produce un campo magnético variable y
creciente sobre la bobina A. Como la bobina B se encuentra muy próxima a la bobina
B, el campo magnético de la bobina A la atraviesa, produciendo de esta manera el
principio de inducción electromagnética, y por lo tanto produciendo una corriente
variable.
Esta corriente solo se producirá mientras el campo magnético sea variable,
que es lo que pasa hasta que la corriente en la bobina A se estabiliza. Cuando se abre
nuevamente la llave la corriente vuelve a variar desde su valor nominal a 0, varia el
campo magnético y se produce la inducción, pero en este caso, la corriente es
contraria a la primera.

Al utilizar un generador de corriente alterna, la corriente se mantiene variable y de
esta manera tenemos inducción electromagnética constante, produciendo una
corriente variable en la otra bobina, y por lo tanto, si tenemos una carga a la salida,
produciendo una tensión inducida.

Como sabemos los inductores están formados por espiras de material conductor, o sea
material conductor enrollado alrededor de un núcleo. El transformador no es más ni
menos que dos bobinas aisladas, con núcleo ferromagnético, pero que se encuentran
muy próximas, facilitando de esta manera la inducción electromagnética.
A la espira a la cual se le aplica la corriente alterna se la llama primario o inductor, y a
la que es inducida se la llama secundario o inducida. Ambas bobinas están
eléctricamente aisladas.

Cada una de estas dos bobinas posee una cantidad de espiras, por lo que tenemos un
Número de Espiras del Primario (Np) y un Número de Espiras del Secundario (Ns). El
número de espiras en ambas bobinas determina la relación directa entre las tensiones
que tenemos entre le primario (Vp) y el secundario (Vs):

Vp/Vs = Np/Ns

Si despejamos entonces:

Vs = Vp * Ns/Np

Esta relación determinará que tipo de transformador tenemos:

Tipos de trasformadores en relacion a la tension:

- Elevador: Ns > Np -> Vs > Vp 

- Aislador: Ns = Np -> Vs = Vp

- Reductor: Ns < Np -> Vs < Vp -

Las últimas dos configuraciones se utilizan como transformadores de tensión, como
también para procesar audio (telefonía).

Ejemplos:

10:1 220V 22V
1:10 220V 2200V

En todos los casos donde tenemos un transformador se entra con corriente alterna y
se sale con corriente alterna.

La **potencia en el primario y el secundario siempre será la misma, solamente se
producen las variaciones necesarias de corriente para equilibrar ambos lados**:

O sea, por ejemplo en el transformador elevador (12V 24V) 

Si Ps = Pp
-> Vs > Vp
-> Is < Ip

En un transformador reductor (220V 24V)

Si Ps = Pp
-> Vs < Vp
-> Is > Ip

De esta manera no hay desbalances de potencia, ya que la corriente se adecua a la
situación.
Con respecto a la frecuencia, esta se mantiene inalterable cuando es inducida al
secundario, o sea tenemos la misma frecuencia en el primario como en el secundario.

De esta manera, mediante el uso del transformador, tenemos el primer paso cumplido
para comenzar el diseño de la fuente de alimentación: **transformamos la tensión que
nos viene de la red domestica de 220V CA a otro valor de CA (más pequeño, más
grande, etc).**

Otras consideraciones de los transformadores:

Que sucede cuando no tenemos ninguna resistencia de carga en el secundario?

Para contestar esto debemos tener en cuenta que las bobinas de un transformador
son de cobre, y por lo tanto tienen una resistencia asociada, aunque esta sea pequeña.
Al no tener ninguna resistencia en el secundario, este comienza a calentar debido a
que comienza a disipar la potencia inducida por esta resistencia asociada.
Esta resistencia se traduce directamente como perdidas en el cable, por eso comienza
a calentar.
Además hay que tener claro que el núcleo también tiene corrientes que lo recorren
debido a que también es atravesado por los campos electromagnéticos del primario, y
esto produce perdidas. Estas corrientes son denominadas parasitas, y este efecto se
minimiza utilizando láminas de metal en vez de un bloque de metal para el núcleo.

Entonces cuando se tiene un transformador hay que tener en cuenta las siguientes
perdidas:

- Pérdidas por la resistencia del cobre, tanto en el primario como en el
secundario.
- Pérdidas por el núcleo por las corrientes parasitas y el efecto de histéresis.

Estas pérdidas producen elevación de temperatura.

Por lo que la potencia del primario se traduce como la potencia del secundario + las
perdidas de todo el bloque.

### Rectificación

Una vez tenemos una tensión alterna más baja gracias a la acción del transformador,
debe existir una forma de poder **transformar la tensión alterna en tensión continua**. En
esta etapa entran en juego los circuitos de rectificación. Un circuito de rectificación es
ni más ni menos un circuito que “transforma” una tensión que alterna de positivo a
negativo, dejando solamente una de las partes de la señal. Este trabajo lo realiza sin
problemas un componente que ya conocemos: los diodos.

Como hemos visto, un diodo puede polarizarse solamente de una manera, y de esta
manera permitirá el paso de la corriente, si se polariza a la inversa, no habrá
conducción de corriente. Gracias a estas características, se puede rectificar la tensión
alterna, convirtiéndola en continua.
Ahora analicemos el siguiente circuito que se denomina Rectificador de Media Onda:

Si aplicamos una tensión alterna, el diodo solo dejara pasar la corriente cuando la
señal se encuentre en su semiciclo positivo:

Convirtiendo de esta manera, la tensión alterna, en continua.  

Igualmente en este caso aun no tenemos una tensión constante, ya que se observan variaciones importantes de
tensión continua. Para mejorar aun más esto se utiliza lo que se llama Rectificador de
Onda Completa, en el que se utilizan dos pares de diodos, y el transformador posee
una descarga a tierra para tener una referencia, que ayude a mejorar la rectificación.

Cuando la polaridad de la CA es + -, el diodo 1 deja pasar a este, diseccionándolo a la
resistencia de salida que tiene la tierra como referencia:

Cuando la polaridad cambia a - +, el diodo que conduce es el 2, dejando pasar la
corriente, pero también disponiéndola sobre la resistencia de carga, que al estar
referenciada a masa, tendrá nuevamente polaridad positiva:

De esta manera la tensión de salida será nuevamente continua, pero las variaciones
serán menos bruscas:

Aun así seguimos teniendo una tensión continua pulsante.
Otra configuración muy conocida que realiza una rectificación de onda completa es el
llamado Puente Rectificador de Diodos. El circuito de esta configuración es el
siguiente:

Como vemos este circuito lleva cuatro diodos. Como funciona esto? De la siguiente
manera:

Cuando la tensión alterna tiene polaridad + -, el los diodos D1 y D2 son los que
conducen:

Cuando la polaridad es - +, los que conducen son los diodos D3 y D4:

De esta manera siempre estamos entregando a la resistencia un valor positivo con
respecto a la tierra del circuito, y por lo tanto se rectifican tanto el semiciclo positivo
como el negativo, obteniendo la siguiente corriente continua aunque todavía pulsante:

Gracias a la rectificación mediante diodos, ya tenemos otra parte importante de
nuestra fuente, y hemos llevado una señal de CA a CC. Sin embargo es evidente que
hay que mejorar la pulsación que todavía tenemos en la señal, y esto lo hará la
siguiente etapa, la de filtrado.

### Filtrado

Mediante el uso de un capacitor a la salida del rectificador podemos lograr que la
pulsación de la señal sea minimizada.

Esto se debe a que el capacitor funciona como un filtro ya que elimina las pulsaciones,
aunque aun deja un pequeño rizado en la señal. Recordemos como trabaja el capacitor
en continua.
Mediante la utilización del puente de diodos (rectificador de onda completa) y el
capacitor (de entre 220uf y 5000uf, electrolítico) logramos un ciclo de carga y descarga
del capacitor (5.R.C) que no deja que la pulsación se lleve a cabo. Aun así como el
capacitor llega a descargarse un poco, se produce el rizado.
Si el capacitor se descarga muy lento el valor medio de la señal aumenta, si el valor de
la resistencia de carga baja, el capacitor se descarga más rápido y el valor medio baja.

Gracias a estas tres etapas tenemos una fuente de tensión continua y bastante
constante, pero con un poco de rizado que hace variar el valor de tensión. A este tipo
de fuentes se la llama **Fuente de Tensión no Regulada** por que modifican su tensión de
salida dependiendo mucho de la carga que le pongamos.

### Fuente de Tensión Regulación

En la fuente no regulada la tensión de salida no es constante debido a que esta
depende directamente de resistencia con la cual se carga, ya que esta afecta
directamente a la descarga del capacitor y por lo tanto al rizado final. También hay que
tener en cuenta que la tensión con la cual se alimenta a la fuente (red hogareña)
también varía bastante con respecto a los 220 V que conocemos.

Si RL aumenta, aumenta la tensión de salida.
Si RL baja, disminuye la tensión de salida.

El peligro de tener una fuente no regulada es que con resistencias de carga muy bajas
la tensión de salida sube demasiado y el equipo puede no estar preparado para esto,
por lo que puede ser dañado.

Para poder realizar una regulación efectiva existe un componente que se llama
Regulador de Tensión.

### Regulación

El regulador de tensión posee tres patas, una de entrada, una de salida y
otra de tierra. Los reguladores pueden tener varios valores de salida.

7815 Regulador positivo (78) – Tensión de salida regulada (15)
7915 Regulador negativo (79) – Tensión de salida regulada (15)

Las tensiones más utilizadas pueden ser: 05 – 08 – 09 – 12 – 15

En el regulador positivo Vin y Vout son positivos con respecto a GND.
En el regulador negativo Vin y Vout son negativos con respecto a GND.

El circuito necesita tensión continua y constante. La función del regulador es mantener
una tensión constante dentro de ciertos límites.

Por ejemplo: Utilizando un regulador de 15 volts, el 7815, la entrada debe estar entre
estos parámetros:

17v <= Vin <= 30v

Ambos son valores Pico de tensión.

Estos valores se deben tener en cuenta para obtener una buena regulación de tensión.
Si la tensión baja de los 17v, la señal comienza a copiar el rizado que aparece después
del capacitor.

Si se pasa de los 30v, las condiciones de regulación son peores, ya que el componente
no se comporta como debería, y no esta asegurada una tensión de salida de 15v. Ya a
una tensión de entrada de 35V, el regulador se destruye.
Las especificaciones de este componente dicen que la carga no debe superar los 1.5A
de corriente (o sea no se debe poner una resistencia de carga que produzca esta
corriente – 10 ohm), y la mínima puede ser de 0A, o sea el circuito puede estar abierto,
cosa que no afectará al componente.

Si establecemos por ejemplo una tensión pico de entrada de 22v, lo que estaría dentro
del margen de utilización, podemos llegar a calcular que tipo de transformador
necesitamos.

Como 22v es el valor pico de la señal, para **calcular el valor eficaz de la salida del
secundario del transformador solamente hacemos la cuenta**:

Vs = Vp / √2 = 22V / √2 = 15.55vef

De esta manera vemos que necesitaremos un transformador que pase de 220v a
15.55v.
Esto significa que la relación entre espiras debe ser de 14.14:

220v / 15.55 = Np / Ns = 14.14

También podemos calcular cual sería la tensión que debe tener la red eléctrica para
llegar al límite de 30vpico en el secundario, lo que respondería a una suba de tensión:

Vef secundario = 30v / √2 = 21.21vef

Vlinea / 21.21vef = 14.14 Vlinea = 21.21vef x 14.14 = 299.9V

O sea la tensión de línea debería llegar a casi 300V para que nuestro regulador
comience a funcionar mal.

Podemos seguir pensando en cual sería la tensión mínima de línea para llegar a los 17v
pico mínimos que necesita el regulador.

Veficaz del secundario = 14vi / √2 = 12.02vef

Vlinea / 12.02vef = 14.14 Vlinea = 12.02vef x 14.14 = 169.66V

De esta manera tenemos ya armada nuestra fuente de alimentación regulada, que
puede también llamarse Fuente d Tensión Convencional.

Existe otro tipo de fuentes de tensión reguladas: las **conmutadas o Switching**, muy
utilizadas para alimentar computadoras, y que poseen varias ventajas con respecto a
las fuentes convencionales.
Estas trabajan haciendo conmutar transistores a alta frecuencia entre la zona activa y
pasiva de trabajo del transistor. Así se forma una onda cuadrada de alta frecuencia que
alimenta a transformadores de núcleo de ferrite, que son muchos más livianos que los
transformadores comunes, y tienen la capacidad de trabajar mucho mejor en altas
frecuencias.
Las ventajas son:

1- poseen un amplio margen de trabajo en tensión de entrada
2- Su peso físico es muy bajo comparado a una fuente convencional
3- mayor eficiencia de transformación de tensiones, y por eso menor calentamiento.

Las desventajas son:

1- son más complejas de construir.
2- producen ruido de alta frecuencia que debe ser aislado cuidadosamente.

Apunte realizado por Esteban Calcagno y Martín Matus para uso interno exclusivo de la materia Taller
de Instrumental y Equipos I de la Carrera de Composición con Medios Electroacústicos de la Universidad
Nacional de Quilmes.

