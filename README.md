# Git

Sistema de control de versiones.

* Permite llevar un historial de los cambios del proyecto.
* Trabajar en equipos sobre el mismo proyecto.

### Crear un repositorio

Sólo se ejecuta una vez por proyecto:
```
$ git init
```

### Borrar un repositorio

```
$ rm -rf .git
```

### Crear un commit

```
$ git add .
$ git commit -m 'La descripción del commit'
```

### Ver el historial de cambios (commits)

```
$ git log
```

### Ver el estado del repositorio

```
$ git status
```

### Ver los cambios desde el último commit

```
$ git diff
```

### Editar el mensaje del último commit

```
$ git commit --amend -m 'Nuevo mensaje'
```

## Publicando a Github

### Crear el remoto

Lo más fácil es copiarlo de las instrucciones que aparecen en Github cuando se crea el repositorio.

```
$ git remote add <name> <url>
```

### Publicar los cambios a Github (repositorio remoto)

```
$ git push -u origin main
```

Las próximas veces que se ejecute el `git push` no es necesario el `-u`


## Temas para la prueba técnica.

* Manejar la línea de comandos (abrirla, navegar por las carpetas, crear una carpeta, abrir la carpeta actual en el editor de texto)
* Manejar el editor de texto (abrir, crear un archivo, cambiar el nombre del archivo, eliminar un archivo)
* Crear un documento HTML
* Utilizar los elementos básicos de HTML (títulos, párrafos, listas, imágenes, tablas, formulario, links, divs)
* Enlazar un archivo CSS y realizar operaciones como: cambiar el fondo, cambiar el color y tamaño de la fuente de un elemento específico. Márgenes, paddings, bordes.
*  JavaScript: 
	* Tipos y operadores.
	* Variables
	* Condicionales
	* Ciclos
	* Funciones
	* Arreglos
	* Cadenas de texto
	* Objetos literales
