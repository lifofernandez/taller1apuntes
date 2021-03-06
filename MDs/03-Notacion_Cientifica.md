Notación Científica – Múltiplos y Submúltiplos

Notación científica

Introducción:
Supongamos que deseamos resolver, el siguiente ejercicio:

V = 10 Volts
R= 10 Ω
I = ?

Como hemos estudiado, para poder obtener la corriente en esta sencilla cuenta, se debe aplicar la Ley de Ohm que dice que:

I = V/R

Fácilmente la resolución de este ejercicio sería:

I = 10 Volts / 10 Ω = 1 Amper

Hasta aquí todo bien, pero que sucede en el siguiente caso:

V = 0.5 V
R = 100.000 Ω
I = ?

En ese caso, nuevamente por Ley de Ohm, la respuesta sería:

I = 0.5 V / 100.000 Ω = 0.000005 A

Se observa que la corriente aparece como un número bastante pequeño, con muchos ceros después de la coma. Lo mismo pasa con la resistencia, que aparece como un número muy grande y con muchos ceros.
La idea de esto es observar que las magnitudes, especialmente en electrónica, aparecen casi siempre con valores muy pequeños y muy grandes. Para resolver este problema, se utiliza lo que se llama “Notación Científica”.
Básicamente la notación científica nos da la posibilidad de expresar un número muy pequeño o muy grande, en número que se pueden reconocer a simple vista.
Esto simplifica también las operaciones entre números de tales características.

Potencias de Diez:

La Notación científica se basa en las características que poseen las potencias de 10.
Veamos la siguiente tabla:

Esta tabla muestra las características básicas de las potencias de 10, y una forma fácil de reducir el número de ceros.

NOTA:
CUALQUIER NÚMERO ELEVADO A “0”, EL RESULTADO SIEMPRE ES 1.

Pero analicemos un poco lo que nos muestra esta tabla.
En el caso del número 1, este no posee ningún 0, por lo tanto se representa como 10 a la 0. En el caso de 1000, por ejemplo, se representa como 10 a la 3, por que tiene 3 ceros.

Con las magnitudes menores a 1, la lógica es la misma, solo que también se cuenta el 0
a la izquierda de la coma, además que el exponente se representa como número
negativo.
Entonces un número como 0.1, en este caso se representa como 10 a la -1.
En realidad la forma correcta de nombrar estos números es decir, por ejemplo con una magnitud de 0.1:

1 por 10 a la menos 1.

Una forma rápida para determinar cual es la potencia de 10 que representa a un número es la que muestra la siguiente tabla:

Método que se basa en contar la cantidad de “lugares” hacia la derecha (números mayores a 1) y hacia la izquierda (números menores a 1), hasta llegar al punto decimal.
Así con 10.000, se cuenta hacia la derecha 4 lugares hasta que se llega al ultimo digito, pero empezando después del primer dígito.
Con 0.00001, se cuenta empezando del último dígito, 5 lugares hasta el punto.
Este último método es el más utilizado debido a que permite hacer la notación de cualquier número. Por lo tanto usaremos este.
Por ejemplo el número:
12.340.000

Puede representarse de muchas maneras. En este caso el método de contar la cantidad de ceros, solo servirá hasta un determinado lugar:

12.340.000 = 12.340 por 10 a la 3 = 1234 por 10 a la 4

Cuando se hace el cálculo en la calculadora, se debe recordar que la multiplicación de un número por una exponente en base 10 es una tecla especial, que esta justamente simbolizada como 10 a la x. De lo contrario las cuentas no darán bien. Si se desea utilizar la tecla EXP, se debe quitar la base 10, y directamente elevar el número al exponente al cual esta el 10.

Entonces el ejemplo anterior sería:

12.340 a la 3 = 12.340.000

En la calculadora: 12340 EXP 3

De esta manera comenzamos a reducir la forma de representar los números grandes utilizando solamente el exponente. Otros ejemplo:

45.678 = 45,678 a la 3 (45,678 EXP 3)
45.678 = 456,78 a la 2 (456,78 EXP 2)
45.678 = 4.567,8 a la 1 (4.567,8 EXP 1)

Nótese la diferencia entre el punto y la coma. El punto separa los dígitos de a tres para lograr una imagen visual más fácil de entender. Puede o no estar presente en la notación. La coma representa los decimales, y debe estar siempre que se necesite.

NOTA:
EN LA CALCULADORA SE UTILIZA EL PUNTO (.) COMO COMA (,)

Más ejemplos:
En este caso números menores a 1 (exponente negativo)

0.00345 = 345 a la -5 (345 EXP 5 +/- (para poner 5 negativo))
0.00345 = 34,5 a la -4 (34,5 EXP 4 +/- (para poner 4 negativo))
0.00345 = 3,45 a la -3 (3,45 EXP 3 +/- (para poner 3 negativo))

0.000000023 = 23 a la -9 (23 EXP 9 +/- (para poner 9 negativo))
0.000000023 = 2,3 a la -8 (2,3 EXP 8 +/- (para poner 8 negativo))
0.000000023 = 230 a la -10 (230 EXP 10 +/- (para poner 10 negativo))

Como se observa en este último, en un número menor que 1 con decimales, se puede agregar decimales a la derecha, para representarlo.

0.0000000230

Ese último 0 no afecta al valor, y nos da la posibilidad de crear otra representación y decir que este número también puede ser:

230 a la -10.

Múltiplos y Submúltiplos

Para seguir facilitando el manejo con números muy pequeños y muy grandes, también se utiliza lo que se denomina múltiplos y submúltiplos, que no son más que
representaciones de las potencias que vimos en la notación científica. Presentaremos algunos de los múltiplos y submúltiplos que más utilizaremos y luego daremos cuenta de todos:

5.000.000 = 5 a la 6 = 5 M se dice 5 Mega… Por ejemplo 5 M Volts
3.000 = 3 a la 3 = 3 K se dice 3 Kilo… Por ejemplo 3 K Ohms
0.015 = 15 a la -3 = 15 m se dice 15 mili… Por ejemplo 15 m Amper
0.000023 = 23 a la -6 = 23 u se dice 23 micro… Por ejemplo 23 u Volts

Todos los múltiplos y submúltiplos del sistema internacional serían:

