# Documentación de React - listas and keys

1. ¿Qué retorna .map()?

- El metodo `.map()` en JavaScript retorna un nuevo arreglo que contiene los resultados de aplicar la función de mapeo (callback), a cada momento del arreglo original.
- De manera más sensilla podemos decir que retorna una nueva lista o arreglo con lo que decidimos poner dentro de la función que le damos.

2. Si quiero recorrer un bucle a través de un array y mostrar cada valor en JSX ¿cómo lo haría en React?

- Podemos usar método `(map())`, para convertir un arreglo en una lista de elementos en JSX. 

3. Cada elemento de la lista necesita un ____ único.

- Cada elemento necesita una **`key`** única.  Los keys son fundamentales para ayudar a React a identificar que elementos cambian, se agregan o se eliminan en una lista.

4. ¿Cuál es el propósito de una key?

- Las keys ayudan a React a rastrear los elementos y optimizar las actualizaciones. Nos ayuda a identificar de manera única cada elemento, React necesita saber cuál es cada uno para poder actualizarlos correctamente si algo cambia.

5. El Operador Spread

- El operador permite pasar todas las propiedades de una objeto como props en un componente. 

        const props = { name: 'Sheryl', age: 18 };
        <Component {...props} />;

# ¿Qué es el operador spread?
1. Enumera 4 cosas que el operador spread puede hacer.

- Podemos hacer una copia superficial de un array, combinar varios arrays, añadir elementos a un array y también combinar objetos de manera eficiente.

2. Da un ejemplo del uso del operador spread para combinar dos arrays.

        const arr1 = [1, 2];
        const arr2 = [3, 4];
        const combiArreglo = [...arr1, ...arr2];
        console.log(combiArreglo); 

3. Da un ejemplo del uso del operador spread para añadir un nuevo elemento a un array.

- Esto permite añadir nuevos elementos de forma sencilla.

        const arreglo = [1, 2, 3];
        const newArreglo = [...arr, 4];
        console.log(newArreglo);

4. Da un ejemplo del uso del operador spread para combinar dos objetos en uno

- Permite combinar las propiedades de objetos de una forma compacta.

        const obj1 = { a: 1, b: 2 };
        const obj2 = { c: 3 };
        const combiObjeto = { ...obj1, ...obj2 };
        console.log(combiObjeto);

# How to Pass Functions Between Components

1. En el vídeo, ¿cuál es el primer paso que el desarrollador realiza para pasar funciones entre componentes?

- El primer paso que el desarrollador realiza es crear una función en el componente padre luego pasar esa función como una `prop` al componente **hijo**.

2. En tus propias palabras, ¿qué hace la función handleClick?

- Cuando usamos handleClick esperamos que algo pase, podemos contar los clicks, puede cambiar el color de la página, mostrar un mensaje o hacer cualquier cosa que quieras. Practicamente depende de lo que escribas en la función.

3. ¿Cómo se puede transmitir un método de un parent component a un child component?

- **parent**: es un componente principal que contiene a otros componentes más pequeños.
- Para transmitir un método del componente padre al hijo, el componente padre pasa el método como una prop al hijo. Esto lo hace asignando la función en el JSK del componente padre, como si fuera cualquier otro prop. 

4. ¿Cómo el child component llama a un método que se le envió desde un parent component?

- El componente hijo puede llamar al método que se le envió desde el componente padre accediendo a esa función a través de las props. Luego, puede invocar como si fuera una función normal cuando lo necesite, como puede ser en respuesta a un evento como un click.