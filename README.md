# NOVA ARCADIA 2087 — MODERN EDITION 3.0

Versión 2D moderna y detallada del videojuego «Escape de Morfeo».

## Publicación en GitHub Pages

1. Extraé este ZIP.
2. Subí **el contenido**, incluido `index.html`, a la raíz de un repositorio de GitHub.
3. En Settings → Pages, elegí Deploy from a branch, `main` y `/ (root)`.
4. Abrí la dirección de GitHub Pages.

## Contenido

- Cinco sectores jugables con mapas generados por semilla.
- Tres dificultades: fácil (5 vidas, 20 min), medio (3 vidas, 14 min) y difícil (2 vidas, 10 min).
- Modo individual, apodos, cronómetro, objetivos y drones.
- Salas de 2 a 4 participantes usando Firebase Realtime Database y autenticación anónima.
- Controles de teclado y táctiles.
- Historia original en `/historia/index.html`.
- Estética MODERN EDITION: arte de portada detallado, interfaz renovada, materiales e iluminación en canvas y Kai con silueta humana.

## Pruebas necesarias

El proyecto no se ha validado con partidas reales en navegadores o con las reglas de tu Firebase. Probá especialmente: acceso anónimo, crear/unirse a sala, iniciar carrera, cambio de nivel y clasificación. La sincronización y validación de resultados necesitan controles adicionales en servidor para impedir trampas; las reglas de Firebase existentes deben permitir las rutas que utiliza el código.

El proyecto utiliza Firebase desde CDN; se requiere conexión a Internet para multijugador.
