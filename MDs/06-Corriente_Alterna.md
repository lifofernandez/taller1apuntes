Corriente Alterna

Para comenzar a entender la diferencia entre corriente continua CC (que es el
tipo que venimos estudiando hasta ahora) y la corriente alterna CA, debemos
entender algunos conceptos básicos de teoría de señales eléctricas y
trigonometría.

Señales Eléctricas

Definiremos señal eléctrica en general a una señal cuyos valores de tensión y
corriente se comportan de determinada manera al paso del tiempo. Para poder
hacer una representación gráfica de estas señales debemos utilizar un sistema
apropiado. En este caso utilizaremos el sistema de ejes cartesianos de dos
dimensiones, que se representa de la siguiente manera:

Como vemos tenemos un eje horizontal (eje X de absisas) donde nosotros
representaremos el tiempo, o sea que si nos movemos hacia la derecha sobre
el eje horizontal, el tiempo aumenta, y si nos movemos hacia la izquierda el
tiempo disminuye, y un eje vertical (eje Y de ordenadas) que representará la
amplitud de la señal, o sea si voy hacia arriba por este eje la amplitud aumenta
y si voy para abajo la amplitud disminuye.
Como vemos, los ejes se cruzan en un punto en particular. Ese cruce es el
origen del eje cartesiano, y muestra el comienzo “0” de ambos ejes. A la
derecha del origen los valores de X son positivos, a la izquierda del origen los

valores de X son negativos, arriba del origen los valores de Y son positivo y
abajo son negativos.
Esto se observa aun más claro cuando entendemos que el sistema cartesiano
se divide en 4 cuadrantes:

El cuadrante I tiene valores de X e Y positivos.
El cuadrante II tiene valores de X negativos e Y positivos.
El cuadrante III tiene valores de X negativos e Y negativos.
El cuadrante IV tiene valores de X positivos e Y negativos.

En realidad para la representación de señales eléctricas solo utilizaremos los
cuadrantes I y IV. Gracias a estos datos ya tenemos un sistema donde poder
graficar los valores de amplitud en función del tiempo de una señal eléctrica.

El sistema de notación que se utiliza para representar a una señal eléctrica
esta dado de la siguiente manera.

Cuando hablamos de X(t), nos referimos a alguna magnitud que depende del
tiempo.
Cuando hablamos de v(t) nos referimos a una tensión cuya amplitud depende
del tiempo
Cuando hablamos de i(t) nos referimos a una corriente cuya intensidad
depende del tiempo.

Por lo general se designa la palabra señal para referirse a magnitudes que
varían de alguna forma en el tiempo. Interpretaremos a las magnitudes
constantes como casos particulares de señales eléctricas.

Características comunes
Una de tantas clasificaciones que podemos hacer con respecto a este tipo de
señales, se basa en su comportamiento al paso del tiempo. Así podemos
clasificar señales constantes en el tiempo, y señales variantes en el tiempo.
Las señales que llamamos constantes son las que se mantienen
imperturbables con el correr del tiempo, o sea cuyo valor no varía con el paso
del tiempo:

Las señales variantes obtienen su nombre justamente por que tienen la
característica de variar sus valores con el correr del tiempo:

Como se puede observar fácilmente, las señales mostradas siempre se
encuentran dentro de un solo cuadrante del plano cartesiano. Teniendo esto en
cuenta, podemos describir otra característica de las señales eléctricas, que
presentará otra clasificación posible.
Entonces, nos encontramos ahora con las que se llaman señales continuas y
alternas.

Las señales continuas son aquellas que siempre presentan un mismo signo
con el paso del tiempo, sean constantes o variantes. Las posibilidades no son
muchas o sus valores de amplitud (eje Y - vertical) toman valores positivos (Y
mayor a cero) o nulos (0), o toman valores negativos (Y menor a cero) o
nulos (0). En el caso de la corriente esto significa que siempre circulará
hacia un solo lado en todo instante de tiempo, aunque su valor puede variar.
Las gráficas arriba mostradas representan ambas, señales continúas.

En cambio, las señales alternas varían el signo de su magnitud con el paso
del tiempo. Esto quiere decir que este tipo de señales ocupan el cuadrante I y
el cuadrante IV del eje cartesiano para eslongarse. Así la corriente cambiará de
dirección cuando se pase de un cuadrante a otro. Por estas características, una
señal alterna nunca puede ser constante.

En la gráfica de arriba se observa inmediatamente la diferencia: Ambas señales
son variantes en el tiempo, pero una de ellas ocupa solo el primer cuadrante
(señal continua) y otra los cuadrantes I y IV (alterna).

Hasta este momento, solamente habíamos realizado cálculos y aplicado leyes
teniendo en cuenta que las señales que utilizábamos eran señales Continuas y
constantes. Una señal continua variable puede ser la amplitud observada sobre
un potenciómetro siendo cambiado en el tiempo.
Comenzaremos entonces el estudio específico de las señales alternas, en
nuestro caso señales de corriente alterna (CA).

Señales Alternas
Nos centraremos ahora en describir algunas de las características más
importantes de las señales alternas, que nos permitirá poder comenzar a
trabaja.
Las señales alternas pueden ser periódicas o aperiódicas. Pero que significa
esto?

