# Adivina_el_numero
Desarrollo de un juego de adivinanzas en lenguaje Python.
Se pretende realizar mediante el lenguaje Python un programa que simule un juego de adivinanza.
Al comenzar el juego y durante el desarrollo del mismo las opciones que se muestran hasta elegir la opción salir son:
1. Partida modo solitario
2. Partida 2 Jugadores
3. Estadística
4. Salir
Modo solitario supone que el número a adivinar es generado aleatoriamente por el ordenador.
Modo 2 Jugadores: primero se escribe un número a adivinar y luego un segundo jugador intenta adivinarlo.
El número a adivinar debe ser entre 1 y 1000.
Tanto la opción 1 como la opción 2 tendrán el siguiente submenú para elegir la dificultad
1. Fácil (20 intentos)
2. Medio (12 intentos)
3. Difícil (5 intentos)
En ambos menús debe chequearse que la opción elegida es válida y avisar en caso contrario.
Si se adivina el número se gana la partida y se vuelve al menú principal, sino se indica si el número buscado es mayor o menor.
Si se supera el número de intentos se pierde y se vuelve al menú principal.
Se gane o se pierda se pide el nombre del jugador y se guarda esta información junto con el resultado de la partida en un fichero Excel.
La opción estadística nos mostrara los datos almacenados en Excel.
