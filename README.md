# Poker Básico

Este es un proyecto de juego de poker básico desarrollado en Python, donde dos jugadores compiten contra un crupier controlado por la máquina. El juego incluye la lógica básica del poker, donde se reparten cartas aleatorias a cada jugador y al crupier, se muestra el flop y se determina el ganador basado en la mano de cada jugador y las cartas comunitarias.

## Características principales

- **Juego de poker básico:** Implementa las reglas fundamentales del poker para dos jugadores y un crupier.
- **Reparto de cartas aleatorio:** Las cartas se reparten aleatoriamente a cada jugador y al crupier, y se restan del mazo después de ser repartidas.
- **Determinación instantánea del ganador:** Una vez se muestra el flop, el juego determina instantáneamente al ganador basado en la mano de cada jugador y las cartas comunitarias.
- **Recursos multimedia:** Incluye archivos de música e imágenes que pueden ser utilizados en el juego.

## Instalación

1. Clona el repositorio a tu máquina local:

    ```bash
    git clone https://github.com/ipfabio/poker-basico.git
    ```

2. Navega al directorio del proyecto:

    ```bash
    cd poker-basico
    ```

3. Ejecuta el juego:

    ```bash
    python main.py
    ```

## Estructura del proyecto

El proyecto está organizado en cuatro módulos:

- **Hand:** Contiene la lógica para evaluar las manos de los jugadores.
- **Cards:** Define la estructura de las cartas y métodos para el manejo de cartas.
- **Settings:** Incluye configuraciones y constantes utilizadas en el juego.
- **Main:** Es el punto de entrada principal del juego.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir a este proyecto, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una rama para tu nueva funcionalidad: `git checkout -b nueva-funcionalidad`.
3. Haz tus cambios y commitea: `git commit -m 'Añade una nueva funcionalidad'`.
4. Empuja tus cambios a la rama: `git push origin nueva-funcionalidad`.
5. Abre un pull request en el repositorio original.

## Licencia

Este proyecto está bajo la Licencia [Tipo de Licencia]. Para más detalles, consulta el archivo `LICENSE`.
