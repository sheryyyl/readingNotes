# Listas en HTML, Control de flujo en JS, y CSS: Box Model
## Aprende HTML
1. ¿Cuándo se puede utilizar una lista no ordenada en tu documento HTML?
- Una lista no ordenada se usa cuando el orden de los elementos no importa. Es útil para listas o cualquier conjunto de elementos en los que la secuencia no es relevante.
2. ¿Cómo cambias el estilo bullet de la lista de elementos no ordenados?
- Se puede cambiar el estilo del bullet utilizando la propiedad `list-style-type` en **CSS**.
3. ¿Cuándo debes usar una lista ordenada o lista no ordenada en tu documento HTML?
- Usaremos una lista ordenada `**<ol>**` cuando el orden de los elementos sea importante, como en instrucciones, tambien podemos usarlas para clasificaciones. Usaremos una lista no ordenada `**<ul>**` cuando el orden no importa y solo necesites agrupar elementos, podrías usarla en una lista de características o un menú.
4. Describe dos formas en las que puedes cambiar los números en los elementos de la lista proporcionados por una lista ordenada
- Cambiar el tipo de **numeración** con `list-style-type`.
- Cambiar el **valor inicial** con el atributo `start`.


## Aprende CSS
1. Describe las propiedades de margin y padding en CSS como si fueran los personajes de una historia. ¿Cuál es su rol en la historia: “El Box Model”?
- Conociendo la historia del **"Box Model"**, `padding` es el guardián que protege al contenido, se asegura de que tenga espacio a su alrededor es decir no dejará que el contenido choque con el borde. Por otro lado `margin`, es el vigilante exterior, se asegura de que otros elementos respeten la zona del contenido, creando espacio entre el contenido y los elementos vecinos. Estos protegen al contenido y a su espacio.

2. Enumera y describe las cuatro partes de un box del elementos HTML según el box model.

- Content o **Contenido**: La parte central del box, donde se muestra el texto o los elementos multimedia.
- Padding o **Relleno**: El espacio entre el contenido y el borde del box, que aumenta unicamente la distancia alrededor del contenido.
- Border o **Borde**: La línea que rodea al padding y contenido, puede ser visible o invisible, variando de los estilos que se podrian agregar al **CSS**.
- Margin o **Margen**: El espacio entre el borde del box y los elementos, separando visualmente el box de los demás.

## Aprende JS
1. ¿Qué tipos de datos puedes almacenar en un Array?
- Un array puede almacenar números, strings, booleanos, objetos, etc.
2. ¿El array people es un array de JavaScript válido? De ser así, ¿cómo puedo acceder a los valores almacenados? Y si no, ¿por qué?
- Si people está declarado como un array válido, por ejemplo: `let people = ["John", "Jane", "Tom"];`, puedes acceder a los valores almacenados utilizando los índices:

    - people[0] accede a "John".
    - people[1] accede a "Jane".
    - people[2] accede a "Tom".

3. Enumera cinco opreadores abreviados de asignación en javascript y describe lo que hacen.
    - `+=`: Suma el valor de la derecha al de la izquierda y asigna el resultado. 
    - `-=`: Resta el valor de la derecha al de la izquierda y asigna el resultado. 
    - `*=`: Multiplica el valor de la derecha por el de la izquierda y asigna el resultado.
    - `/=`: Divide el valor de la izquierda por el de la derecha y asigna el resultado. Ejemplo:
    - `%=`: Asigna el resto de la división entre los valores de la izquierda y la derecha.
4. Lee el código a continuación, evalúa la últimaexpresión y explica cuál sería el resultado y por qué.
      -     let a = 10;
            let b = 'dog';
            let c = false;

            // evalúa esto
            (a + c) + b;
            
- Tenemos que La expresión (a + c) + b evaluada da como resultado '10dog', porque se sumó el valor de a con c (que dio 10), y luego ese 10 se concatenó con la cadena 'dog'.

5. Describe un ejemplo cotidiano de por qué una declaración condicional se debería usar en un programa en JavaScript.
- Un ejemplo cotidiano podría ser la verificación de edad en una página web. Usarías una declaración condicional para verificar si la edad ingresada por un usuario es mayor o igual a 18. Si lo es, le permites acceder al contenido.

6. Da un ejempo de por qué un Bucle es últil en JavaScript.
- Un bucle es útil para repetir tareas automáticamente, si tienes una lista de nombres en un array y deseas imprimir cada uno en la consola, puedes usar un bucle `for` para iterar sobre el array en lugar de escribir múltiples líneas de código.