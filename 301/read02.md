# React lifecycle

1. Según el diagrama, ¿qué sucede primero, el ‘render’ o el ‘componentDidMount’?
- El método `render()` se ejecuta primero antes pues es el método que dibuja o establece el elemento en pantalla luego, luego llamemos al `componentDidMount` que realiza tareas cuando el componente ya esta en el DOM.

2. ¿Qué es lo primero que sucede en el ciclo de vida de React?
- Lo primero que ocurre es la fase `Mounting`, que es lo que pasa cuando una instancia de un componente se esta creando en el DOM.
dentro de esta fase lo primero que ocurre es el **`constructor()`**, en este se pueden inicializar los valores y enlazar métodos de eventos.

3. Coloca las siguientes cosas en el orden en que suceden: componentDidMount, render, constructor, componentWillUnmount, React Updates
    - constructor()
    - render
    - componentDidMount
    - React Updates
    - componentWillUnmount
 
4. ¿Qué hace el componentDidMount?
- Es un método que se ejecuta inmediatamente después de que un componente este en el DOM.

# React State Vs Props

1. ¿Qué tipo de cosas puedes enviar mediante props?
- Son como argumentos para componentes en React, que se inicializan con valores especificos entre estos incluye a los string, numeros, booleanos, objetos, arrays, funciones y hasta otros componentes.

2. ¿Cuál es la mayor diferencia entre props y state?
- Las propiedades se manejan externamente y no se pueden cambiar directamente, en cambio `state` se maneja internamente dentro de un componente, lo que permite que los componentes mantengan su propia información y lógica. 

3. ¿Cuándo volvemos a renderizar nuestra aplicación?
- Cuando los props cambian, React vuelve a renderizar el componente automaticamente, lo que asegura que la interfaz de usuario refleja los datos actuales.

4. ¿Cuáles son algunos ejemplos de cosas que podríamos almacenar en el state?
- Podemos incluir formularios, menús desplegables o cualquier elemento que pueda ser actualizado dinámicamente.