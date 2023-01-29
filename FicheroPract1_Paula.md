# Práctica 1 PAT
## Paula Pijoan Gros
### 3B GITT+BA

I.	Prerrequisitos 

Se ha de tener una cuenta de Github y con la cuenta de usuario, se hará un fork sobre el repositorio: https://github.com/gitt-3-pat/hello-world 

 
![image](https://user-images.githubusercontent.com/98013115/215350851-f374ab05-fb23-4919-922f-6fb67ade9afc.png)

 ![image](https://user-images.githubusercontent.com/98013115/215350873-42077fe9-6ea5-4716-a024-670ace018e3d.png)


II.	Desarrollo de la práctica

Comandos para probar:

1.	Git clone

El comando git clone sirve para clonar o copiar un repositorio existente en un nuevo directorio, es decir en otra ubicación. Para realizar la copia es necesario obtener el URL del repositorio que quieres. En caso de no tener permisos por parte de la persona que estas clonando el respositorio, primero hay que crear un Fork, haciendo una copia del repositorio que está publicado en Github y despues ya puedes clonar y realizar los cambios que quieras. Al realizar el Fork, el repositorio pertenece a tu usuario, y por tanto se encuentra en tu cuenta por lo que tienes permisos de realizar los cambios que quieras y actualizar tu repositorio. 

 ![image](https://user-images.githubusercontent.com/98013115/215350880-a757b7da-6f36-4761-a109-e3a03542cf98.png)


2.	Git Status

El comando git status nos permite saber el estado en el que se encuentra nuestro repositorio de trabajo. De esta manera, uno puede identificar si se está trabajando con los últimos cambios realizados, o si es necesario actualizarlos mediante un commit. Adicionalmente, el comando permite ver que archivos están modificados, cuales se crearon y cuáles han sido eliminados. Una vez se ejecuta el comando, se devuelve un resumen con información acerca del estado, la rama en la que se encuentra el individuo y cuales son los archivos que tienen cambios. 

 ![image](https://user-images.githubusercontent.com/98013115/215350887-22f12683-88ba-4e33-ab75-1d0875de99d0.png)


En este caso, se observa que todo esta en up to date y que estoy en main. Sin embargo, si con los otros comandos añado un fichero de prueba, observaríamos esto:

 ![image](https://user-images.githubusercontent.com/98013115/215350893-6bd007d4-152d-4e4c-bf6b-6dc0c4e493d2.png)


Observaría que sería necesario hacer un commit. 

Una vez que hago el commit, se vuelve a cambiar el status:
 
 ![image](https://user-images.githubusercontent.com/98013115/215350908-21190b3e-f03c-40da-af86-f309a4570166.png)


3.	Git add

El comando git add, mueve el fichero que se especifique al área de preparación. Por tanto, de esta manera se incluye en el repositorio en la siguiente confirmación.  

En este caso, se observa que se ha realizado este proceso con el ejemplo anterior mediante el fichero Prueba.txt para que apareciese en el status. 

4.	Git commit

El comando commit nos permite guardar todos los cambios que hayan sido realizados en la zona de preparación. Por ejemplo, mediante el comando git add del cual se mencionaba previamente. Adicionalmente, se incluye una pequeña descripción o comentario del usuario. En este momento se encuentra en la capa de staging. 

Una vez más, observamos que mediante la explicación del git status, se ha realizado un commit por lo que ha cambiado el status, guardándose los cambios que se habían realizado en la zona de preparación. 

5.	Git Push

El comando git push nos permite cargar el archivo que anteriormente hemos guardado mediante el commit para subirlo al repositorio remoto de github. De esta manera se carga el contenido del repositorio de manera local a un repositorio remoto.

Al hacer push, se observa que aparece en el repositorio.

![image](https://user-images.githubusercontent.com/98013115/215350930-4eb39f06-d924-4bd0-8da4-fb9ca7c4c0dd.png)

6.	Git Checkout

Por último, el comando git checkout tiene varias posibles funciones. En primer lugar, nos permite recuperar archivos, volviendo a una versión anterior de un commit o historial de las versiones del programa. Adicionalmente, el comando git checkout permite moverse entre las ramas. Por ejemplo, uno se puede mover del main a una que creemos. 


III.	Comandos adicionales

1.	Git branch new_branch
Este comando esta relacionado con el git checkout que se ha definido previamente. En este caso podemos crear una nueva rama a nuestro repositorio, y despues, mediante el git checkout nos podemos cambiar entre ramas. Adicionalmente, existe la posibilidad de poder visualizar las ramas existentes dentro del repositorio y saber en la que nos encontramos mediante el comando git branch. 

 ![image](https://user-images.githubusercontent.com/98013115/215350937-6862c88c-2cc6-4ec9-9f1a-20660056d151.png)


2.	Git pull

El comando git pull nos permite descargar en el repositorio local la última versión que existe y esta subida en el repositorio remoto. De esta manera, se nos permite trabajar con los cambios más recientes pudiendo extraer y descagar el contenido. 

 ![image](https://user-images.githubusercontent.com/98013115/215350945-49210979-c67b-4189-a28a-d4abb6584626.png)

3.	Git rm

El comando git rm es un comando muy simple e intuitivo que nos permite eliminar un archivo dentro del repositorio. 

En este caso, borramos el fichero prueba realizado anteriormente:

 ![image](https://user-images.githubusercontent.com/98013115/215350953-58fd597c-3c8c-4aaa-bad4-115cb544842c.png)


4.	Git revert 

El comando git revert nos permite deshacer cambios que hemos realizado. Es esencial tener cuidado para asegurar de que no se borra lo que uno quiere. Para hacer el revert es necesario ver el historial de commits. Esto se puede hacer mediante el git log - - oneline, donde se encuentran las distintos commits asociados a un número. Para realizar el commit se selecciona el codigo junto al commit que uno desea, pudiendo por tanto deshacer esos cambios. 

![image](https://user-images.githubusercontent.com/98013115/215350959-d1fb5bc0-ad16-40ec-8ad3-95c3202b7761.png)

 
En caso de querer revertir cualquier cambio, se usaría el comando “git revert ---- (numero)”

5.	Git init

El comando git init se usa para inicializar o crear un repositorio local vacio de Git. En este caso, nos puede servir tanto para convertir un proyecto ya existente en un repositorio de GitHub o inicializar un nuevo repositorio que este vacío. 


IV.	Instalación de las herramientas necesarias

1.	Docker

 ![image](https://user-images.githubusercontent.com/98013115/215350974-5a56c14f-7971-4fa6-a106-d2c528fa1468.png)


2.	Java

 ![image](https://user-images.githubusercontent.com/98013115/215350979-9a91d0c4-8f0d-4733-a9f5-b741102a2bff.png)


3.	Maven

 ![image](https://user-images.githubusercontent.com/98013115/215350983-da430a80-64b9-48bf-95ff-d23d2046cf9b.png)
 
 4. Intellij

![image](https://user-images.githubusercontent.com/98013115/215351000-d485e2dd-a7f6-484b-b04b-432d00925a1c.png)


