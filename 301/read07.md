# Express en español
# Extiende tus conocimientos consultando con un agente de IA

1. ¿Qué es Express y por qué es tan popular en Node.js?

- Express es un framework minimilista y flexible, este permite crear aplicaciones web y APIs de manera rápida y sencilla, basicamente simplifica el proceso de desarrollo web en Node.js proporcionando herramientas de manera más eficiente.
- En otras palabras hace todo más sencilla es como tener todas las herramientas listas con todo lo que necesitas para hacer un sitio web y no tener que empezar desde 0. 

2. ¿Cuáles son los beneficios de usar Express versus usar Node.js puro?

- `middleware` : al usar esto podemos verificar entre permisos o si la info ya esta lista para ser mostrada, es como un ayudante o manager que se encarga de ver si todo esta ok.

- Express proporciona un API de alto nivel que permite manejar rutas, peticiones y respuestas sin necesidad de escribir el código desde 0, tiene facilidad al definir rutas de aplicaciones mediante métodos, `middleware` permite gestionar solicitudes y respuestas de manera mucho mas flexible además podemos agrear funcionalidades sin complicar el código.

- Express es como tener algo ya armado con todo lo necesario, en cambio con al usar Node.js puede ser más lento y complicado puesto que tienes que hacer todo desde 0.

3. ¿Qué significa que Express es un framework “minimalista”?

- **Express** no impone un estructura escrita y tampoco una arquitectura completa, proporciona funcionalidades para la creación de la web, basicamente es como si te proporcionara unos zapatos pero tu decides si caminar con estos, decorarlos o revenderlos, te da una libertad de hacer las cosas que tu desees sin que **Exprees** te diga como hacero exactamente. 

4. ¿Cómo se escribe una ruta en Express?

- Para definir una ruta en **Express** se utiliza un método HTTP (get, post, put, delete), 

        const express = require('express'); // esto es un servidor que esta siendo llamado 
        const app = express();

        app.get('/', (req, res) => { // se cargará cuando entres a la ruta principal
        res.send('¡Hola, Mundo!');
        });

- Acá lanzará el mensaje "¡Hola, Mundo!". 
- Basicamente las rutas es por donde pasarán los usuarios antes de llegar al sitio web, **Express** indicará que tiene que hacer en todo el tramo.