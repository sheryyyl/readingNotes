# How to use Forms in React

1. ¿Qué es un ‘Componente Controlado’?

- Un componente controlado es aquel cuyo que esta totalmente controlado por el estado de React, incluye al input que se actualiza conforme al estado actual.

2. ¿Deberíamos esperar a almacenar las respuestas de los usuarios del formulario en el state cuando envían el formulario O debemos actualizar el state con sus respuestas tan pronto como las ingresen? ¿Por qué?

- Es más práctico actualizar al estado mientras el usuario escribe, ya que esto asegura que el valor esté sincronizado continuamente con el componente React.

3. ¿Cómo utilizamos target lo que el usuario está introduciendo si tenemos un event handler en un campo de input?

- Usamos `event.target.value` en un event handler para acceder al valor actual del campo input. Cada que escribimos algo el evento se dispara, es como estarle diciendo a un amigo algo y te cuenta esto mientras lo esta escribiendo.

# Conditional (Ternary) Operator Explained

1. ¿Por qué utilizaríamos un operador ternario?

- El operador ternario nos permite escribir condiciones de forma más compacta en una sola línea de código, simplifica la lectura especialmente cuando solo se necesita asignar un valor dependiendo de una condición simple, basicamente te permite hacer una elección rápida es como decir "si es verdad, haz esto, si no, haz lo otro".

2. Vuelve a escribir la siguiente declaración utilizando una declaración ternaria:

        if(x===y){
        console.log(true);
        } else {
        console.log(false);
        }


Se vería asi: `x === y ? console.log(true) : console.log(false);`
