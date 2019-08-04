# Ejercicio Texas Holdem

## Descripción del problema

Tu trabajo es comparar pares de manos de póquer e indicar cuál es el ganador, y con que tipo de mano gano

Debe tener en cuenta que solo debe implementar 5 de los 10 tipos de manos pero en el orden normal, por ejemplo: Escalera real, Escalera de color, Poker, Full House y Color

## Descripción de las reglas de poker

Una baraja de póquer contiene 52 cartas; cada carta tiene un palo que es uno de los tréboles, diamantes, corazones o espadas (indicados con C , D, H y S respectivamente). Cada tarjeta también tiene un valor que es uno de 2, 3, 4, 5, 6, 7, 8, 9, 10, jota, reina, rey, as (denotado 2, 3, 4, 5, 6, 7, 8 , 9, 10, J, Q, K, A). Para fines de puntuación, los trajes no están ordenados, mientras que los valores se ordenan como se indicó anteriormente, siendo 2 el valor más bajo y el más alto el as.

Una mano de poker consiste en 5 cartas repartidas desde el mazo. Las manos de póquer se clasifican según el siguiente orden parcial de menor a mayor.

- Carta alta: Las manos que no encajan en ninguna categoría superior se clasifican según el valor de su carta más alta. Si las cartas más altas tienen el mismo valor, las manos se clasifican por la siguiente más alta, y así sucesivamente.

- Par: 2 de las 5 cartas en la mano tienen el mismo valor. Las manos que contienen un par se clasifican según el valor de las cartas que forman el par. Si estos valores son los mismos, las manos se clasifican según los valores de las cartas que no forman el par, en orden decreciente.

- Dos pares: La mano contiene 2 pares diferentes. Las manos que contienen 2 pares se clasifican por el valor de su par más alto. Las manos con el mismo par más alto se clasifican según el valor de su otro par. Si estos valores son los mismos, las manos se clasifican según el valor de la carta restante.

- Tres de una clase: Tres de las cartas en la mano tienen el mismo valor. Las manos que contienen tres de una clase se clasifican según el valor de las 3 cartas.

- Escalera: La mano contiene 5 cartas con valores consecutivos. Las manos que contienen una recta se clasifican por su carta más alta.

- Color: Mano contiene 5 cartas del mismo palo. Las manos que son ambos enrojecimientos se clasifican según las reglas de Carta alta.

- Full House: 3 cartas del mismo valor, con las 2 cartas restantes formando un par. Clasificado por el valor de las 3 cartas.

- Poker: 4 cartas con el mismo valor. Clasificado por el valor de las 4 cartas.

- Escalera de color: 5 cartas del mismo palo con valores consecutivos. Clasificado por la carta más alta de la mano.

- Escalera real: Cinco cartas del mismo palo del 10 al as.

## Instrucciones

Debe crear una cuenta en github y un repositorio público con el contenido de este proyecto, una vez creado debe enviarnos la dirección

Los test ya fueron creados, debe crear las clases que representan las entidades del dominio (ejemplo: Carta, Mano, etc) y los métodos para evaluar el problema según se indicó anteriormente.

Debe implementar **solo** 5 de las 10 validaciones, debe indicar cuáles de las 5 selecciono.

Tambien debe implementar los test con los casos mensionados en la descripcion segun las validaciones que escoja.

Se evaluará:
- Estilo de codificación.
- Diseño de los módulos y las clases.
- Lógica de la implementación.
- Que el proyecto funcione correctamente (es decir que al bajar el proyecto de git solo se use maven para la configuración y pueda correr el proyecto).
- Que pasen los test asociados a los casos que seleccionó.
- Se da un plus si crea nuevos test
- Se da un plus si implementa más de las 5 validaciones, pero solo si funcionan todas las que implemente.


