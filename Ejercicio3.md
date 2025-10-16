# EJERCICIO3
## SAMUEL RUIZ

### PASO 1
1. Lo primero que tendremos que hacer sera poner el comando `git branch` para poder ver en que rama estamos y luego un `git branch primera` para crearla
![Captura1](IAW/Imagen1(ejer3).png)

### PASO 2
2. Ahora una vez creada la rama primera la tendremos que seleccionar con el comando `git checkout primera` y luego un `git branch` para comprobar que estamos en la rama primera
![Captura2](IAW/Imagen2(ejer3).png)

### PASO 3
3. Despues crearemos un archivo en la rama primera `nano ArchivoPrimeraRama`
![Captura3](IAW/Imagen3(ejer3).png)

### PASO 4
4. Una vez creado el archivo haremos un `git add .` y un `git commit -m` para guardarlo
![Captura4](IAW/Imagen4(ejer3).png)

### PASO 5
5. Ahora nos iremos al **GitHub** para comprobar que esta el archivo con lo modificado dentro
![Captura5](IAW/Imagen5(ejer3).png)+

### PASO 6
6. Luego comprobamos que estamos en primera y cambiamos a la rama main `git checkout main` y hacemos un `git merge primera` para fusionar una rama con otra
![Captura6](IAW/Imagen6(ejer3).png)

### PASO 7
7. Ahora borramos la rama primera con el comando `git branch -d primera`
![Captura7](IAW/Imagen7(ejer3).png)

### PASO 8
8. Modificamos el archivo 
![Captura8](IAW/Imagen8(ejer3).png)

### PASO 9
9. Creamos la rama segunda `git branch segunda` y creamos otro archivo en la rama segunda.Una vez creado haremos `git add .`,`git commit -m` y `git push origin segunda`
![Captura9](IAW/Imagen9(ejer3).png)

### PASO 10
10. Hacemos un `git merge segunda` para fusionarla
![Captura10](IAW/Imagen10(ejer3).png)

### PASO 11
11. Aqui vemos el conflicto que se genera
|[Captura11](IAW/Imagen11(ejer3).png)

### PASO 12
12.  Volveremos a la rama main y eliminaremos uno de los dos archivos.Hacemos `git add .`,`git commit -m` y `git push origin main` y por ultimo un `git merge segunda`
![Captura12](IAW/Imagen12(ejer3).png)

### PASO 13
13. Nos vamos al **GitHub** y vemos como aparece la rama segunda y como esta eliminada la rama primera
![Captura13](IAW/Imagen13(ejer3).png)
