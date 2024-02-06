# ***INSTALACION WORDPRESS USANDO DOCKER***
## Primero ejecutaremos este comando para que, en caso de tener paquetes instalados de docker, eliminarlos y que no ocurran problemas más adelante.
![](img/1.PNG)
## Ejecutamos todos los comandos con los que añadimos la clave autorizada y luego añadimos unas líneas de comando (no tengo las capturas porque fue cuando daba error por no poner el /ubuntu y perdi las capturas de lo demás).
![](img/3.PNG)
## Instalamos los paquetes de Docker.
![](img/4.PNG)
## Verificamos la instalación ejecutando la imagen hello-world.
![](img/5.PNG)
## Instalamos *compose* y comprobamos la versión.
![](img/6.PNG)
## Creamos el *.env* con las variables para el fichero del paso siguiente.
![](img/7.PNG)
## Configuramos el *.yml* para que permita utilizar tanto **MariaDB**, **php** como **WordPress**.
![](img/8.PNG)
## Verificamos que tanto el *.env* como el *.yml* estan en el mismo directorio.
![](img/9.PNG)
## Vemos que la imagen creada funciona correctamente.
![](img/10.PNG)
## Usando la ip pública de la máquina AWS, nos metemos en el navegador para configurar **WordPress**.
![](img/11.PNG)
![](img/12.PNG)
## Comprobamos que la conexión funciona y WordPress esta conectado a lo creado en los anteriores ejercicios.
![](img/13.PNG)
