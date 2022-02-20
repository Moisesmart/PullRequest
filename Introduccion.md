
![bitbucket411-blog-1200x-branches2](https://user-images.githubusercontent.com/72433702/153570294-85919312-5c1c-4813-a519-b7027ef2ce96.png)



## El sistema de control de versiones git, ofrece una solución muy conveniente a la hora de llevar control sobre el desarrollo de un proyecto con el cual podemos ver el progreso del trabajo solo con inspeccionar el cambio realizado en cada commit. Los pull request permiten no solo llevar de forma más ordenada las tareas en la etapa del desarrollo, sino también crear propuestas o cambios que puedan ser integrados posteriormente a dicho proyecto.

## Básicamente un pull request es una petición para integrar nuestras propuestas o cambios de código a un proyecto.


### Antes de iniciar es muy importante que tengas en cuenta cómo funciona el Sistema de ramificaciones en git.

### Cuando trabajas en un proyecto propio tal vez te baste con crear una nueva rama en el repositorio, hacer algunos cambios y posteriormente hacer un merge de esta rama en la rama master, por ejemplo puedes trabajar en crear el home de tu aplicación en una rama llamada «front-page» y una vez terminado, puedes incluirla en la rama master con
## `$ git merge front-page`

### Pero, cuando estás trabajando como parte de un equipo, debes ser un poco más cuidadoso, es allí donde entra en juego el uso de los pull request, cada vez que creas un cambio, es recomendable subir al repositorio central la nueva rama de trabajo, digamos «front-page» y con un pull request estarías haciendo una petición de que esta rama sea incluida en master, entonces, de esta forma puedes dar una explicación mucho más detallada de lo que hace tu código (más allá del mensaje del commit) y la persona encargada de la integración puede descargar tu rama, probar los cambios y aprobar o rechazar la petición, según sea el caso, inclusive  dejar un comentario para que hagas algún arreglo si es requerido
