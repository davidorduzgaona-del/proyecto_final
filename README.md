# proyecto_final
_Jesus David Orduz Gaona_

Simulador 2D de dron en escenarios de desastre creado en Python con Pygame. Permite controlar un dron para explorar zonas afectadas, evitar obstáculos y llegar al objetivo. Simula navegación, colisiones y rescate en entornos peligrosos con controles W, A, S, D o flechas.

python codigo_fuente_proyecto_final.py

## libreria externa 
**pygame**  
pip install pygame

# desiciones de diseño 
_Se usó una matriz para representar el entorno 2D del desastre, donde cada celda indica muros, espacios libres, el dron y el objetivo_

_El movimiento se controla por coordenadas (x, y) para simplificar la detección de colisiones y límites del mapa_

_Se eligió Pygame porque permite representar visualmente el entorno de manera clara y sencilla, permitiendo generar tanto las estructuras como el dibujo directo de nuestro dron en el codigo, ademas que pygame ofrece muchas alternativas dinamicas al momento de usar comandos_

El código se organizó en funciones ([dibujar_mapa], [mover_dron], [reiniciar_mapa])
