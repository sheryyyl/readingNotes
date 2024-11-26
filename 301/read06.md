## Introducción a Node.js en español
## Trabajar con variables de entorno en Node.js
## CommonJS vs ES Modules

1. ¿Cuál es la diferencia entre Node.js y el runtime de JavaScript del navegador?

- Node.js permite ejecutar Javascript en el servidor, mientras que lo navegadores solo ejecutan Javascript en el lado del cliente. Como explica el artículo, el runtime de un navegador está optimizado para interactuar con el DOM y gestionar la interfaz de usuario, mientras que Node.js permite acceder a recursos del sistemas, como el sistema de archivos.

2. ¿Qué es npm y cuál es su relación con Node.js?

- npm es el gestor de paquetes de Node.js permite instalar y gestionar dependencias, bibliotecas y herramientas necesarias para desarrollar aplicaciones con Node.js.

3. ¿Por qué son importantes las variables de entorno en el desarrollo de aplicaciones?

- Las variables de entorno permiten almacenar información sensible de manera seguro, como cavles API y credenciales de bases de datos, sin exponerlas directamente en el código, además las variables de entorno facilita la configuración según el entorno sin tener que modificar el código.

4. ¿Cuál es la diferencia entre CommonJS y ES Modules?

- La diferencia radica en como se manejan las importaciones y exportaciones de módulos, **CommonJS** utiliza `requiere()` para importar módulos y **module.exports** para expotarlos, mientras que en `ES Modules` utilizamos palabras claves como **import** y **export** . Además tenemos que **CommonJS** solo permite la carga síncronica de módulos que puede bloquear la ejecución hasta que esten completamente cargados, mientras que **** permite la carga sincrónica y asincrónica que da una mejor eficiencia al manejar aplicaciones más grandes.
- En otras palabras **module.exports**  es que a la hora de pedir algo se realiza de forma directa y sin pausas mientras que en **CommonJS** también podemos hacerlo de manera más flexible, puedes pedir varias cosas sin esperar. Teniendo en cuenta que **CommonJS** es más antiguo que **module.exports** siendo este más moderno y flexible.

5. ¿Qué es el package.json y cuál es su importancia?

- El archivo  **package.json** es fundamental para proyectos de Node.js ya que contiene toda la metadata relacionada con el proyecto a realizar `(nombre, versión, dependencias y scripts)`, además facilita la gestión de dependencias, la configuración de tu proyecto y la automatización de tareas con scripts ya definidos.
