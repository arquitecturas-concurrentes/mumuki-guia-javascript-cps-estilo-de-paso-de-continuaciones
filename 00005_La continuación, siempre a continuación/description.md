En oposición al estilo directo, caracterizado por la obtención de resultados mediante retornos, surge así el _estilo de paso de continuaciones_ (*CPS*, por sus siglas en inglés). 

Es decir, cuando tenemos una función que toma una continuación y efectivamente colocamos todo el código que opera con el resultado dentro de la misma, tenemos una función CPS.

El CPS es especial porque es fácil introducirlo, pero imposible salir de él, al menos no sin introducir bugs y potenciales problemas en el sistema.


> Veamos un ejemplo: si ahora queremos implementar una función que incrementa el doble de un número, usando nuestro `successor` CPS, podríamos escribir el código que está en el editor. Pero no va a funcionar :sob:, ¡corregilo!




