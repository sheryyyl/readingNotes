# ¿Cuál es el propósito de CSS?
- `CSS` __(Cascading Style Sheets)__ es un lenguaje utilizado para describir la presentación de un documento escrito en HTML, tiene como __propósito principal__  separar el contenido del documento de su presentación, permitiendo definir y aplicar estilos como colores, fuentes, espaciado, y diseño general a los elementos del documento. Esto facilita el mantenimiento y la reutilización del código, así como la creación de interfaces de usuario más atractivas y coherentes en las páginas web.
# ¿Cuáles son las tres formas de insertar CSS en tu proyecto?

- CSS en línea __(inline CSS):__ Se utiliza el atributo style directamente en el elemento HTML que se quiere estilizar.
    - `<p style="color: red;">` Este texto será rojo`</p>`

- CSS interno __(internal CSS):__ Se incluye un bloque de estilo dentro de la etiqueta `<style>` en la sección "header"
 
    - `<style>`
        p {
            color: red;
        }
    `</style>`

- CSS externo __(external CSS):__ Se crea un archivo separado con extensión .css y se enlaza en el documento HTML usando la etiqueta `<link>`.

   - `<link rel="stylesheet" type="text/css" href="styles.css">`

# Escribe un ejemplo de una regla CSS que daría texto rojo a todos los elementos `<p>`
- `p {
    color: red;
}`