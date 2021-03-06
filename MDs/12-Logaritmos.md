# Logaritmos
## Introducción
Los logaritmos son una de las herramientas más utilizadas a la hora de trabajar
con valores de ganancia o atenuación de las señales eléctricas que recorren la
cadena de audio. Estos son la base para el entendimiento de los decibeles.
Entender como funcionan los logaritmos, es entender como funcionan los
decibeles, y poder así adueñarse de una herramienta muy importante para
entender como se comportan las señales eléctricas.
Como nota aparte, cabe aclarar que la forma en que percibimos sonidos con
nuestro sistema auditivo, es logarítmica. Por lo tanto al usar logaritmos solo
estamos adecuándonos a nuestra forma de percibir.

### La función logarítmica:

Tengamos en cuenta la siguiente función matemática:
```
N = ( B ) ^ X
```
Se trata ni más ni menos de una función exponencial.

Esta función establece que el número N es igual a una base b elevada a un
número x.
Por ejemplo:
```
 100 = 10 ^ 2
  27 =  3 ^ 3
54.6 =  e ^ 4 ( donde e = 2.7183 )
```
Ahora supongamos que queremos saber cual es el exponente x al cual hay que
elevar la base b para obtener el número N.
```
1200 = ( 10 ) ^ X
```
Para eso se utilizan los logaritmos, ya que el logaritmo, en base 10, de 1200
nos da ese valor de X:
```
X = log10( 1200 ) = 3.079
```

O sea, que si elevamos 10, que es la base, a 3,079, obtendremos 1200.
En la calculadora científica existe directamente una función que realiza el
logaritmo en base 10, y viceversa. En general se la reconoce por que se indica
como LOG.
Si bien no existe ninguna restricción para realizar el logaritmo en cualquier
base, en general nosotros utilizaremos la base 10, ya que es la base en la que
se trabaja con los decibeles.

Entonces en general podemos decir:
```
Si N = ( B ) ^ X, entoces X = logB( N )
```
Esta es la formula general de los algoritmos, para cualquier tipo de base.
Entonces esa es la relación que se debe tener en cuenta.
La grafica, mediante el sistema de ejes cartesianos, que produce la función
logarítmica sería como la siguiente, siempre dependiendo de las variables que
se ponen en juego:

*falta dibujo*

A partir de la gráfica de la función logarítmica podemos hablar de las diferentes
propiedades que tiene esta función:

- El logaritmo común o natural (base 10) del número 1 es siempre 0, ya
que 10 a la 0 es 1.
```
log10( 1 ) = 0 
```
- El logaritmo natural de cualquier número que se encuentra entre 0 y 1 es
siempre negativo.
```
log10( 1 /  2 ) =  log10( .5 ) = -0.3 
log10( 1 / 10 ) =  log10( .1 ) = -1 
```
- El logaritmo del producto de dos números es la suma de los logaritmos
de los números.
```
log10( a . b ) =  log10( a ) + log10( b ) 
```
- El logaritmo del cociente (división) de dos números es el logaritmo del
numerador menos el logaritmo del denominador.
```
log10( a / b ) =  log10( a ) - log10( b ) 
```
- El logaritmo de un número elevado a una potencia es igual al producto
entre la potencia por el logaritmo del número.
```
log10( a ) ^ N =  N log10( a ) 
```
Siguiendo un poco más con el análisis de la gráfica, quizás el comportamiento
más interesante que podemos encontrar es que la función logarítmica es
compresora. Peor que significa esto?
Que sea compresora significa que al aumentar a valores de x (eje x de la
gráfica) más altos, los valores de y aumentan también, pero más lentamente.
Esta es quizás la propiedad que define el uso de los logaritmos en el análisis
de las señales de audio.

Ahora presentaremos algunos ejemplos de logaritmos naturales:
```
Log 100  =  2 10 elevado a la 2  = 100
Log 10   =  1 10 elevado a la 1  = 10
Log 1    =  0 10 elevado a la 0  = 1
Log 0.1  = -1 10 elevado a la -1 = 0.1
Log 0.01 = -2 10 elevado a la -2 = 0.01
```
Log de x tendiendo a 0 (que no es lo mismo que x = 0) es -∞ (un numero
infinito pero negativo). De este hecho particular se desprende que en una
consola, el fader de cada canal posea como mínimo valor, el valor de -∞.
Si, el fader de una consola se comporta de manera logarítmica.

---
Apunte realizado por Esteban Calcagno y Martín Matus para uso interno exclusivo de la materia Taller
de Instrumental y Equipos I de la Carrera de Composición con Medios Electroacústicos de la Universidad Nacional de Quilmes.

