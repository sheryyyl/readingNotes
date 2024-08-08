# HTML

1. ¿Por qué es importante utilizar elementos semánticos en nuestro HTML?

- Su valor semántico se puede usar de diferente manera, por ejemplo, por los motores de búsqueda y los lectores de pantalla, además es más fácil de leer y entender.

2. ¿Cuántos niveles de encabezado existen en HTML?

- **HTML** trabaja con seis niveles de encabezado:
  - `<h1>` (nivel más alto y más importante)
  - `<h2>`
  - `<h3>`
  - `<h4>`
  - `<h5>`
  - `<h6>` (nivel más bajo y menos importante)

3. ¿Cuáles son algunos de los usos para los elementos `<sup>` y `<sub>`?

- Son elementos en HTML para formatear texto, no muy conocidos. Se usa para texto que debe aparecer ligeramente por encima o debajo del texto.

4. Al utilizar el elemento `<abbr>`, qué atributo se debe añadir para proporcionar una ampliación del término?

- Proporcionamos una expansión completa del término dentro de un atributo **`title`**.

# CSS

1. ¿De qué formas podemos añadir CSS a nuestro HTML?

- Existen 3 maneras para añadir CSS, directamente en el atributo `style`, dentro de una etiqueta `<style>` o enlazandola.

2. ¿Por qué deberíamos evitar utilizar estilos inline?

- Hacen que el código sea más difícil de mantener y actualizar, además estilos inline mezcla los estilos con el contenido del HTML.

3. Revisa el código a continuación y responde a las siguientes preguntas:
   - `h2 {
     color: black;
     padding: 5px;
   }`
    1. ¿Qué representa el selector?
    - El selector es **h2**. Este selector de tipo se aplica a todos los elementos `<h2>` del HTML.
    2. ¿Qué componentes son declaraciones CSS?
    - `color: black;`
    - `padding: 5px;`
    3. ¿Qué componentes se consideran propiedades?
   - `color` refiriendose al color del texto.
   - `padding` espacio interior alrededor del contenido.

# JS

1. ¿Qué tipo de dato es una secuencia de texto entre comillas simples?
- string es un tipo de dato de cadena.
2. Enumera 4 tipos de operadores en JavaScript.
- Tenemos a los operadores aritméticos, de comparación, lógicos y de asignación.
3. Describe un problema práctico que puedes resolver con una función.
- Un click sobre el botón ejecutará una función para por ejemplo abrir un correo. Lo que hace JavaScript es manejar el evento sobre el botón y gestionarlo a conveniencia pudiendo interactuar con otras partes de la pagina

- ### código — condicionales

1. Si una declaración if comprueba un **`condición`**  y si resulta **`verdadera`**, entonces el código se ejecutará.
2. ¿Cuál es el uso del else if?
- El **else if** se utiliza para comprobar condiciones cuando la condición inicial del if es falsa da paso a verificar otras condiciones. Se puede manejar diferentes casos.
3. Enumera 3 tipos de operadores de comparación.
    - `==` **(igual a)**
    - `!=` **(diferente de)**
    - `>` **(mayor que)**
4. ¿Cuál es la diferencia entre los operadores lógicos && y ||?
- `&&` = Devuelve true solo si ambas condiciones son verdaderas.
- `||` = Devuelve true si al menos una de las condiciones es verdadera.