Las señales periódicas toman su nombre de las características que poseen de
repetir sus valores cada cierto tiempo, o sea que pueden poseer un patrón de
repetitividad, por ejemplo:

Como se observa en la gráfica los valores se van repitiendo. De aquí se
determinan ciertas características y convenciones que se hacen con respecto a
la señal periódica. A este patrón de repeticiones, o sea desde que la onda
comienza en 0, pasa por los valores positivos, baja hacia los negativos y vuelve
a cero, se lo denomina ciclo de la onda, como indica las flechas en la gráfica.
A todo este tiempo (T) que la onda tarda en desarrollarse se le llama periodo
y es el equivalente en unidades de tiempo del ciclo de la onda.
Luego, cuando ya tenemos estas definiciones, se llama frecuencia a la
cantidad de veces que este ciclo de onda sucede en 1 segundo, y su
magnitud se mide en Hertz (Hz), o sea la cantidad de ciclos por segundo que
sucede la onda.
Entonces, la frecuencia se traduce como la relación existente entre la
frecuencia y el periodo de la señal, y su fórmula es la siguiente:

Donde f es la frecuencia a calcular. T es el periodo, y el uno que allí aparece
representa la ventana temporal de 1 segundo donde se medirá la cantidad de
veces que el ciclo de onda, o el periodo, sucede.
Así si por ejemplo:
Si nuestra señal tiene un periodo de 1 segundo, la frecuencia será entonces de
1 Hz.
Si la señal tiene un periodo de 5 segundos, como la de la gráfica, la frecuencia
será igual a 1 / 5 = 0.2 Hz, lo que indica que la señal solo ha desarrollado 1/5
de su forma en 1 segundo.
Si la señal tiene un periodo de 0.2 segundos, entonces la frecuencia será igual
a 1 / 0.2 = 5 Hz.

Un problema inverso sería el de tratar de saber cuanto es el periodo de una
señal que tiene una frecuencia de 440 Hz, que dicho sea de paso es
justamente la frecuencia que equivale al LA central de la escala tonal.
Para hacer esto tendríamos que despejar la formula de frecuencia. T pasa al
lado izquierdo de la ecuación multiplicando a f, y luego pasamos f dividiendo a
1. La ecuación quedaría entonces:

T = 1 / f

f ya lo tenemos (440 Hz), y entonces el periodo sería igual aproximadamente a
0.002272 seg, o en milisegundos 2.272 ms (recuerden que para pasar a
milisegundos una magnitud solo se debe correr la coma tres lugares hacia la
derecha).

Este tipo de señales son las que más utilizaremos en esta primera etapa.

En contraparte a las señales periódicas, existen las señales aperiódicas que
justamente son las señales a las cuales no se le puede definir un periodo, por
que justamente no se repiten en el tiempo, sino que varían su magnitud con el
correr de este.
Muchas de las señales de audio poseen estas características, y puede
llamárselas aperiódicas, aunque a veces, si el análisis de la señal se hace con
ventanas de análisis determinadas podemos encontrar que las señales de
audio pueden estar constituidas por señales periódicas.
Estas son más difíciles de analizar, pero existen formas de hacerlo.
Nos centraremos entonces en las señales periódicas, ya que serán más fáciles
de manejar en esta primera instancia.

Características de las señales periódicas
Hay varios parámetros de amplitud que se pueden identificar en la señal
periódica alterna:

Amplitud de pico: es el valor máximo que tiene una señal. Se mide desde el
valor de amplitud cero, hasta la máxima elongación en amplitud que alcanza la
onda.

Amplitud pico a pico: es el valor que podemos medir desde la máxima
elongación negativa (máximo valor negativo) hasta la máxima elongación
positiva de la onda (máximo valor positivo), en el rango de la amplitud.

Valor eficaz: Debido a que las señales alternas cambian continuamente se
hace necesario determinar un valor intermedio que represente a la señal en los
cálculos y medidas. En el caso particular de la tensión, se define como aquella
que en las mismas condiciones produce los mismos efectos de disipación de
calor en una resistencia eléctrica que una tensión continua del mismo valor.

Valor medio: es el promedio de todos los valores de una señal tomados en un
ciclo. Para señales simétricas como la senoidal, el valor medio es nulo.

Valor instantáneo: Es el valor que toma la señal en determinado instante de
tiempo.

En la gráfica se observan los valores de amplitud explicados. Vp, valor pico,
Vpp, valor pico pico. El valor medio de esta onda es 0.

Por supuesto, pueden existir infinita cantidad de ondas que sean periódicas.
Pero a nosotros nos interesará, debido a unas cuantas características que
ayudan a los cálculos de los diferentes tipos de valores, la onda senoidal.

Señal Senoidal

Se considera a la señal senoidal una de las señales de “prueba” más
interesantes. Se le llama de prueba por que las señales senoidales son las que
se utilizan casi siempre para realizar comprobaciones en los equipos
electrónicos, esto es justamente por las características especiales que posee.

