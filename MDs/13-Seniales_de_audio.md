# SEÑALES DE AUDIO, CABLES Y CONEXIONES
Cuando hablamos de señales de audio estamos haciendo referencia a señales de
tensión variables en el tiempo, que pueden ser convertidas por transductores en base a
señales acústicas, o que pueden ser producidas por dispositivos específicos (por ejemplo,
un teclado). Estas señales se utilizan para diversos
fines, como por ejemplo la grabación o el refuerzo de
sonido en vivo1.

A continuación se resumirán algunos aspectos
importantes referentes a las señales de audio y a la
manera en que se transmiten y se interconectan los
equipos que trabajan con estas señales. Este apunte no
pretende abarcar en profundidad todos estos aspectos
sino presentar una aproximación al tema, que podrá ser
desarrollado posteriormente.

## NIVELES DE SEÑAL
Como ya se mencionó, la mayor parte del equipamiento utilizado para diversos fines
relacionados con el sonido y la música trabaja principalmente con señales de audio.
Estas señales no son otra cosa que señales de tensión alterna con diversas características.
Uno de los aspectos más importantes respecto a los tipos de dispositivos a utilizar y
a su correcto uso, tiene que ver con los niveles de tensión que posean las señales de
audio con las que trabajemos. Es posible establecer una clasificación general de las
señales según su nivel de tensión nominal de la siguiente manera:
```
TIPO DE SEÑAL      NIVEL NOMINAL

Nivel de potencia  Mayor a +30 dBu
Nivel de línea     Entre -20 dBu y +30 dBu
Nivel de micrófono Menor a -20 dBu
```
Con valor nominal nos referimos a que se toma como promedio este valor pudiendo las
señales poseer, en determinadas circunstancias, valores inferiores o superiores a los
límites estipulados.

### Nivel de micrófono (o bajo nivel)
Son aquel as señales que l egan hasta -20 dBu aproximadamente (es decir 77,5 mV de
valor eficaz). Ejemplos típicos de señales con este nivel son las producidas por micrófonos,
cápsulas fonocaptoras, o cabezales de reproducción magnética, considerando que no
posean ningún tipo de preamplificación.

nota: En este apunte nos referiremos exclusivamente a las señales de audio analógico, y no serán tratadas las
señales de audio digital.

### Nivel de línea (o nivel medio)
El rango de estas señales se encuentra entre -20 dBu y +30 dBu (24,5 V). Trabajan con
nivel de señal de línea los siguientes dispositivos, entre otros: teclados (sintetizadores,
samplers, etc.), las salidas de preamplificadores y consolas, reproductores de CD, DAT,
VHS, etc., y la mayoría de los procesadores y efectos de audio (procesadores dinámicos,
ecualizadores, efectos como delay y reverb, entre otros). Valores nominales de línea
típicos son -10 dBu (245 mV), +4 dBu (1,23 V) y + 8 dBu (1,95 V).

## Nivel de potencia (o alto nivel)
Todas las señales que posean valores iguales o superiores a +30 dBu (24,5 V). Son
principalmente las señales de salida de los amplificadores de potencia que alimentan a los
parlantes.

## CONEXIONES BASICAS
Aunque la conexión de señales de audio sea algo relativamente estandarizado, es
habitual encontrar problemas de interconexión entre componentes, incluso en ámbitos
profesionales. Parte de la solución a este problema es utilizar dispositivos que sean
eléctricamente compatibles. La otra parte es saber como conectarlos en forma adecuada y
consistente.

Hemos visto en detalle los niveles nominales operativos para equipos de audio. Uno
de los niveles de línea estándar es +4 dBu (también l amado nivel Pro). Si nos aseguramos
de que todos los equipos en nuestra cadena de audio cumplan con esta norma evitaremos
muchos de los problemas de interconexión más comunes. Sin embargo, existe cada vez
más equipamiento que trabaja con niveles de señal de -10 dBV (a veces denominado
Consumer o Semi-pro) que provee buena calidad, generalmente a más bajo costo que el
equipo Pro.

