¡Momento! ¿Qué fue eso? Si bien puede verse un poco perturbador al principio, este código es totalmente equivalente al anterior: cuando se aplica la función `successor`, calcula su siguiente, y se lo pasa al callback, que opera con el mismo normalmente.

Es decir, _funcionalmente_ hace lo mismo, pero en lugar de expresar el resultado como un retorno, lo recibimos como el parámetro de una función que *no devuelve nada*. A esta función la llamaremos _continuación_ porque... ¡es lo que que se ejecuta a continuación! :stuck_out_tongue:. ¡Renombremosla!

```javascript
function successor(x, continuation) {
  continuation(x + 1);
}
```

> ¡Cuidado! Como ya intuimos en el ejercio anterior, esta versión de la función `successor` tiene sus problemas. 






