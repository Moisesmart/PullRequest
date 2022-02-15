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
