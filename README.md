# Proyecto final y optativo IG

Se ha decidido ampliar varias ampliaciones de la última tarea con VR en codesandbox. Aunque aparentemente sencillas, estas enriquecen la experiencia de juego.

### Funcionalidades Añadidas:

- **Barras de Vida en 3D:** Se ha implementado un sistema de salud visual sobre la cabeza de cada modelo. Consiste en 5 bloques rectangulares que representan la vida del objetivo.
- **Gradación de Color (Color Grading):** Las barras de vida cambian de color dinámicamente según el daño recibido. Empiezan en verde, pasan a lima, amarillo, naranja y terminan en rojo cuando queda poca vida.
- **Mensaje "Catch it NOW!":** Cuando la vida de un modelo llega a 0, la barra de vida desaparece y es reemplazada por un cartel que dice "Catch it NOW!", indicando que el siguiente golpe capturará al objetivo.
- **Marcador en la Mano Izquierda:** Se ha añadido un texto flotante sobre el controlador izquierdo que muestra la puntuación actual frente al total de objetivos (ej. "Score: 1 / 4").
- **Texto de Alto Contraste:** Para mejorar la legibilidad en el entorno VR, tanto el marcador como el mensaje de captura utilizan una fuente blanca con un **borde negro grueso** y un fondo semitransparente, evitando que se pierdan contra el cielo o el entorno.
- **Escalado Inteligente de UI:** Se ha añadido lógica para contrarrestar el tamaño de los modelos. Ahora, la barra de vida y el texto se ven del mismo tamaño (aproximadamente 1 metro de ancho) tanto en el T-Rex gigante como en el Pikachu pequeño.
- **Corrección de Altura para el T-Rex:** Se añadió una excepción específica para el T-Rex para colocar la interfaz mucho más arriba, compensando su gran altura.
- **Efecto "Billboard":** Todos los elementos de la interfaz (barras de vida y textos) rotan automáticamente para mirar siempre hacia la cámara del jugador, asegurando que siempre sean visibles sin importar hacia dónde camine el Pokémon.