Existen varias soluciones a esta cuestión. Reconociendo la necesidad del mercado
de tener la opción de utilizar equipo con niveles de -10 dBV en algunas etapas de la
cadena de audio (por ejemplo, diversos equipos de reproducción y grabación de audio, y
procesadores de audio externos), algunos fabricantes proveen salidas con los dos niveles
(+4 dBu y -10 dBV). Por otra parte, algunas compañías ofrecen interfaces activas que
convierten los niveles de señal entre estos valores.

### Conexiones balanceadas y no balanceadas

Las conexiones no balanceadas utilizan dos conductores, uno con un potencial de
tierra o masa y el otro que l eva la señal. Los equipos que operan a -10 dBV
invariablemente utilizan conexiones no balanceadas.

Las conexiones balanceadas usan dos conductores: cada uno l eva la misma señal,
pero una de el as está invertida de fase. Pueden o no estar referidas a tierra; si no lo
están se denominan conexiones flotantes. Una conexión balanceada referida a tierra
requiere tres conductores, el tercero de el os sirviendo como potencial de tierra (una
conexión flotante puede tener un tercer conductor, pero en este caso solo se utiliza como
blindaje y no se conecta al potencial de tierra del circuito).

Las conexiones balanceadas siempre son preferibles a las no balanceadas porque
son menos susceptibles a captar interferencias o ruido. Como puede observarse en el
gráfico, el principio por el cual funcionan las lineas balanceadas tiene que ver con que al
llegar las dos señales invertidas de fase a la entrada del dispositivo (por ejemplo una
consola) se produce nuevamente la inversión de la fase de una de el as y se suman dando
como resultado una señal del doble de amplitud, en donde (idealmente) cualquier ruido o
interferencia que hayan sido captados por la línea serán cancelados.

En los casos en que se necesite recorrer largos trayectos con señales de audio,
sobre todo de bajo nivel (por ejemplo en las patcheras que l evan señales de micrófono
desde el escenario hasta la consola de F.O.H.), el uso de señales balanceadas es
indispensable. El equipo de audio profesional (+4 dBu) generalmente provee entradas y
salidas balanceadas.

*falta diagrama*

## CABLES
Los cables probablemente sean la parte menos costosa de un sistema de sonido,
pero su uso incorrecto, la mala calidad o el mal estado de los mismos pueden determinar
la calidad final de la totalidad del sistema.

Algunos de los problemas más comunes que
pueden producirse por estas causas son: la
aparición de ruidos indeseados en las señales
de audio, perdida de señal por circuitos
abiertos o falsos contactos, o fal as en la
salida del audio por cortocircuitos.

Si bien conceptualmente se considera a
los cables conductores ideales, en la práctica
los cables reales presentan propiedades físicas
y eléctricas como flexibilidad, densidad del
blindaje, durabilidad, resistencia, capacitancia
entre conductores, inductancia entre conductores, etc.

El blindaje es indispensable en cables que transmiten señales de nivel de
micrófono o línea ya que éstas siempre necesitan amplificación de algún tipo, y cualquier
ruido o interferencia no deseada será amplificada junto con la señal. El propósito del
blindaje es desviar hacia la tierra o masa eléctrica los denominados campos
electrostáticos, evitando que se sumen a la señal transportada por el o los conductores
internos del cable. Las descargas electrostáticas pueden ser causadas por motores o
generadores cercanos y por descargas de gases en la iluminación (neón o fluorescente),
entre otros motivos.

*falta imagen*

Aparte del ruido electrostático existe otro tipo de ruido conocido como ruido
electromagnético. Este puede generarse por bobinas en motores eléctricos, los balastros
de los tubos fluorescentes, o en algunas etapas de diversos tipos de dimmers de
iluminación. Este ruido se introduce en el cable por medio del acoplamiento inductivo. El
blindaje normal no excluye este ruido generado por campos electromagnéticos. Esto solo
puede evitarse mediante el uso de líneas balanceadas, y distanciando los cables de las
fuentes mencionadas.

