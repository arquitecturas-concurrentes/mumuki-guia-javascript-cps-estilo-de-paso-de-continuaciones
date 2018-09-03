Hasta acá nada extraño. Hagamos ahora un salto conceptual: otra forma posible de escribir este código, es que el resultado se obtenga a partir de un _callback_.

```javascript
function successor(x, callback) {
 callback(x + 1);
}
```

> ¡Momento! ¿Cómo se usa esto? ¿Te animás a descubrirlo? 
> 
> Probá usar `successor` de estas formas:  
>
> ```javascript
> ム successor(30)
> ム successor(30, (r) => r + 1)
> ム successor(30, (r) => { console.log(r + 1) } )
> ```
>
> ¿Cuál de ellas anda y por qué?