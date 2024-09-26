# Formularios en HTML

## Mi primer formulario HTML. Cómo estructurar un formulario HTML.

1. ¿Por qué los formularios son tan importantes en el desarrollo web?

- Los formularios son importantes porque permiten a los usuarios enviar datos al servidor, esenciales para funciones como registros y compras.

2. Al diseñar un formulario, ¿cuáles son algunas de las cosas más importantes a tener en cuenta sobre la experiencia de usuario?

- El formulario debe tener claridad, ser fácil de entender y rellenar con etiquetas claras para cada campo, además contar con accesibilidad incluyendo a usuarios con discapacidades, el tamaño y disposición deben mantenerse sorganizados y finalmente contar con un feedback que muentre mensajes claros sobre errores o éxito tras enviar un formulario.

3. Enumera 5 elementos de los formularios y explica su importancia.
Aprende JS
- `<input type="text">`: Permite al usuario ingresar texto simple. Además ss útil para obtener datos como nombres, direcciones, etc.
- `<input type="email">`: Este elemento valida automáticamente que el valor sea un correo electrónico válido.
- `<select>`: Crea un menú desplegable para que el usuario elija una opción predefinida, útil para seleccionar entre varias alternativas.
- `<input type="submit">`: Botón que envía los datos del formulario al servidor.
- `<textarea>`: Permite al usuario introducir texto largo, ideal para comentarios o descripciones detalladas.

## Introducción a los Eventos.

1. ¿Cómo describirías los event a un amigo sin conocimiento técnico?

- Es una acción que ocurre en una página se da como un click o al presionar una tecla.

2. Al utilizar el método addEventListener(), ¿cuáles son los 2 arguments que debes proporcionar?

- Deberiamos estar emplementando `El tipo de evento` **(cadena que representa el tipo de evento a escuchar)** y `La función callback` **(función que se ejecutará cuando ocurra el evento)**.

3. Describe el objeto event. ¿Por qué el target dentro del objeto event es útil?

- El `objeto event` es un **parámetro**, `event.target` es una propiedad del objeto event que hace referencia al elemento exacto donde se originó el evento.

4. ¿Cuál es la diferencia entre event bubbling y event capturing?

- **Event bubbling**: El evento se dispara primero en el elemento que lo generó y luego sube por los elementos padres hasta el document. Este es el comportamiento por defecto.

- **Event capturing**: El evento empieza desde el elemento más externo y baja se dirige hasta el elemento que lo originó. Se activa en addEventListener().
