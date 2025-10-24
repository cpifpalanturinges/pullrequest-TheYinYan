# Tarea 6: Generación de un conflicto en git y fichero .gitignore

1. Realicemos un fork del repositorio

![Imagen](/Imagenes/1.png)


2. Clona el repositorio

![Imagen](/Imagenes/2.png)

Abre la terminal y ejecuta el siguiente comando. Esto clonará el repositorio localmente.

	git clone [DIRECCIÓN HTTPS]

Debemos ir al repositorio clonado ejecutando el siguiente comando:

	cd [NOMBRE DEL REPOSITORIO]


3. Crea una rama

Ahora crea una rama usando el comando *git checkout*
	
	git checkout -b [Nombre de la Rama]

	![Imagen](/Imagenes/4.png)


4. Realiza cambios y confírmalos

Has cambios esenciales al proyecto y guárdalos. <br>
Luego ejecuta *git status* , y verás los cambios.

	![Imagen](/Imagenes/5.png)

Agrega esos cambios a la rama recién creada usando el comando git add:

	git add .

Ahora confirma esos cambios utilizando el comando git commit:

	git commit -m "Adding an article to week 02 of articles of the week"	
	
	![Imagen](/Imagenes/6.png)


5. Envía los cambios a GitHub


Para enviar los cambios a GitHub, debemos identificar el nombre del repositorio remoto.

	git remote

Luego de identificar el nombre podemos enviar en forma segura los cambios a GitHub.

	git push origin [Nombre de la Rama]


6. Crea un pull request

Ve a tu repositorio en GitHub y verás un botón llamado "Pull request", has clic en él.

	![Imagen](/Imagenes/7.png)


7. Aceptar un push

	![Imagen](/Imagenes/Aceptamos_El_PullMiguel.png)
	![Imagen](/Imagenes/Aceptamos_El_PullMiguel1.png)
