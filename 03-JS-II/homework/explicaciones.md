# Expicación de conceptos

## for

Imagina que tienes que hacer una tarea que se repite muchas veces, Como subir un escalón en una escalera, haces el mismo movimiento con las piernas una y otra vez. Bueno, para que un computador haga una tarea muchas veces se inventó algo llamado 'los ciclos'. Una forma de crear un ciclo es utilizar la sentencia ̈́ 'for'. Para que un 'for' funcione se le da un rango de números como del 1 a 15, 5 a 10 y así de la forma que tú quieras. Resulta que for trabaja contando, así como contamos todos: 1,2,3,4,5... entonces le das el número por donde tiene que empezar, por ejemplo:1. Cómo tiene que contar, por ejemplo: de 3 en 3. Y por cuanto tiene que contar, por ejemplo: cuenta mientras no hayas superado el 8.

Un ejemplo que reúne todo esto sería:

> for(var i= 1; i<=8; i=i+3){ }

'var i=1' es la forma como le decimos que empiece por el uno.'i<=8' es decirle que cuente mientras no hayas superado el ocho. 'i=i+3' es que cuente de 3 en 3.

Ahora solo tienes que poner entre las llaves la acción que quieres hacer. Un ejemplo suponiendo que programaste tus piernas para subir 20 escalones de uno en uno, sería así:

> for(var i= 0; i<20; i= i+1){ subirEscalon(misPiernas) }

## || && !

En programación estos son operadores lógicos. Todo el tiempo usamos operadores lógicos mientras hablamos entonces lo podrás entender con la definición y algunos ejemplos.

#### ||
Esto significa _o_ sí la letra _o_ y se usa para indicar que si unes varias afirmaciones con _o_ osea ||, creando una afirmación más grande, con que solo una afirmación sea verdadera toda la afirmación será verdadera la afirmación grande.



Ejemplo: el arroz es blanco _o_ el arroz es pequeño


### En JS sería así:
> if(arrozEsBlanco || arrozEsPequeno )

si el arroz es blanco, automáticamente todo lo que está entre paréntesis es verdadero.


### &&
Esto significa _y_ sí la letra _y_ y se usa para indicar que si unes varias afirmaciones con _y_ osea &&, creando una afirmación más grande, tienen que ser todas verdaderas para que la afirmación grande afirmación grande sea verdadera.


Utilizando el ejemplo anterior: el arroz es blanco _y_ el arroz es pequeño

#### En JS sería así:
> if(arrozEsBlanco || arrozEsPequeno )

 Todo lo que está entre paréntesis es verdadero si las dos afirmaciones son ciertas. Recuerda que puede ser más de dos afirmaciones


 ### !

 Esto simplemente significa _no_ y lo pones antes de una afirmación para negarla.

 Ejemplo:
 > !(arrozEsBlanco || arrozEsPequeno)

 Suponga que arrozEsBlanco es verdadero, entonces todo lo que está entre paréntesis es verdadero. Como le pusimos la negación '_!_' quedaría falso.
