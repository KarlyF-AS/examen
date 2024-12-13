# Examen 1ª Evaluación
## #Realiza el diagrama de flujo para recorrer un tablero (8x8) de "Damas", sacando por pantalla si la casilla está ocupada (mostrando la coordenada) y que tipo de ficha es. Además cuenta las fichas de cada jugador sacando por pantalla quien va ganando. 
![diagrama](Descargas/20241213_100136%20%281%29.jpg)
## Explicación del Código

Este código recorre un tablero de **Damas** 8x8, verifica si las casillas están ocupadas, cuenta las piezas de cada jugador y muestra quién está ganando.

### Pasos del código:

1. **Representación del tablero:**
   El tablero se representa como una matriz de 8x8 en Java, donde:
    - `'R'` representa una ficha roja.
    - `'N'` representa una ficha negra.
    - `' '` representa una casilla vacía.

   Ejemplo de un tablero inicial:

   ```java
   char[][] tablero = {
       {' ', 'R', ' ', 'R', ' ', 'R', ' ', 'R'},
       {'R', ' ', 'R', ' ', 'R', ' ', 'R', ' '},
       {' ', 'R', ' ', 'R', ' ', 'R', ' ', 'R'},
       {' ', ' ', ' ', ' ', ' ', ' ', ' ', ' '},
       {' ', ' ', ' ', ' ', ' ', ' ', ' ', ' '},
       {'N', ' ', 'N', ' ', 'N', ' ', 'N', ' '},
       {' ', 'N', ' ', 'N', ' ', 'N', ' ', 'N'},
       {'N', ' ', 'N', ' ', 'N', ' ', 'N', ' '}
   };
# TABLERO
![Imagen de Tablero de Damas](https://stencilstop.com/cdn/shop/products/checkerboard-stencil-stop_8x8_bf670483-e7cd-4348-bbcd-aef7d9505627.jpg?v=1615987424&width=2048)
