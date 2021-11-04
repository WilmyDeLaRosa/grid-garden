# grid-garden
Niveles del juego GRID GARDEN

- ¡Bienvenido a Grid Garden, donde escribirás tu código CSS para cultivar tu jardín de zanahorias! Riega solo las áreas que tienen zanahorias usando la propiedad grid-column-start.
- Oh oh, parece que hay malas hierbas creciendo en la esquina de tu jardín. Usa grid-column-start para envenenarlas. Fíjate en que las malas hierbas comienzan en el quinto borde vertical de la cuadrícula.
- Cuando grid-column-start se usa solo, la expansión por defecto del elemento en la cuadrícula será de exactamente una columna. No obstante, puedes extender el elemento varias columnas añadiendo la propiedad grid-column-end.
- Al emparejar grid-column-start y grid-column-end, podrías asumir que el valor final tiene que ser mayor que el valor inicial. ¡Pero no es el caso!
- Si prefieres contar las líneas de la cuadrícula comenzando por la derecha, puedes dar a grid-column-start y grid-column-end valores negativos. Por ejemplo, puedes establecerlos a -1 para indicar la primera línea comenzando por la derecha.
- Ahora intenta establecer grid-column-start a un valor negativo.
- En lugar de definir un elemento en la cuadrícula basado en la posicion inicial y final, puedes definirlo basado en la longitud de columnas deseada usando la palabra clave span. Ten presente que span solo funciona con valores positivos.
- Intenta usar grid-column-end con la palabra clave span de nuevo para regar tus zanahorias.
- También puedes usar la palabra clave span con grid-column-start para establecer la anchura del elemento en relación a la posición final.
- Escribir ambos grid-column-start y grid-column-end cada vez puede resultar cansado. Afortunadamente, grid-column es una propiedad abreviada que acepta ambos valores a la vez, separados por una barra oblicua.
- Intenta usar grid-column para regar las zanahorias. La palabra clave span también funciona con esta propiedad abreviada así que ¡dale una oportunidad!
- Una de las cosas que diferencia las cuadrículas de CSS de flexbox es que puedes posicionar los elementos fácilmente en 2 dimensiones: columnas y filas. grid-row-start funciona de manera semejante a grid-column-start pero a lo largo del eje vertical.
- Ahora dale una oportunidad a la propiedad abreviada grid-row.
- Usa grid-column y grid-row a la vez para establecer una posición en ambas dimensiones.
- También puedes usar grid-column y grid-row juntos para abarcar áreas más extensas en la cuadrícula. ¡Inténtalo!
- Si escribir grid-column y grid-row se te hace demasiado pesado, aquí tienes otra propiedad abreviada. grid-area admite cuatro valores separados por barras oblicuas: grid-row-start, grid-column-start, grid-row-end, seguido de grid-column-end.
- ¿Y qué me dices de múltiples elementos? Puedes superponerlos sin problema. Usa grid-area para definir una segunda área que cubra todas las zanahorias que están sin regar.
- Si los elementos de la cuadrícula no se sitúan explícitamente con grid-area, grid-column, grid-row, etc., se sitúan automáticamente de acuerdo al orden en el código fuente. Puedes sobrescribir esto usando la propiedad order, que es una de las ventajas de la cuadrícula frente al diseño basado en tablas.

Por defecto, el valor de order de todos los elementos es igual a 0, pero puede ser establecido a cualquier valor positivo o negativo, de manera similar a z-index.
- Ahora el veneno y el agua se alternan, a pesar de que todas las malas hierbas están al comienzo de tu jardín. Cambia el valor de order de los venenos para solucionar esto.
- Hasta este momento, has tenido un jardín formado por cinco columnas, cada una ocupando el 20% de la anchura total, y cinco filas, cada una ocupando el 20% de la altura total.
- Especificar un puñado de columnas con la misma anchura puede ser aburrido. Afortunadamente hay una función repeat que te ayudará con eso.
- grid-template-columns no acepta solo valores porcentuales, sino también otras unidades como pixels y ems. Incluso puedes mezclar diferentes unidades a la vez.
- CSS Grid también introduce una nueva medida, la fracción fr. Cada unidad fr asigna una porción del espacio disponible. Por ejemplo, si dos elementos están establecidos a 1fr y 3fr respectivamente el espacio se divide en 4 porciones iguales; el primer elemento ocupa 1/4 del espacio y el segundo elemento los 3/4 restantes.
- Cuando algunas columnas son establecidas en píxeles, porcentajes o ems, cualquier otra columna establecida con fr dividirá el espacio restante.
- Ahora hay una columna de malas hierbas de 75 píxeles en el lado izquierdo del jardín. En 3/5 del espacio restante crecen zanahorias, mientras que los 2/5 restantes han sido invadidos por malas hierbas.
- grid-template-rows funciona exactamente igual que grid-template-columns.
- grid-template es una propiedad abreviada que combina grid-template-rows y grid-template-columns.
- Tu jardín tiene una pinta genial. Esta vez se ha dejado un camino de 50 píxeles de ancho en el fondo de tu jardín y se ha llenado el resto con zanahorias.

