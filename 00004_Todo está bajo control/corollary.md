Acá estamos capturando el resultado de `successor` a través de la continuación, guardándolo en una variable `x`, asumiendo que el código se ejecutará inmediatamente y que estará disponible cuando hagamos `console.log`.

Pero si es realmente successor quien tiene control sobre cuándo y cómo se ejecuta la continuación, no podemos garantizar esto dado que no sabemos cuándo se va a ejecutar la continuación.

¿Esto significa que el código anterior no funciona? No, pero tenemos que entender que estamos rompiendo el modelo de continuación, al no permitir que sea la función successor la que determine cuándo y cómo seguir. Y eso puede ser una fuente de bugs :bug:.