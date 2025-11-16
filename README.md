# 🚀 Misión Scratch: Primeros Pasos

¡Una mini-aventura interactiva creada con HTML, CSS y JavaScript para enseñar los conceptos fundamentales de Scratch de una manera divertida y visual!

## 🎯 ¿Qué es este proyecto?

Este proyecto es un "juego" web de una sola página diseñado con una estética retro-pixel (inspirada en Mario) que guía a los nuevos usuarios a través de los pilares de la programación en Scratch. El objetivo es que, en lugar de solo leer, el usuario interactúe con los conceptos.

## ✨ Características principales

El proyecto se divide en cuatro pantallas o "niveles":

1.  **Pantalla de Bienvenida**: Introduce la misión y da la bienvenida al usuario con una estética de cielo y nubes animadas.
2.  **Conceptos Clave**: Utiliza un sistema de "tarjetas" para explicar visualmente qué son los **Eventos**, el **Movimiento**, la **Apariencia** y los **Sprites**, mostrando simulaciones de los bloques de Scratch.
3.  **Mini Editor (Drag & Drop)**: ¡La parte más importante! El usuario debe arrastrar y soltar bloques de Scratch (Evento, Decir y Mover) en el orden correcto para construir un script funcional. El proyecto valida la secuencia y da feedback.
4.  **Mini Reto Final**: Una sencilla pregunta de tipo quiz para consolidar el conocimiento (sobre el bloque "Repetir").

Al finalizar el reto, el juego se reinicia, listo para un nuevo usuario.

## 🛠️ Tecnologías Utilizadas

Este proyecto se construyó desde cero utilizando únicamente las tres tecnologías base de la web:

* **HTML5**: Para la estructura semántica de las diferentes pantallas y contenedores.
* **CSS3**:
    * **Variables CSS (Custom Properties)**: Para manejar fácilmente la paleta de colores (estilo Mario y estilo Scratch).
    * **Flexbox y Grid**: Para el layout responsive de las pantallas y las tarjetas.
    * **Animaciones (`@keyframes`)**: Para las nubes del fondo.
    * **Estilos de Pseudo-elementos (`::before`, `::after`)**: Para crear las muescas y salientes de los bloques de Scratch.
* **JavaScript (ES6+)**:
    * **Manipulación del DOM**: Para mostrar y ocultar las diferentes pantallas (`.screen`).
    * **Event Listeners**: Para los botones y la navegación.
    * **API Drag and Drop**: Para la funcionalidad de arrastrar y soltar en el mini editor.
    * **Lógica de validación**: Para comprobar si la secuencia de bloques es correcta y dar feedback al usuario.

## 🏃‍♀️ Cómo usar este proyecto

No se requiere instalación. ¡Es solo un sitio web!

1.  Clona o descarga este repositorio.
2.  Abre el archivo `index.html` en tu navegador web preferido.
3.  ¡Juega y aprende!

## 💡 Posibles Mejoras a Futuro

* [ ] Añadir más bloques al mini-editor.
* [ ] Incluir bloques de "Control" (como el `Repetir` del quiz).
* [ ] Guardar el progreso en `localStorage`.
* [ ] Añadir efectos de sonido "retro" al hacer clic y al completar tareas.