Otro tipo de ruido que puede presentarse en los cables es el causado por los
llamados lazos de tierra (Ground Loops). La única solución apropiada para este tipo de
ruido es la correcta conexión a tierra de la totalidad del sistema de sonido.

*falta diagrama*

### Auto-capacitancia de los cables
Si bien el blindaje tiene la ventaja de evitar el ruido electrostático, posee un aspecto
negativo: aumenta la capacitancia entre los cables conductores de señal. Como el cable
presenta también algún tipo de
resistencia eléctrica, la combinación entre
capacitancia y resistencia constituirá un
filtro pasa-bajos. Mientras más largo sea
el cable y/o mayor sea la capacitancia,
menor será la frecuencia de corte del
filtro. Esto dependerá de la calidad de los
cables, e incidirá más mientras mayores
sean los trayectos que sea necesario
recorrer.

### Cables blindados unipolares y dobles
Los cables blindados de un solo conductor central se utilizan en circuitos no
balanceados. En caso de utilizarlos en circuitos balanceados la señal se desbalaceará. Los
cables blindados con dos conductores centrales se utilizan principalmente en circuitos
balanceados, aunque pueden presentar ventajas cuando se conecta una salida balanceada
a una entrada desbalanceada. No se recomienda utilizar cables dobles cuando se conectan
salidas desbalanceadas a entradas desbalanceadas, porque esto aumentará el efecto
capacitivo entre conductores, produciéndose el efecto de filtro explicado anteriormente. En
cables dobles (balanceados) el blindaje siempre va a tierra y los dos conductores internos
l evan las señales vivas. Más allá de los colores de los cables, lo importante es mantener
un criterio coherente en la conexión de las fichas de ambos lados del cable. Caso
contrario, pueden suceder importantes perdidas o cancelaciones en la señal.

### Cables de parlantes (no blindados)
El blindaje no solo agrega capacitancia a los cables, sino que también aumenta su
peso, tamaño y costo. Si bien en algunos casos es impensable utilizar cables que no sean
blindados (como por ejemplo en cables de micrófono), hay casos en los que es preferible
utilizar cables no blindados. Mientras no exista una fuente de interferencia electrostática
cerca y los niveles de señal sean altos, no habrá riesgo de que exista ruido excesivo.
Particularmente en los cables de parlantes (que provienen desde la salida del
amplificador de potencia) el nivel de señal es tan alto que existe mucho menos riesgo de
que se introduzca ruido externo. Sin embargo, en este caso existen otros problemas que
hay que tener en cuenta.

Aunque la capacitancia incide menos en estos cables, la
inductancia del cable puede presentar un problema serio. Como
hemos visto, un flujo de corriente eléctrica alterna producirá un
campo magnético que será proporcional a el a. Mientras mayores
sean los niveles de corriente, mayores serán los campos
magnéticos, produciendo en consecuencia una mayor perdida en
bajas frecuencias debido a la inductancia del cable. Por este
motivo no es recomendable enrol ar los cables de parlantes,
debido a que esto aumenta su inductancia.

Otro problema que puede repercutir, dependiendo de la __Cables no blindados
impedancia de la carga, es el de la resistencia del cable.

Mientras mayor sea el largo del cable y menor sea su calibre, mayor será la resistencia
total que presentará2. Esto producirá que parte de la potencia que se pretende entregar a
los parlantes sea disipada por el cable. En algunos casos estas perdidas pueden l egar a
ser importantes y disminuir en forma notoria el rendimiento de nuestro sistema.

nota: Esto se puede observar en la fórmula de resistencia eléctrica (R) de un conductor:
```
R =  p ( l / S )
```
en la cual ρ es el coeficiente de resistividad del material, l su longitud y S su área transversal.

