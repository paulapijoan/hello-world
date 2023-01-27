I.	Prerrequisitos 

Se ha de tener una cuenta de Github y con la cuenta de usuario, se hará un fork sobre el repositorio: https://github.com/gitt-3-pat/hello-world 

 

 

II.	Desarrollo de la práctica

Comandos para probar:

1.	Git clone

El comando git clone sirve para clonar o copiar un repositorio existente en un nuevo directorio, es decir en otra ubicación. Para realizar la copia es necesario obtener el URL del repositorio que quieres. En caso de no tener permisos por parte de la persona que estas clonando el respositorio, primero hay que crear un Fork, haciendo una copia del repositorio que está publicado en Github y despues ya puedes clonar y realizar los cambios que quieras. Al realizar el Fork, el repositorio pertenece a tu usuario, y por tanto se encuentra en tu cuenta por lo que tienes permisos de realizar los cambios que quieras y actualizar tu repositorio. 

 

2.	Git Status

El comando git status nos permite saber el estado en el que se encuentra nuestro repositorio de trabajo. De esta manera, uno puede identificar si se está trabajando con los últimos cambios realizados, o si es necesario actualizarlos mediante un commit. Adicionalmente, el comando permite ver que archivos están modificados, cuales se crearon y cuáles han sido eliminados. Una vez se ejecuta el comando, se devuelve un resumen con información acerca del estado, la rama en la que se encuentra el individuo y cuales son los archivos que tienen cambios. 

 

3.	Git add

El comando git add, mueve el fichero que se especifique al área de preparación. Por tanto, de esta manera se incluye en el repositorio en la siguiente confirmación.  



-	PROBAR CON UN FICHERO

4.	Git commit

El comando commit nos permite guardar todos los cambios que hayan sido realizados en la zona de preparación. Por ejemplo, mediante el comando git add del cual se mencionaba previamente. Adicionalmente, se incluye una pequeña descripción o comentario del usuario. En este momento se encuentra en la capa de staging. 


5.	Git Push

El comando git push nos permite cargar el archivo que anteriormente hemos guardado mediante el commit para subirlo al repositorio remoto de github. De esta manera se carga el contenido del repositorio de manera local a un repositorio remoto.


6.	Git Checkout

Por último, el comando git checkout tiene varias posibles funciones. En primer lugar, nos permite recuperar archivos, volviendo a una versión anterior de un commit o historial de las versiones del programa. Adicionalmente, el comando git checkout permite moverse entre las ramas. Por ejemplo, uno se puede mover del main a una que creemos. 


III.	Comandos adicionales

1.	Git branch new_branch
Este comando esta relacionado con el git checkout que se ha definido previamente. En este caso podemos crear una nueva rama a nuestro repositorio, y despues, mediante el git checkout nos podemos cambiar entre ramas. Adicionalmente, existe la posibilidad de poder visualizar las ramas existentes dentro del repositorio y saber en la que nos encontramos mediante el comando git branch. 

2.	Git pull

El comando git pull nos permite descargar en el repositorio local la última versión que existe y esta subida en el repositorio remoto. De esta manera, se nos permite trabajar con los cambios más recientes pudiendo extraer y descagar el contenido. 

3.	Git rm

El comando git rm es un comando muy simple e intuitivo que nos permite eliminar un archivo dentro del repositorio. 

4.	Git revert 

El comando git revert nos permite deshacer cambios que hemos realizado. Es esencial tener cuidado para asegurar de que no se borra lo que uno quiere. Para hacer el revert es necesario ver el historial de commits. Esto se puede hacer mediante el git log –oneline, donde se encuentran las distintos commits asociados a un número. Para realizar el commit se selecciona el codigo junto al commit que uno desea, pudiendo por tanto deshacer esos cambios. 

5.	Git init

El comando git init se usa para inicializar o crear un repositorio local vacio de Git. En este caso, nos puede servir tanto para convertir un proyecto ya existente en un repositorio de GitHub o inicializar un nuevo repositorio que este vacío. 



IV.	Instalación de las herramientas necesarias

1.	Docker

 


2.	Java

 

3.	Maven

 

4. Intelij

 

