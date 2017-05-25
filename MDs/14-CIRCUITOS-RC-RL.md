# Circuitos Resistivos Capasitivos y Resistivos Inductivos en Corriente Alterna

## Circuitos R-C (Resistivos Capasitivos) en CA
Imaginemos que tenemos el siguiente circuito compuesto por una resistencia y un
capacitor:

*falta diagrama*

Para obtener el valor de la corriente que circula por este circuito, no solo se tiene que
tener en cuenta la resistencia de R, sino también la reactancia de Xc, ya que esta afecta
directamente a la corriente, dependiendo de la frecuencia. El valor resistivo de una
resistencia no es afectada por la frecuencia, por lo tanto se lo considera un
componente pasivo, pero el valor de reactancia de un capacitor si se ve afectado por la
frecuencia por lo tanto se lo considera un componente activo.

Debido a que ambas son resistencias que se aplica al flujo de corriente se debe tener
en cuenta el aporte de ambos componentes. A esta unión se la denominará
impedancia, que no es ni más ni menos que la suma de la oposición a la corriente de
las componentes pasivas y reactivas de un circuito. La impedancia se simboliza con una
Z.
Entonces de este modo la corriente se podrá calcular como I = V/Z.

Para entender esto aun mejor, pensemos en que la tensión total aplicada al circuito se
divide en las caídas de tensión en R y en Xc.
```
VR  = R.I
VXc = Xc.I
```
La suma de estas dos se debe hacer en forma vectorial ya que la reactancia capacitiva
además de un modulo posee un ángulo de desarrollo. Por lo tanto el diagrama
vectorial de un circuito RC sería igual al siguiente:

*falta diagrama*

Vxc tendrá un retraso de 90º con respecto a Vr, por que Xc se comporta de esta
manera. De aquí podemos deducir el triangulo de impedancias:

*falta diagrama*

Desde donde podemos obtener Z.
Gracias al teorema de Pitágoras podemos obtener la magnitud y la fase de Z de la siguiente manera:

##### Fase de la Impedancia 
###### Angulo Tangente = opuesto / adyasente
```
tan = Xc / R
```
##### Magnitud de la Impedancia
###### Hipotenusa = Raiz Cuadrada ( opuesto^ + adyasente^ )
```
Z = sqr( R^ + Xc^ )
```


## Circuitos R-L (Resistivos Inductivos) en CA

Tenemos un circuito R-L:

Para obtener la tensión necesitamos el diagrama vectorial igual que antes:

*falta diagrama*

En este caso, por todo lo que vimos antes, VL adelanta a VR en 90º. De acá sacamos el
triangulo de impedancias, para poder calcular Z:

*falta diagrama*

Y nuevamente por Pitágoras obtenemos la magnitud y el ángulo de Z:

##### Fase de la Impedancia 
###### Angulo Tangente = opuesto / adyasente
```
tan = Xl / R
```
##### Magnitud de la Impedancia
###### Hipotenusa = Raiz Cuadrada ( opuesto^ + adyasente^ )
```
Z = sqr( R^ + Xl^ )
```
