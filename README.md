# Cuatro en Raya 3D

Juego de cuatro en raya (Connect 4) en 3D contra la computadora, en una única página web con [three.js](https://threejs.org/).

- Tablero clásico 7×6 y modo cubo 4×4×4 (cuatro en raya tridimensional).
- Cinco niveles de dificultad: la IA usa negamax con poda alfa-beta y profundización iterativa, ejecutada en un Web Worker.
- Cámara orbital, fichas con relieve y textura, línea ganadora resaltada, marcador persistente, tema claro y oscuro.

Todo está en `index.html`; basta con abrirlo en un navegador con conexión a internet (three.js y las fuentes se cargan desde CDN).
