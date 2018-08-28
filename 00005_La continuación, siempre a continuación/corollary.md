He aquí el problema: `incrementarDoble` debe retornar `i1`, ¡pero no puede hacerlo, porque no hay garantías de cuando se va a ejecutar la continuación, ni cuantas veces!

Por ello, la única alternativa válida (sin basarse en los detalles de implementación de successor, claro), es convertir a `incrementarDoble` en CPS.

Moraleja: una vez que introducimos CPS, su uso sólo puede extenderse.
