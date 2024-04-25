# Tarea Tema 18 - Entornos de desarrollo
## Comandos GIT utilizados:

### *git branch {nombre}*
Con este comando creamos una nueva rama

### *git branch -m {nombre rama} {nuevo nombre}*
Con este comando renombramos una rama existente

### *git branch*
Con este comando podemos observar las ramas disponibles

![git branch](Tema-18/imagenes/image4.png)

### *git checkout {nombre}*
Con este comando podemos cambiar de rama

![git checkout](Tema-18/imagenes/image7.png)

### *git merge {ramaOrigen} {ramaDestino}*
Con este comando fusionamos los cambios de una rama de origen con otro rama destino.

![git merge](Tema-18/imagenes/image6.png)


## Problemas al realizar la fusión de ramas

![alt text](Tema-18/imagenes/image9.png)

Al tratar de realizar una fusión entre archivos que han sido modificados independientemente obtenemos un error, para el que deberemos resolver esos conflictos antes de continuar.

![alt text](Tema-18/imagenes/image8.png)

El editor nos muestra las porciones de código que son diferentes en cada archivo, donde nosotros deberemos de elegir qué cambios queremos conservar para poder fusionar los archivos.