## CONECTORES Y FICHAS
Idealmente una ficha debería ser fácil de usar, difícil de desconectar
accidentalmente , y no debería presentar resistencia eléctrica ni permitir que ingresen
interferencias al sistemas de sonido. Dependiendo de la situación, algunos conectores se
acercan más a este ideal que otros. Si el sistema no va a ser movido o recableado a
menudo entonces lo mejor es disminuir la cantidad de conectores al mínimo utilizando
conexiones soldadas. Estas conexiones poseen mínima resistencia, no tienden a
desarrollar resistencia con el paso del tiempo, y difícilmente se desconecten de manera
accidental. De hecho, esto es lo que se usa habitualmente en el cableado de estudios,
donde a las consolas se conectan cables de micrófono y líneas que se dejan fijos. En
sistemas portátiles, es necesario usar otros medios de interconexión.

Cada vez que se inserta un plug y un jack en la ruta de audio se agrega resistencia
al flujo de señal. Incluso si la resistencia del contacto es mínima cuando se arma el
sistema, esta resistencia aumenta con el paso del tiempo, a medida que entra suciedad o
se corroe el material. Cuando los conectores son conectados y desconectados con
frecuencia, esta acción mantiene el material limpio y la resistencia no sube en forma
excesiva. Por este motivo es recomendable disminuir la cantidad de conectores en
sistemas fijos donde la acción de conectar y desconectar no se realiza habitualmente. En
caso de usar conectores en sistemas permanentes, es mejor utilizar conectores bañados
en oro, que poseen baja resistencia inicial y no desarrollan corrosión en el material. A
continuación se detallarán las características más importantes de los conectores de audio
usados para niveles de línea y de micrófono.

Si el conector se utilizará en circuitos no balanceados, solo necesita tener dos
contactos. Ejemplos de esto son los plugs de dos conductores (TS) o las fichas RCA. Los
conectores con tres contactos como el plug TRS y los XLR se usan básicamente para
conexiones balanceadas, pero en determinadas circunstancias pueden usarse para
conexiones desbalanceadas.

¿Como elegir el tipo de conector a utilizar? Generalmente esta decisión está
determinada por el fabricante del equipo, que provee un tipo de conector particular. En
algunos casos, hay más de una opción, y la decisión dependerá de nosotros. Para eso es
útil conocer las ventajas y desventajas de las distintas fichas.

### Conectores Plug
Los plugs de tres conductores son también l amados TRS, siendo las
iniciales de Tip (punta), Ring (anil o), y Sleeve (masa o tierra). Existen
por otra parte plugs de dos conductores l amados TS, faltando en estos
casos el conductor del medio (Ring).

*falta diagrama*

Los plugs se conectan en las fichas denominadas jacks. Son fáciles de soldar,
relativamente baratos y en algunos casos permiten que alternar automáticamente entre
diversos circuitos cuando se conectan. Sin embargo hay que tener en
cuenta algunas precauciones.

En una línea balanceada, la punta (Tip) l eva la señal de audio
principal, el anil o (Ring) l eva la señal invertida de fase y la malla
(Sleeve) va conectada a masa. Si un plug de este tipo se conecta a un
jack no balanceado (tip/sleeve) la línea se desbalanceará, pero la
Plug y Jack polaridad se mantendrá correcta.

Uno de los problemas que presentan los plugs es que pueden producir ruido cuando
se conectan a un sistema de sonido en funcionamiento o cuando son manipulados. Otras
desventajas de los plugs es que no tienen ningún tipo de mecanismo de seguridad, lo que
significa que pueden desconectarse por accidente. Además la mayoría de las conexiones
plug-jack presentan alta resistencia de contacto, lo que puede producir ruido o pérdida de
potencia si son utilizados en circuitos que incluyan parlantes.
Al plug TRS a veces se le l ama “plug estéreo” porque este es el uso que tiene en
los auriculares estéreo. En este caso el circuito es desbalanceado y se conecta el canal
izquierdo a la punta (T), el derecho al anil o (R) y la
masa común es el Sleeve (S).

Existe otro tipo de conexión llamada inserción
(Insert) que se utiliza principalmente para conectar
efectos o procesadores de audio externos en las
consolas que permiten este tipo de conexión. La
inserción permite ubicar en el mismo conector TRS una
salida (envío de la señal al procesador o Send) y una
entrada (retorno de la señal o Return) desbalanceadas
Cable de Inserción
para ahorrar espacio. Las desventajas que presenta este
tipo de combinación de entrada-salida son:

