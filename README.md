# GT3 RS · Configurador 3D

Borrador de configurador 3D futurista (Three.js):

- Cambio de color de pintura y acabado (brillo / metalizado / mate)
- Tintado de vidrios (de transparente a oscuro total)
- Suspensión regulable (modo pista y front lift)
- Color de llantas, escenario neón con auto-giro

## Modelo 3D
Si hay un archivo `modelo.glb` en la raíz del repositorio, la página lo carga automáticamente.
Si no, se muestra un coche de demostración (modelo de ejemplo de three.js).
Las piezas cuyo nombre contenga `body`/`paint` y `glass`/`window` se conectan a los controles de pintura y vidrios.
