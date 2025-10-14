# EJERCICIO 14
## SAMUEL RUIZ

## PASO 1
1. Lo primero que tendremos que hacer sera entrar en el repositorio dentro **Git-Bash** usando los comandos necesarios.
![Captura1](IAW/Imagen1.png)

## PASO 2
2. Despues Iremos al **GitHub** y crearemos nuestro **Repositorio** en mi caso llamado **Prueba2_Samuel** y tambien habilitaremos la opcion de README.md
![Captura2](IAW/Imagen2.png)

## PASO 3
3. Luego volveremos al **Git-Bash** y haremos un **Git Init** para inicializar un nuevo repositorio en GIT
![Captura3](IAW/Imagen3.png)

## PASO 4
4. Ahora empezaremos a crear los **archivos.txt** usando los comandos: `nano archivo1.txt` - `nano archivo2.txt`  
![Captura4](IAW/Imagen4.png)

## PASO 5
5. Una vez creados los archivos. Otra vez en el **Git-Bash** pondremos los comandos `git add .` para mover los archivos creados a la staging area y luego un `git status` para revisar el estado de los archivos.
![Captura5](IAW/Imagen5.png)

## PASO 6
6. Despues añadiremos un repositorio remoto a un repositorio ya existente gracias al comando `git remote add origin https://USERNAME:TOKEN@github.com/USERNAME/REPO.git`
![Captura6](IAW/Imagen6.png)

## PASO 7
7. Una vez añadido haremos un `git commit -m "texto"` para guardar los cambios al repositorio
![Captura7](IAW/Imagen7.png)

## PASO 8
8. Una vez guardados los cambios los enviamos al repositorio con `git push -u origin master`
![Captura8](IAW/Imagen8.png)

## PASO 9
9. Iremos al **GitHub** para comprobar si ya estan subido los archivos.txt
![Captura9](IAW/Imagen9.png)

## PASO 10
10. Luego conectaremos en el visual studio code con el debian y entraremos dentro del repositorio
![Captura10](IAW/Imagen10.png)

## PASO 11
11.  Ahora haremos un `git clone https://USERNAME:TOKEN@github.com/USERNAME/REPO.git` para tener clonado el repositorio en el visual studio code
![Captura11](IAW/Imagen11.png)

## PASO 12
12. Ahora dentro del **Git-Bash** modificaremos el archivo1 como nos pide en el ejercicio
![Captura12](IAW/Imagen12.png)

## PASO 13
13.  Despues comprobamos los cambios con un `git status`
![Cptura13](IAW/Imagen13.png)

## PASO 14
14. Por ultimo usaremos los comandos `git add .` y `git commit` para confirmar los datos y luego haremos un `git push` para subirlo al repositorio.Tambien hacemos un `git pull` para actualizar la version local del repositorio de DEBIAN