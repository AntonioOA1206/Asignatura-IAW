# **TEMA 2**

# Tarea 2.2

### Descargar Imagenes

#### Ubuntu:

![Texto alternativo](/imagenes/tema2/descargarUbuntu.png)

#### mysql

![Texto alternativo](/imagenes/tema2/descargarMysql.png)

#### httpd

![Texto alternativo](/imagenes/tema2/descargarHttpd.png)

#### php

![Texto alternativo](/imagenes/tema2/descargarPhp.png)

#### centos

![Texto alternativo](/imagenes/tema2/descargarCentos.png)

#### debian

![Texto alternativo](/imagenes/tema2/descargarDebian.png)
#### mariadb

![Texto alternativo](/imagenes/tema2/descargarMariadb.png)

#### tomcat

![Texto alternativo](/imagenes/tema2/descargarTomcat.png)

#### jenkins

![Texto alternativo](/imagenes/tema2/descargarJenkins.png)

#### Comprobar que estan todas descargadas:

![Texto alternativo](/imagenes/tema2/descargasComprobacion.png)

# Tarea 2.3
### Arrancar un contenedor de la imagen ubuntu:18.04 al que llamaremos ubuntu. Una vez arrancado realizar las siguiente operaciones

![Texto alternativo](/imagenes/tema2/arrancarUbuntu.png)

### Salir del contenedor y capturar un pantallazo donde se pueda comprobar que ese
contenedor se ha parado

![Texto alternativo](/imagenes/tema2/salirUbuntu.png)

### Rearrancar el contenedor desde tu equipo y capturar un pantallazo donde se pueda
comprobar que está funcionando

![Texto alternativo](/imagenes/tema2/arrancarUbuntu2.png)

### Sin entrar en el contenedor, mostrar por pantalla el fichero /etc/os-release y capturar un
pantallazo del resultado

![Texto alternativo](/imagenes/tema2/ejecutarCatUbuntu.png)

# Tarea 2.4
### Arranca un contenedor que ejecute una instancia de la imagen php:7.3-apache, que se llame web y que sea accesible desde tu equipo en el puerto 8181

![Texto alternativo](/imagenes/tema2/arrancarPhp.png)

### Colocar en el directorio raiz del servicio web de dicho contenedor un fichero llamado index.html con el siguiente contenido:
```html
<h1>HOLA SOY TUNOMBRE</h1>
```

![Texto alternativo](/imagenes/tema2/colocarIndex.png)

### Colocar en ese mismo directorio raiz un archivo llamado index.php con el siguiente contenido:
```php
<?php phpinfo(); ?>
```

![Texto alternativo](/imagenes/tema2/colocarPhp.png)

### Arrancar un contenedor que se llame bbdd y que ejecute una instancia de la imagen mariadb para que sea accesible desde el puerto 3336.

![Texto alternativo](/imagenes/tema2/comandoBbdd.png)

#### Comprobacion del index

![Texto alternativo](/imagenes/tema2/comprobarIndex.png)
#### Comprobacion php

![Texto alternativo](/imagenes/tema2/comprobarPhp.png)

#### Ultima comprobacion

![Texto alternativo](/imagenes/tema2/ultimaComprobacion.png)

# Tarea 2.5

### Partiendo de los contenedores en ejecución de la tarea anterior y ejecutando la orden de docker cli adecuada obtener la siguiente información realizando un pantallazo cada vez:

#### Dirección IP del contenedor web

![Texto alternativo](/imagenes/tema2/direccionIP.png)
#### Redirección de puertos del contenedor web

![Texto alternativo](/imagenes/tema2/redireccionPuertos.png)
#### Dirección IP del contenedor bbdd

![Texto alternativo](/imagenes/tema2/direccionIP2.png)
#### Redirección de puertos del contenedor bbdd

![Texto alternativo](/imagenes/tema2/redireccionPuertos2.png)

# **TEMA 3**

# Tarea 3.2

### 1. Descargar una nueva imagen desde Docker Hub, la imagen Ubuntu:20.04.

![Texto alternativo](/imagenes/tema3/3.2-descargar-ubuntu1.png)
![Texto alternativo](/imagenes/tema3/3.2-descargar-ubuntu2.png)

### 2. Obtener toda la información de esa imagen y volcarla en el fichero info.txt.

![Texto alternativo](/imagenes/tema3/3.2-informacion-imagen-ubuntu-20.04.png)

### 3. Instanciar esa imagen creando un contenedor llamado modulo3.

![Texto alternativo](/imagenes/tema3/3.2-crear-contenedor-modulo3.png)

### 4. Intentar borrar la imagen Ubuntu:20.04. ¿Has podido borrar la imagen? Responde razonadamente.

No se puede borrar la imagen mientras exista un contenedor creado a partir de ella, aunque el contenedor no esté en ejecución. Que el contenedor esté parado no significa que haya dejado de depender de la imagen.

![Texto alternativo](/imagenes/tema3/3.2-intentar-eliminar-imagen-ubuntu-20.04.png)

### 5. Realizar las operaciones necesarias para poder borrar la imagen.

![Texto alternativo](/imagenes/tema3/3.2-eliminar-imagen-ubuntu-20.04.png)

