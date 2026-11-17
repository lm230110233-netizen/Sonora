# Decisiones

**Componentes que reutilicé tal cual**
- Los tokens de color, tipografía, radios, espaciado y sombra, con los mismos nombres del sistema.
- Las recetas de clases de botón primario, botón secundario, chip, tarjeta de medio, fila de canción, buscador y barra de progreso.
- La reproducción simulada con un arreglo de canciones y un temporizador.

**Qué cambié y por qué**
- Usé Tailwind v3 por CDN, así que los tokens están en `tailwind.config` y en `:root`, como indica el brief para v3.
- El logo y los iconos están dibujados en línea (SVG), en lugar de cargarlos desde `assets/`.
- En la barra inferior los controles son secundarios, para que cada vista tenga un solo botón primario ámbar.
- La barra se oculta en la pantalla Reproductor, donde el botón de reproducir ya es el principal.
- En móvil el menú pasa a su propia fila y muestra solo texto.