- a. la necesidad de cables especiales (no estándar);
- b. la posibilidad de que, si se conecta mal el cable, pueda dañarse alguno de los
dispositivos conectados; y
- c. la posibilidad de oscilación causada por diafonía (Crosstalk).

El plug TRS estándar o el TS tiene un diámetro de 1/4” (6.25 mm). Existen algunos
conectores similares más chicos, como los mini-plugs u otros, que generalmente son de
uso hogareño o no profesional.

Hay algunas consideraciones a tener en cuenta con estos conectores. Una es
asegurarse que el plug quede bien fijo en el jack cuando se conecta. Otra es la de no
tocar los contactos metálicos de la ficha con los dedos, ya que esto puede generar
corrosión en el material a mediano plazo.

### Conectores XLR
El conector XLR de tres contactos fue originalmente introducido por la
empresa Cannon (de hecho es habitual hacer referencia a estas fichas
directamente con este nombre). Esta es una de las fichas más utilizadas
en audio profesional, y para algunas aplicaciones (como la conexión de
micrófonos) es prácticamente el estándar.

Consiste en la ficha (macho o hembra) que posee tres conductores. El conductor 1
va a masa, mientras que en las señales balanceadas el conductor 2 l eva la señal y el
conductor 3 la misma señal invertida de polaridad.

Una de las ventajas principales que tiene este tipo de ficha es que cuando se
conecta, queda trabada. No se saldrá por accidente a menos que presione el pestil o que
posee la ficha (hembra). Además al conectarla el primer conductor que hace contacto es
el 1 (masa), l evando posibles ruidos de masa o descargas electrostáticas a tierra antes de
que se conecte el circuito de audio y puedan ser transmitidos por el sistema (como puede
suceder cuando se conectan plugs). Por otra parte, la superficie de contacto es grande y
esto hace que presente baja resistencia. La desventaja principal de estos conectores es su
precio más elevado en comparación con otros, y las precauciones necesarias para
soldarlos a los cables.

### Conectores RCA
Desarrol ados por la empresa RCA para uso principal en equipos
de radio y televisión, también se los conoce como Phono por
utilizarse originariamente en las cápsulas fonocaptoras de
tocadiscos. Con el pasar del tiempo, este conector se transformó
en un estándar para la mayoría del equipamiento de audio
hogareño con niveles de línea (también se usa para otro tipo de conexiones como la
SPDIF de audio digital, y en algunos cables de video). Este tipo de ficha se usa en algunas
aplicaciones profesionales porque es barato y permite conectar muchos conectores en un
área relativamente pequeña.

Como son un poco más difíciles de soldar que otras fichas a veces es preferible
comprar cables ya armados. Sin embargo, existe una gama variada de calidades en los
cables armados, a la que hay que prestar atención para no correr riesgos que puedan
comprometer la confiabilidad de las conexiones.

Una desventaja que pueden presentar estas fichas es que al tener un diámetro
chico puedan presentar una capacitancia alta. Otra de las desventajas posibles es la
tendencia a desarrol ar alta resistencia en la conexión. Esto es así particularmente en
equipos de audio Consumer, los que una vez instalados pueden quedar así por años,
dando lugar a la formación de óxido que degradará la calidad de audio. Para evitar este
problema pueden utilizarse conectores bañados en oro. Otra recomendación es girar
periódicamente las fichas en los conectores realizando una limpieza del material.

---
> Para el presente apunte fueron seleccionados y traducidos fragmentos del libro :
> Davis, G. y Jones, R. (1989), The Sound Reinforcement Handbook. Milwaukee: Hal
> Leonard Corporation.

Apunte realizado por Martín Matus y Esteban Calcagno para uso interno exclusivo de la
materia Taller de Instrumental y Equipos I de la Carrera de Composición con Medios
Electroacústicos de la Universidad Nacional de Quilmes.


