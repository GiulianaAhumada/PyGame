# PyGame

🎯 Objetivo del juego
Descubrir todas las casillas que no tienen minas. Si haces clic en una mina, perdés.

🟦 Cómo se juega
Tablero: Es una cuadrícula con casillas ocultas. Algunas tienen minas, otras están vacías.

Primer clic: Siempre es seguro (no hay mina). El juego empieza revelando algunas casillas.

Clic izquierdo: Revela una casilla.

Si tiene un número, ese número indica cuántas minas hay en las 8 casillas alrededor.

Si está vacía, se revelan automáticamente más casillas vacías cercanas.

Si tiene una mina, perdiste.

Clic derecho: Marca una casilla con una bandera 🚩 si creés que hay una mina ahí.

Podés volver a hacer clic derecho para poner un signo de pregunta (?) o quitar la marca.

📊 Estrategia básica
Si ves un número (ej: 1) y hay una sola casilla sin descubrir al lado, esa casilla tiene una mina ⇒ poné una bandera.

Cuando hayas marcado todas las minas alrededor de un número, podés abrir con seguridad las demás casillas vecinas.

