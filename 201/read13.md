# Local Storage and How To Use It On Websites

1. ¿Por qué un desarrollador utilizaría el local storage para una aplicación web?

- Es una herramienta que permite la persistencia de datos, lo que significa que la información se conserva incluso después de que el usuario cierra el navegador o recarga la página, es ideal para almacenar configuraciones de usuario,facilita la creación de aplicaciones más interactivas y dinámicas, ya que permite guardar y recuperar datos y su uso es bastante sencillo solo se necesita JavaScript para acceder y manipular los datos.

2. ¿Qué información no se puede guardar en el local storage?

- No se debe almacenar información sensible **como contraseñas o datos de tarjetas de crédito** en local storage, ya que es accesible a través de JavaScript y vulnerable a ataques, **local storage** tiene un límite de almacenamiento, generalmente de 5 a 10 MB por orige lo que lo convierte inadecuado para guardar grandes cantidades de datos **como imágenes o videos**, tampoco se pueden almacenar objetos JavaScript directamente estos deben ser convertidos a texto antes de ser guardados.

3. ¿Qué tipo de datos se pueden guardar en el local storage? ¿Cómo puedes convertirlo a ese tipo de archivo antes de guardarlo?

- El **local storage** solo puede almacenar datos en formato de texto, sin embargo se pueden almacenar diferentes tipos de datos al convertirlos a JSON, tenemos que las cadenas de texto se pueden almacenar directamente mientras que los números deben ser convertidos a cadenas usando **toString()** para almacenar objetos y arrays, se utilizan **JSON.stringify()**
