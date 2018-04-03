Hasta acá nada extraño. Hagamos ahora un salto conceptual: otra forma posible de escribir este código, es que el resultado se obtenga a partir de un _callback_.

```javascript
function succesor(x, callback) {
 callback(x + 1);
}
```

> ¡Momento! ¿Cómo se usa ésto? ¿Te animás a descubrirlo? 
> 
> Probá en la consola para calcular y mostrar el resultado