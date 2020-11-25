# Proceso de solución de problemas

1. Entender muy bien lo que nos están pidiendo. Utilizar analogías, hacer gráficos.
2. Proponer una solución. Pueden buscar en Internet, dibujar. Diagramas de flujo.
3. Implementarlo en JavaScript.
4. Validarlo (prueba de escritorio).
5. Refactor (opcional). Mejorar el código para hacerlo más legible.


La lámpara no funciona
Si no está enchufada (if …)
   Enchufar la lámpara
De lo contrario (else )
    Si está quemada la ampolleta (if)
        Cambiar la ampolleta
     De lo contrario (else)
         Comprar lámpara nueva

Variables <- booleana
Arreglos
Objetos <- 

```javascript
var pedido1 = {
  precio: 12,
  bonus: 3,
  ingredientes: [1, 2, 3]
}

var pedido2 = {
  precio: 10,
  bonus: 1,
  ingredientes: [3, 3, 3, 3]
}

var pedidos = [pedido1, pedido2]

```

```javascript
var lampara = {
  enchufada: true,
  bombilla: true
}

if (!lampara.enchufada) {
  lampara.enchufada = true
} else if (!lampara.bombilla) {
  lampara.bombilla = true
} else {
  lampara = {
	   enchufada: true
     bombilla: true
  }
}
```