La señal senoidal tiene varias características que la hacen única y diferente a
cualquier otro tipo de señal, como por ejemplo el hecho de que una senoidal
teórica no tiene ni principio ni fin y para utilizarla solo tomamos un momento de
tiempo. Las señales senoidales poseen una doble simetría, una en el eje del
tiempo y otra en el eje amplitud, tomando en cuenta el punto medio de la onda.
En la onda senoidal el valor pico es su valor en amplitud más alto, el valor
pico a pico es la distancia que existe entre su valor de amplitud mas alto y
su valor de amplitud más bajo. El valor medio (o promedio) de un ciclo de
esta señal es cero (0), porque si observamos, el promedio de todos los valores
de un ciclo de esta señal, da cero.
Cuando hablamos antes de valor eficaz, también puede referirse como valor
RMS de la señal (RMS: Root Mean Square – Raíz Media Cuadrática) no es ni
más ni menos que el valor del voltaje o corriente en C.A. que produce el mismo
efecto de disipación de calor que su equivalente de voltaje o corriente directa.
Este valor se obtiene, solo en señales señoidales, dividiendo el valor pico de la
señal por la raíz cuadrada de 2, o lo que es lo mismo multiplicado por 0.707.

Veficaz = Vpico/√2

Veficaz = Vpico*0.707

Si nos referimos a la tensión eficaz entonces el cálculo sería

Vef = Vpico/√2

NOTA:
La electricidad que obtenemos directamente del enchufe de nuestra casa es
una señal alterna, de 220Volts, Valor Eficaz, y con una frecuencia de 50Hz. Si
hacemos la cuenta, el valor pico de esta señal llega a unos 311Volts. A esto se
lo llama generalmente tensión de línea, y se lo conoce directamente como 220
Volts, 50Hz.
Los 50Hz de frecuencia de la tensión de línea, significa que la señal esta
cambiando del valores positivos a valores negativos 50 veces por segundo.
Este tipo de electricidad alterna se comenzó a utilizar, y se sigue utilizando por
tres razones:
- Es fácil de generar
- Es fácil de transportar
- Es fácil de usar.

Simbología

Por supuesto cuando hablamos de CA estamos hablando tanto de una tensión
que es alterna, como una corriente que es alterna. Un generador de tensión en
alterna será simbolizado en un circuito de la siguiente manera:

Ley de Ohm en CA

Una resistencia puede conectarse directamente a un generador de tensión
alterna, como lo hacíamos con una fuente de tensión continua, como lo indica
el siguiente gráfico:

En este caso, y por tratarse de un componente pasivo con respecto a la
frecuencia de la señal (o sea, no afecta a la señal en frecuencia) la tensión y la
corriente se encuentra en fase:

Diagrama vectorial de una tensión y una intensidad sobre una resistencia pura

Como indicamos arriba la resistencia se comporta de forma similar en CC como
en CA. Por lo tanto se sigue cumpliendo la ley de ohm, pero ahora hay que
tener en cuenta que estas leyes se aplican sobre los valores eficaces de
corriente y tensión:

Ief = Vef / R

De esta manera se deduce que para una tensión eficaz determinada aplicada a
una resistencia, la intensidad eficaz que aparece en corriente alterna es del
mismo valor que la intensidad de corriente continúa que recorrería el mismo
circuito.
Por esto se dice que la potencia que se desarrolla en CA es igual a la que se
desarrolla en CC.
Este efecto se puede comprobar experimentalmente. Si se conecta un
wattimetro para medir una resistencia pura, se puede verificar que la lectura del

wattimetro es la misma en CC que en CA, siempre y cuando se utilice los
mismo valores de tensión e intensidad.
Por lo tanto la potencia en CA se puede calcular como:
P = Vef.Ief

NOTA: la tensión eficaz y la corriente eficaz es la que indican los voltímetros y
amperímetros, respectivamente

Las relaciones entre valor eficaz y valor pico serán las siguientes, siempre
teniendo en cuenta que estamos utilizando una señal senoidal:

Tensión:
Vef = Vpico*0.707

Corriente:
Ief = Ipico*0.707

Fase y Desfasaje

La fase de una onda es el momento angular en que se encuentra cuando
empezamos a medirla. Tomando las dos senoidales que tenemos en el
siguiente gráfico observaremos que cada una de estas posee una fase
diferente a la otra:

Cuando dos señales idénticas como las que vimos se encuentran en diferente
fase, se dice que están desfasadas.
Una vez explicado esto podemos ver la ecuación de la onda senoidal y
entender que es cada factor que la forma:

V1(t) y V2(2)= Señales senoidales que se desarrollan en el tiempo
VP = amplitud de la señal, su valor pico en ese instante de tiempo
Sen() = es una señal senoidal
2PI = velocidad angular
f = frecuencia de la onda
t = momento de tiempo en el que se desarrolla
+ PI/2 = fase de la onda, en este caso la segunda onda tendrá una fase
diferente.

Apunte realizado por Esteban Calcagno y Martín Matus para uso interno exclusivo de la
materia Taller de Instrumental y Equipos I de la Carrera de Composición con Medios
Electroacústicos de la Universidad Nacional de Quilmes.

