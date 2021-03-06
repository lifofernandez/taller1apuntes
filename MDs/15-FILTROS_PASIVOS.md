# Filtros Pasivos
## Introducción

Cualquier combinación de elementos pasivos (que no necesitan alimentación externa) R, L o C, o sea resistencias, bobinas y capacitores, y/o activos (que necesitan alimentación externa), como los transistores o amplificadores operacionales, diseñados
para seleccionar o rechazar una banda de frecuencias de una señal que atraviesa el circuito que estos disponen, se considera un filtro. En este caso el filtrado se produce de manera eléctrica y no acústica.

En los sistemas de comunicación los filtros se utilizan para dejar pasar aquellas bandas
de frecuencias que contengan la información deseada, y rechazar las bandas de
frecuencias no deseadas. Por ejemplo en radio o telefonía se asignan determinadas bandas de frecuencias para la comunicación, lo que obliga al diseño de filtros que solo
dejen pasar esa banda.

Entonces como vimos, los filtros pueden estar diseñados con componentes pasivos y activos, y por lo tanto existe una clasificación que agrupa a los filtros de esta manera:
- Filtros pasivos: son los que se componen de combinaciones en serie o paralelo de los elementos R, L o C.
- Filtros activos: Son los que utilizan dispositivos activos tales como transistores y amplificadores operacionales en combinación con elementos R, L o C.

En esta primera parte nos centraremos en el estudio de los filtros pasivos, y, en otra etapa, cuando estudiemos transistores y operacionales, pasaremos a los filtros activos.

## Configuraciones fundamentales
En general los filtros, activos o pasivos, se dividen en cuatro grandes y amplias categorías básicas:
- Filtros pasa bajos
- Filtros pasa altos
- Filtros pasa bandas
- Filtros rechaza bandas

*falta diagrama*

Como se ve en las figuras para cada tipo de filtro existen frecuencias críticas, definidas por las bandas de paso y las bandas de atenuación, también llamadas bandas de rechazo.
Cualquier señal que atraviese el filtro y sus frecuencias se encuentren dentro de la banda de paso, cruzará a la siguiente etapa con al menos al 70,7% del voltaje máximo.

En este caso nos centraremos solamente en los filtros pasivos RC, en sus
configuraciones pasa bajo y pasa alto.

## Filtro R-C pasa bajos
*falta diagrama*

Este diseño sencillo puede utilizarse tanto como un filtro pasa bajos como un pasa altos.
Si tomamos como salida la caída en el capacitor, tenemos un filtro pasa-bajos, si intercambiamos las posiciones entre el capacitor y el resistor, y tomamos la salida en la resistencia, tenemos un pasa alto.
Este circuito, en configuración pasa bajo, se comporta de manera que cuando medimos
sobre el capacitor habrá un nivel de tensión alto para las frecuencias bajas, y un nivel cada vez más bajo para frecuencias altas, por supuesto que se encuentren entre los valores críticos.

Analizamos el circuito para extremos de frecuencia.

Si la **frecuencia es igual 0Hz** entonces la reactancia capacitiva estará dada por:
```
Xc = ( 1 / 2PIfC ) = Inf. Ohms
```
Y será infinita, lo que significa que la señal estará al máximo de amplitud, ya que **el circuito se comportará como un circuito abierto**:

*falta diagrama*

La señal de entrada, saldrá directamente a la salida.

Si en cambio la **frecuencia es muy alta**, el resultado de la reactancia estará dado por:
```
Xc = ( 1 / 2PIfC ) = 0 Ohms
```
La reactancia capacitiva será 0, y por lo tanto no dejará pasar la señal por que se **comportaría como un corto circuito**:

*falta diagrama*

Donde la salida será igual a 0 volts.

Si hacemos una gráfica de la magnitud de la caída de tensión en función de la frecuencia
que dará la siguiente curva:

*falta diagrama*

El tema ahora es obtener la frecuencia a la que ocurre la transición, o sea determinar a
que frecuencia comienza a atenuar el filtro, la división entre la banda de paso y la banda de atenuación, lo que se denomina Frecuencia de Corte, Fc.

Es valido aclarar que para los filtros se utiliza muchas veces una gráfica normalizada, en lugar de la grafica de tensión de salida sobre frecuencia.

Nota: La normalización es un proceso por el medio del cual cantidades tales como voltaje, corriente o impedancia se dividen entre una cantidad con la misma unidad de medición para establecer un nivel adimensional de un valor o intervalos específicos.

En este caso se divide la señal de salida por la señal de entrada, de esta manera el valor nunca supera 1, haciendo más fácil su lectura.


*falta diagrama*

La frecuencia de corte se define en el valor de ganancia de 0.707.

En cualquiera de las frecuencias intermedias el voltaje de salida puede determinarse mediante la regla del divisor de tensión que aprendimos en clases anteriores, pero esta
vez solo calculando la ganancia:

La magnitud de la razón Voltaje de Salida (Vo) y el Voltake de Entrada (Vi), o sea la ganancia, estará dada por:
```
Av = ( Vo / Vi ) = Xc / sqr( R^ + Xc^)
```
La Frecuencia de Corte se da en el caso especial en que Xc es igual a R:
```
Xc = 1 / 2 . PI . fc . C = R
fc = 1 / 2 . PI . R . C
```
Para todo filtro Pasa Bajos, la aplicación de cualquier frecuencia menor a fc da por resultado un voltaje de salida que será al menos el 70.7% de la tensión de entrada. Para
cualquier frecuencia que se encuentre por encima de la fc, la salida será menor al 70.7%
de la señal aplicada.

## Filtro R-C Pasa Alto

Como dijimos en un principio, podemos crear un filtro R-C pasa alto solamente invirtiendo los elementos, y tomando como Vo la caída en R:

*falta diagrama*

A frecuencias muy altas la reactancia del capacitor es muy pequeña y se termina convirtiendo en un cortocircuito, por lo que V0 = Vi:

Con f = 0, la reactancia del capacitor es muy alta, por lo tanto se convierte en un circuito abierto, y Vo = 0:

*falta diagrama*


La gráfica de un filtro pasa alto se verá de la siguiente manera:

*falta diagrama*


La frecuencia debe aumentar hasta por lo menos la frecuencia de corte para poder pasar
con por lo menos el %70.7 del total de la señal.
En frecuencias intermedias el voltaje de salida se calcula igualmente con la fórmula del
divisor resistivo de tensión, aunque en este caso nos referimos a la resistencia y no al capacitor.
Como vimos, debemos tener en cuenta la ganancia del mismo para normalizar el
gráfico:

*falta diagrama*

La magnitud de esta razón se calcula como:
```
Av = ( Vo / Vi ) = R / sqr( R^ + Xc^)
```
Cuando Xc = R tenemos la frecuencia de corte del filtro, y se puede calcular de la siguiente manera:
```
Xc = 1 / 2 . PI . fc . C = R
fc = 1 / 2 . PI . R . C
```
