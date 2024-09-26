# Contenido de audio y video

1. Explica cómo la capacidad de utilizar video y audio en la web ha ido evolucionando desde el comienzo de los 2000.

- Tenemos que en los primeros años de los **2000**, era necesario utilizar plugins como `Flash` para reproducir audio y video en la web. A medida que los navegadores y las tecnologías web evolucionaron se incorporaron otras formas nativas de los elementos `<audio>` y `<video>`, haciendo innecesarios los plugins externos y mejorando la accesibilidad, seguridad y compatibilidad de los medios en la web.

2. Describe el uso de los atributos **src** y **controls** en el elemento `<video>`.

- El atributo **src** especifica la ubicación del archivo de video que se va a reproducir, mientras que **controls** habilita un conjunto de controles estándar como reproducir, pausar, volumen y barra de progreso para que el usuario interactúe con el video de manera más fácil.

3. ¿Por qué es importante tener contenido de respaldo en el elemento `<video>`?

- El contenido de respaldo es importante para que, si el navegador no soporta el video, los usuarios vean un mensaje alternativo o tengan otra opción para acceder al contenido. Esto hace que la experiencia sea más amigable y accesible para todos.

4. Escribe una historia corta en donde `<audio>` y `<video>` son personajes. A Complete Guide To Grid

- Tenemos a Audio y Video quienes eran grandes compañeros en la web. Audio siempre traía la mejor música y efectos, y Video hacía que todo se viera increíble. A veces necesitaban ayuda de los controles, pero siempre trabajaban bien juntos. Un día, un navegador viejo no los reconoció, pero no se preocuparon, porque tenían un buen plan de respaldo para seguir en acción.

5. ¿En qué se diferencia el layout Grid del Flex?

- **Grid** es mejor para hacer diseños en dos dimensiones `(filas y columnas)`, mientras que Flexbox es ideal para organizar cosas en una sola fila o columna, grid es más útil para layouts complejos.

6. Grid container, grid item, y grid line son algunos de los términos importantes que se deben entender al utilizar Grid. Por favor describe estos términos en unas pocas frases.

    - **Grid container**: Es el elemento padre que utiliza la propiedad `display: grid` para definir un grid layout.

    - **Grid item**: Son los elementos hijos directos dentro del grid container que se posicionan en las celdas del grid.

    - **Grid line**: Son las líneas que dividen el grid en filas y columnas, las cuales pueden ser utilizadas para posicionar elementos con precisión.

# Imágenes Responsivas

1. Además de hacer que un sitio se vea atractivo visualmente en diferentes tamaños de pantalla, ¿por qué los desarrolladores deberían hacer imágenes responsivas?

- El hacer imágenes responsivas es esencial no solo por el diseño atractivo y la experiencia del usuario. Además tener imagenes adecuadas para diferentes tamaños de pantalla reducen el tiempo de carga y el uso de datos, lo que es especialmente importante en dispositivos móviles.

2. Define los siguientes atributos de `<img>`: **srcset** y **sizes**. Escribe un ejemplo de cómo se usan.

- **srcset**: Especifica diferentes versiones de una imagen para que el navegador elija la más adecuada en función del tamaño de pantalla y la resolución.
- **sizes**: Indica qué ancho ocupará la imagen en diferentes tamaños de pantalla.

3. ¿Cómo es que `srcset` es más útil para las imágenes responsivas que CSS o JavaScript?

- `srcset` es más eficiente porque permite al navegador seleccionar la imagen adecuada sin necesidad de escribir **scripts** adicionales en **JavaScript** o **CSS**. Además, optimiza el rendimiento al cargar solo la imagen necesaria según el dispositivo o la pantalla, lo que reduce el tiempo de carga y el consumo de datos.
