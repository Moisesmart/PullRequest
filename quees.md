## Un pull request es una petición que el propietario de un fork de un repositorio hace al propietario del repositorio original para que este último incorpore los commits que están en el fork. En el caso que nos ocupa, el usuario aprendegit-user1 le enviará la petición a aalbagarcia para que este último incorpore los commits que tiene en su fork.

## Lo primero que hará el usuario aprendegit-user1 será crear una rama que apuntará al último commit que ha hecho y que contiene las modificaciones a la página de inicio. El procedimiento es el de siempre:

![Voila_Capture2](https://user-images.githubusercontent.com/72433702/153570946-ad60221b-776c-4d78-a528-6d8f18472ea8.png)





 ##   Se selecciona a la izquierda la rama master y se hace clic sobre el último commit de la rama
  ##  Se hace click sobre el icono «Branch»
   ## Se introduce el nombre de la rama, en este maso mycommits
   ## Se hace clic sobre «Create Branch»

## Si se usa la línea de comandos, la secuencia sería:

$ git checkout master
Switched to branch 'master'
$ git checkout -b mycommits
Switched to a new branch 'mycommits'


## Una vez creada la rama, el usuario aprendegit-user1 hace push de la rama «mycommits» a su fork:

![Voila_Capture4](https://user-images.githubusercontent.com/72433702/153573477-d2c4bf99-812e-4089-b0f8-61f254d6147d.png)



## Se selecciona la rama mycommits a la izquierda asegurándonos de que esta queda como rama activa haciendo doble clic sobre ella
## Se selecciona el último commit de la rama
## Se hace clic sobre el icono Push de la bara de herramientas
## En el desplegable, se selecciona en la columna «Push?» la rama mycommits y se marca en la columna de la derecha (Track) la rama local como tracking branch.
## Se hace clic sobre OK.

## La secuencia de comandos sería 

![pull](https://user-images.githubusercontent.com/72433702/154037776-7fc00c34-8d78-443a-b091-1925e3f83fb7.PNG)


## Al terminar, el estado del repositorio es el siguiente:


![Voila_Capture5](https://user-images.githubusercontent.com/72433702/154037910-32926dcb-feec-4ca4-a501-d3694020bd65.png)


## Solicitando el pull request

 ### el usuario aprendegit-user1 accede a su cuenta de github y abre en su navegador la página de su fork https://github.com/aprendegit-user1/fork.


## Una vez hemos accedido, cambiamos a la rama mycommits como se indica en la siguiente captura:Acceder a github y cambiar a la rama mycommits
![Voila_Capture6](https://user-images.githubusercontent.com/72433702/154038189-64b33bad-5a03-4fe0-a8cf-b6859649d077.png)

## Una vez se ha cambiado a la rama mycommits, aprendegit-user1 hace clic sobre el botón «Pull Request»El botón pull request
![Voila_Capture7](https://user-images.githubusercontent.com/72433702/154038314-93399faf-3ba3-4f94-bc33-7842a9799110.png)

## Esta es la pantalla que se presenta a aprendegit-user1:Pantalla para enviar el pull request


![Voila_Capture8](https://user-images.githubusercontent.com/72433702/154038358-3c2f0959-3a98-4650-b66b-91a3ee52a243.png)

## En la parte superior, aprendegit-user1 selecciona la rama que contiene los commits que aalbagarcia (el destinatario del pull request) debe incorporar en su repositorio. En la parte de abajo se ven tres pestañas en las que se puede:

   ## Poner un título y descripción al pull request
   ## Ver los commits que aalbagarcia incorporará al repositorio si acepta el pull request (pestaña Commits)
   ## Ver un diff que los cambios que se incluyen en los commits (pestaña Files Changed)

## Es una buena práctica poner un título y descripción que reflejen el motivo del commit. Estos pull requests los ven todos los colaboradores del proyecto (si el proyecto es público lo ve todo el mundo) Así que aunque aalbagarcia y aprendegit-user1 hayan hablado por teléfono acerca de este pull request, el resto del mundo seguramente no ha escuchado la conversación. Pensando en el resto del equipo, aprendegit-user1 incluye un mensaje descriptivo de qué contiene el pull request. Cuando termina, hace clic sobre el botón «Send Pull Request». Esta es la pantalla a la que aprendegit-user1 llega después de enviarlo:

![Voila_Capture9](https://user-images.githubusercontent.com/72433702/154038556-09b97db3-fcfe-4206-a44b-e62f995ccfbd.png)

## La captura es bastante sencilla de entender. Vemos el título y descripción introducidos por aprendegit-user1, los commits y una interfaz para intercambiar comentarios con el equipo.

## Aunque en pequeño, se nos indica qué es lo que tendríamos que hacer para añadir commits a este pull request: enviar más commits a la rama «mycommits» del fork de aprendegit-user1.

## ¿Porqué podemos necesitar añadir más commits? Imagínate que el equipo revisa el pull request y se determina que todavía queda trabajo pendiente de hacer. ¿Cómo se procede? aprendegit-user1 continúa el trabajo en la rama rama «mycommits» de su fork y cuando termina lo sube a su repositorio remoto. El pull request se actualiza y todo el equipo puede ver el nuevo código. Esto lo veremos en detalle en otro artículo, de momento, seguimos con el proceso.

## Aceptando el pull request

### Cuando aprendegit-user1 envía el pull request, Github envía al propietario un email avisándole de que tiene un pull request listo para revisar. En este caso, el usuario aalbagarcia recibe el email, accede a su cuenta de Github y va a su repositorio https://github.com/aprendegit/fork:

![Voila_Capture10](https://user-images.githubusercontent.com/72433702/154038786-04500815-4e92-4cc2-a782-bee4b95b5d34.png)

### En esta pantalla, seleccionamos la pestaña «Pull Requests» y accedemos a una interfaz que nos muestra todos los que tenemos. Dado que este es el primero, en este listado seleccionamos el único que hay:Listado de pull requests del repositorio
![Voila_Capture11](https://user-images.githubusercontent.com/72433702/154038988-1f6b50de-14d8-414f-bccb-b4254eeb7a71.png)

### Cuando aalbagarcia selecciona «Añadiendo logotipo», accede a una pantalla muy parecida a la que hemos visto con el usuario aprendegit-user1. En la siguiente captura indico cuáles son las diferencias:
![Voila_Capture12](https://user-images.githubusercontent.com/72433702/154039050-3649ab90-1a11-42b8-bd3c-9ee52d163802.png)

### Las diferencias son:

   ### Existe un botón «Merge pull request» que el propietario aalbagarcia utilizará para incorporar los commits al repositorio
   ### Existe un botón «Close» que el propietario utiliza para cerrar el pull request sin incorporar los cambios

### Una vez revisado el código y confirmado que todo está bien, aalbagarcia hace clic sobre el botón «Merge Pull Request». En ese momento Github le pedirá que introduzca un comentario para el merge commit. Una vez introducido, aalbagarcia hace clic sobre el botón «Commit merge» y ya está, Github automáticamente cierra el pull request. También envía un email a los dos interesados (aalbagarcia y aprendegit-user1) avisándoles de que se han incorporado los cambios en el repositorio.

## Si volvéis a la página de commits del repositorio en github (https://github.com/aprendegit/fork/commits/master) veréis que tras hacer el pull request, aparece un nuevo commit en el repositorio:
![Voila_Capture15](https://user-images.githubusercontent.com/72433702/154039220-501ea236-98f2-4fe2-8281-68a7af6ef212.png)


