# Conceptos básicos de los objetos JavaScript
1. ¿Cómo le describirías un objeto a un amigo sin conocimiento técnico con el que creciste?
-  Es como una organizador de escritorio, donde cada compartimento tiene un nombre y guarda algo específico.

2. ¿Cuáles son algunas de las ventajas de crear objetos literales?
- Son organizados, fáciles de acceder y flexibles para agrupar datos relacionados.
3. ¿En qué se diferencian los objetos de los arrays?
- Los objetos guardan pares de nombre-valor (como una lista de cosas etiquetadas), mientras que los arrays guardan elementos ordenados en una lista.
4. Da un ejemplo acerca de los momentos en los que necesitarías utilizar bracket notation para acceder a la propiedad de un objeto en vez de dot notation.
- Cuando el nombre de la propiedad es dinámico o contiene caracteres especiales, como un espacio o un número al inicio `(obj["nombre completo"])`.
5. Evalúa el siguiente código. ¿A qué se refiere el término this y cuál es la ventaja de utilizarlo?

        - const dog = {
        name: 'Spot',
        age: 2,
        color: 'white with black spots',
        humanAge: function (){
        console.log(`${this.name} is ${this.age*7} in human years`);
        }
        }

- Tenemos que, **`this`** se refiere al objeto definido como **dog**. La ventaja de usar **`this`** es que permite acceder a las propiedades del objeto desde dentro de sus métodos, lo que hace el código mucho más reutilizable y adaptable.

# Introducción al DOM

1. ¿Qué es el DOM?
-  Es una representación estructurada de un documento HTML o XML que tiene forma de árbol, de esta forma nos permite acceder y poder modificar el contenido y estilo que tiene el documento.
2. Describe brevemente la relación entre el DOM y JavaScript.
- JavaScript usa el DOM para manipular y cambiar dinámicamente los elementos de una página web.