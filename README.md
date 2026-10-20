# **TEMA 2**

# Tarea 2.2

### Descargar Imagenes

#### Ubuntu:

![Texto alternativo](/imagenes/descargarUbuntu.png)

#### mysql

![Texto alternativo](/imagenes/descargarMysql.png)

#### httpd

![Texto alternativo](/imagenes/descargarHttpd.png)

#### php

![Texto alternativo](/imagenes/descargarPhp.png)

#### centos

![Texto alternativo](/imagenes/descargarCentos.png)

#### debian

![Texto alternativo](/imagenes/descargarDebian.png)

#### mariadb

![Texto alternativo](/imagenes/descargarMariadb.png)

#### tomcat

![Texto alternativo](/imagenes/descargarTomcat.png)

#### jenkins

![Texto alternativo](/imagenes/descargarJenkins.png)

#### Comprobar que estan todas descargadas:

![Texto alternativo](/imagenes/descargasComprobacion.png)

# Tarea 2.3 

### Arrancar un contenedor de la imagen ubuntu:18.04 al que llamaremos ubuntu. Una vez arrancado realizar las siguiente operaciones

![Texto alternativo](/imagenes/arrancarUbuntu.png)
 
### Salir del contenedor y capturar un pantallazo donde se pueda comprobar que ese
contenedor se ha parado

![Texto alternativo](/imagenes/salirUbuntu.png)

### Rearrancar el contenedor desde tu equipo y capturar un pantallazo donde se pueda
comprobar que está funcionando

![Texto alternativo](/imagenes/arrancarUbuntu2.png)

### Sin entrar en el contenedor, mostrar por pantalla el fichero /etc/os-release y capturar un
pantallazo del resultado

![Texto alternativo](/imagenes/ejecutarCatUbuntu.png)

# Tarea 2.4

### Arranca un contenedor que ejecute una instancia de la imagen php:7.3-apache, que se llame web y que sea accesible desde tu equipo en el puerto 8181

![Texto alternativo](/imagenes/arrancarPhp.png)

### Colocar en el directorio raiz del servicio web de dicho contenedor un fichero llamado index.html con el siguiente contenido:
``` <h1>HOLA SOY TUNOMBRE</h1>```

![Texto alternativo](/imagenes/colocarIndex.png)

### Colocar en ese mismo directorio raiz un archivo llamado index.php con el siguiente contenido:
```<?php phpinfo(); ?>```

![Texto alternativo](/imagenes/colocarPhp.png)

### Arrancar un contenedor que se llame bbdd y que ejecute una instancia de la imagen mariadb para que sea accesible desde el puerto 3336.

![Texto alternativo](/imagenes/comandoBbdd.png)

#### Comprobacion del index

![Texto alternativo](/imagenes/comprobarIndex.png)

#### Comprobacion php

![Texto alternativo](/imagenes/comprobarPhp.png)

#### Ultima comprobacion

![Texto alternativo](/imagenes/ultimaComprobacion.png)

# Tarea 2.5

### Partiendo de los contenedores en ejecución de la tarea anterior y ejecutando la orden de docker cli adecuada obtener la siguiente información realizando un pantallazo cada vez:

#### Dirección IP del contenedor web

![Texto alternativo](/imagenes/direccionIP.png)

#### Redirección de puertos del contenedor web

![Texto alternativo](/imagenes/redireccionPuertos.png)

#### Dirección IP del contenedor bbdd

![Texto alternativo](/imagenes/direccionIP2.png)

#### Redirección de puertos del contenedor bbdd

![Texto alternativo](/imagenes/redireccionPuertos2.png)
