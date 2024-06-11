
## ¿Qué es el control de versiones?
- Es un sistema que registra los cambios realizados en un archivo o conjunto de archivos a lo largo del tiempo
- Permite a los desarrolladores colaborar y trabajar simultáneamente en proyectos, permite ver que cambios se realizaron y revertir versiones anteriores.

## ¿Qué es “clone” en Git?
- El comando `clone` crea una copia local de un repositorio remoto.
- Es útil cuando deseas trabajar en un proyecto existente que se encuentra en un servidor remoto.

## ¿Cuál es el comando para rastrear y preparar archivos?
- Este comando sirve para añadir o rastrear commit usamos `git add` puede añadir archivos específicos
    - `Añadir un archivo específico:`
git add nombre_del_archivo
    - `Añadir todos los archivos nuevos o modificados en el directorio actual:`
git add .

## ¿Cuál es el comando para tomar una instantánea de los archivos modificados?
- El comando para tomar una instantánea de los archivos rastreados __(añadidos)__ es `git commit`
- Este comando guarda los cambios realizados en el repositorio local. Generalmente se usa con la opción `-m` para incluir un mensaje que describe los cambios realizados:

## ¿Cuál es el comando para enviar los archivos modificados a GitHub?
<<<<<<< HEAD
- El comando `git push` sube el contenido de un repositorio local a un repositorio central. Dado que este comando sobrescribe los cambios, solo debe ejecutarse con una rama vacía como objetivo.
=======
- El comando `git push` sube el contenido de un repositorio local a un repositorio central. Dado que este comando sobrescribe los cambios, solo debe ejecutarse con una rama vacía como objetivo.
>>>>>>> d862c409ad54a970a0f252911407203519e12f2e
